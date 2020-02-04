pipeline {
    agent august

    stages {
        stage('Build') {
            steps {
                echo 'Building HelloWorld.java..',
                javac HelloWorld.java,
                echo 'Build Success!'
            }
        }
        stage('Run') {
            steps {
                echo 'Running HelloWorld.class..',
                java HelloWorld,
                echo 'Running Success!'
            }
        }
    }
}
