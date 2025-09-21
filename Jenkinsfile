pipeline {
    agent { label "dev" }

    environment {
        environment {
            FLASK_SERVER = "172.16.75.129"
            APP_NAME = "flask-deployment"
            DOCKER_IMAGE = "flask-deployment:latest"
        }

        stages {
            stage('Code Clone') {
                steps {
                    git branch: 'main',
                        url: "https://github.com/Shiyas9961/flask-deployment.git"
                }
            }

            stage('Build Stage') {
                steps {
                    echo "This is building"
                }
            }
        }
    }
}