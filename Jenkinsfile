pipeline {
    agent { label "dev" }

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