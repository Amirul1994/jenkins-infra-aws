pipeline {
    agent any
    tools {
        jdk 'JDK-17'
        nodejs 'NODE-18'
    }
    environment {
        DOCKER_IMAGE='simple-react-app'
    }
    options{
        timeout(time:30, unit:'MINUTES')
    }
    stages{
        stage('Clean Workspace'){
            steps{
                cleanWs()
            }
        }
     }
}
