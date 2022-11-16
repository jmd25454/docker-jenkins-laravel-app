pipeline {
    agent any
    
    stages {
        stage("build") {
            steps {
                echo 'building the application...'
            }
        } 
        
        stage("test") {
            steps {
                echo 'testing the application...'
            }
        } 
        
        stage("deploy") {
            steps {
                echo 'deploying the application...'
            }
        }
        stage("deployed") {
            steps {
                echo 'Application deployed!'
            }
        }
    }
}
