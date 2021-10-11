pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        } 
        stage('Build') {
            steps {
                echo 'Building'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing'
            }
        }
        
              timeout(unit: 'SECONDS', time: 5) {
        stage('Release') {
            steps {
                 sleep 0
                echo 'Releasing'
            }
        }
              }
    }
}
/*node {

              timeout(unit: 'SECONDS', time: 5) {
        stage("One"){
            sleep 0
            echo 'hello'
        }
}*/
}
