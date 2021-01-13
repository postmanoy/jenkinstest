pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo "Hello, nice to meet you."
                echo 'test'
            }
        }
        stage('ping') {
            steps {
                sh 'ping -c 4 cloudone.trendmicro.com'
            }
        }
    }
}
