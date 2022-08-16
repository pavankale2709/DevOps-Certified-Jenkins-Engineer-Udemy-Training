pipeline {
      agent any
      stages {
            stage('Init') {
                  steps {
                        echo 'Hi, this is Pavan'
                        echo 'We are Starting the Testing'
                  }
            }
            stage('Build') {
                  steps {
                        echo 'Building Sample Maven Project'
                  }
            }
            stage('Deploy QA') {
                  steps {
                        echo "Deploying in Staging Area"
                  }
            }
            stage('Deploy Staging') {
                  steps {
                        echo "Deploying in Production Area"
                  }
            }
            stage('Deploy Production') {
                  steps {
                        echo "Deploying in Production Area"
                  }
            }
      }
}
