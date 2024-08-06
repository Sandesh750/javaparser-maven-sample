pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build App'
            }
        }
       stage('Test') {
            steps {
                echo 'Test App'
            }
        }
       stage('Deploy') {
            steps {
                echo 'Deploy App'
            }
        }
      
    }

    post
    {
        always
        {
            emailext body: 'Pipeline passed', subject: 'Pipeline Status', to: 'timepass8035@gmail.com'
                
        }
    }
}
