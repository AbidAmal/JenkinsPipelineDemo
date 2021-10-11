pipeline {
    agent any
   options{
    timeout(unit: 'SECONDS', time: 5) 
}
    stages {
        stage('Hello') {0
            steps {
                sleep 1
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
        

        stage('Release') {
            steps {
             
                echo 'Releasing'
            }
        }

    
}
 
}
