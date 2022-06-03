pipeline {
    agent {
        label "demoAgent"
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building..---hyeminshin99 agent!'
            }
        }
        stage('Test') {
            steps {
                echo '202206031824 :current time'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
    
    post {
        always {
            echo '202206031824 pipeline done!!!!'
        }
    }
}
