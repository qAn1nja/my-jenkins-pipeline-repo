pipeline {
    
    agent any
    stages {
        stage('Example'){
            input{
                message "Should we continue?"
                ok "Yes, we should"
            }
            steps{
                echo "${BUILD_NUMBER}"
            }
        }
        stage('Build'){
            echo 'Building'
        }
        }           
    } //end of pipeline
