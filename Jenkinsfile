
@Library('roshan_shared_library') _

pipeline {
    agent any
    stages{
        stage('one'){
            steps{
              welcome()
            }
        }
        stage('two'){
            steps{
              script{
                  welcome.sum(10,10)
                  welcome.mul(20,20)

              }
            }
        }
    }
}
