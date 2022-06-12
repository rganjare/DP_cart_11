@Library('DP_shared-library@main') _

pipeline {
   agent any

   stages{
       stage ("Lint Check"){
           steps {
               script{
                sample.lintChecks()
               }
           }  
       }
   }
}
