pipeline{

    agent any

// uncomment the following lines by removing /* and */ to enable
    tools{
       nodejs 'nodejs'
    }
   

    stages{
        stage('compile'){
            steps{
                echo 'this is the compile job'
                sh 'uptime'
                     }
        }
        stage('test'){
            steps{
                echo 'this is the test job'
                sh 'npm test'
                          }
        }
        stage('package'){
            steps{
                echo 'this is the package job'
                sh 'uptime'
            }
        }
    }
    
    post{
        always{
            echo 'this is my dojo pipeline...'
        }
        
    }
    
}
