pipeline {
    agent any
    stages {
        stage ('build') {
            agent {
                docker "imagename1"
            }
            steps {
                echo 'Build stage'
        }
    }
    stage ('Deploy') {
        agent {
            docker "imagename2"
        }
        steps {
            sh 'date'
            }
        }
    }
}
