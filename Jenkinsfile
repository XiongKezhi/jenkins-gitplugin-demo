pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building HelloWorld.java..'
                sh 'javac HelloWorld.java'
                echo 'Build Success!'
            }
        }
        stage('Run') {
            steps {
                echo 'Running HelloWorld.class..'
                sh 'java HelloWorld'
                echo 'Running Success!'
            }
        }
    }
}
