
pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('install-jenkins-cli') {
            steps {
                echo 'installing-jenkins-cli'
               sh "java -jar /home/jenkins/jenkins-cli.jar -s http://jenkinserver.mycompany.com:8080/jenkins/ -auth teeadmin:Kala8Kuta list-plugins"
                
            }
        }
    }
}
