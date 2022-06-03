pipeline {
    agent {
        label "demoAgent"
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo '202206031808'
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
            echo '202206031808 pipeline done!!!!'
        }
    }
}
