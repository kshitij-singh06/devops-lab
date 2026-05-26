pipeline{
    agents any

    stages{
        stage('clone'){
            steps{
                git clone ""
            }
        }

        stage('intall'){
            steps{
               bat 'npm install'
            }
        }

        steps('run'){
            steps{
                bat 'npm start'
            }
        }
        steps('test'){
            steps{
                bat 'npm test'
            }
        }

    }
}