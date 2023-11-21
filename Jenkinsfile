pipeline {
    /*
    * TODO: Implement pipeline stages/steps
    *   See documentation: https://www.jenkins.io/doc/book/pipeline/syntax/#stages
    */
    agent any
    stages {
        stage("build") {
            steps {
                sh 'echo "Building..."'
                sh './gradlew assemble'
            }
        }

        stage("test") {
            steps {
                sh 'echo "Testing..."'
                sh './gradlew test'
            }
        }

    }
}
