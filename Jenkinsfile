dock {
      agent any
      stages {
            stage('Clone Repository') {
                  steps {
                        echo 'Hi, this is Anshul from LevelUp360'
                        echo 'We are Starting the Testing'
                        checkout scm
}
            }
            stage('Build image') {
                  steps {
                        echo 'Building Sample docker Project'
                  app = docker.build("rupsdan/webapp12")
                  }
            }
            stage('Test image') {
                  steps {
                        echo "Deploying in Staging Area part 1"
                  }
            }
            stage('Deploy Production') {
                  steps {
                        echo "Deploying in Production Area part 2"
                  }
            }
            stage('Deploy Production  1') {
                  steps {
                        echo "Deploying in Production Area part 3"
                  }
            }
