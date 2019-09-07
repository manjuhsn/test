pipeline {
  agent any
  stages {
    stage('Script_pipeline') {
      steps {
        sh '''pipeline {
    agent any 

    stages {
        stage(\'Build Assets\') {
            agent any 
            steps {
                echo \'Building Assets\'
            }
        }
        stage(\'Test\') {
            agent any
            steps {
                echo \'Testing stuff...\'
            }
        }
    }
}
'''
        }
      }
    }
  }