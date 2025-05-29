pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Compile the Java code
                bat 'javac HelloWorld.java'
            }
        }
        stage('Run') {
            steps {
                // Run the compiled Java code
                bat 'java HelloWorld'
            }
        }
    }
}
