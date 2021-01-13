pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo "Hello, nice to meet you."
            }
        }
        stage('ping') {
            steps {
                sh 'nslookup cloudone.trendmicro.com'
            }
        }
    }
}
