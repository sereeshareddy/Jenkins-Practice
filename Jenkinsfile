pipeline {
    agnet { node { label 'AGENT-1'} }
    agent any 
    stages {
        stage('Build') { 
            steps {
                 echo 'Building..'
            }
        }
        stage('Test') { 
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') { 
            steps {
                echo 'Deploying..'
            }
        }
    }
}

post {
         always{
            
            echo "I will always run whether job is success or not"
         }
         success{
            echo " I will run the failre"
         }
}