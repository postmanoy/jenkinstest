pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo "Hello World!"
                echo 'test1'
            }
        }
        stage('ping') {
            steps {
                sh 'ping -c 4 cloudone.trendmicro.com'
            }
        }
    }
}
