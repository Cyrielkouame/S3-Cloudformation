pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation deploy --template-file S3.yml --stack-name valaba"
              }
             }
            }
            }
