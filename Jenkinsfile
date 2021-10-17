pipeline {
    agent any
    stages {
        stage("Build") {
            steps {
                sh "sudo npm install"
                sh "sudo npm run build"
            }
        }
    stage("Deploy") {
        steps {
            sh "sudo rm -rf /var/www/reactpwa"
            sh "sudo cp -r ${3.88.179.91}/build/ /var/www/reactpwa/"
            }
        }
    }
}
