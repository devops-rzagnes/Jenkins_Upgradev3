pipeline {
      agent any
      stages {
            stage('Init') {
                  steps {
                        echo 'Hi, this is Razavi from LevelUp360'
                        echo 'We are Starting the Testing'
                  }
            }
            stage('Build') {
                  steps {
                        echo 'Building Sample Maven Project...@ $(date)'
                  }
            }
            stage('Deploy') {
                  steps {
                        echo "Deploying in Staging Area...@ $(date)"
                  }
            }
            stage('Deploy Production') {
                  steps {
                        echo "Deploying in Production Area...@ $(date)"
                  }
            }
      }
}