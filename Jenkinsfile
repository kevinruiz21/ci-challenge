pipeline {
    stages {
        stage('build and deploy SUT') {
            steps {
                sh "echo 'building SUT....'"
                sh 'sleep 10000'
                sh "echo 'deploying SUT....'"
                sh 'sleep 10000'
            }
        }
        stage("Execute Automation Testing"){
            steps {
                sh 'echo testing'
                sh './gradlew test aggregate'
            }
        }
    }
}