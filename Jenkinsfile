pipeline {
    agent {
        label 'dev'  // Specifies the agent where this pipeline will run
    }

    stages {
        stage('build') {
            steps {
                echo 'build stage working ....'
            }
        }

        stage('Test') {
            steps {
                echo 'test stage working....'
            }
        }

        stage('deploy') {
            steps {
                echo 'deploying....'
            }
        }
    }
}
