

pipeline {
    agent any

    tools {
        jdk 'JDK21'
        maven 'MAVEN'
    }

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Build') {
            steps {
                bat 'mvn clean package'
            }
        }

        stage('Test') {
            steps {
                bat 'mvn test'
            }
        }
    }
}

            }
        }
    }
}
