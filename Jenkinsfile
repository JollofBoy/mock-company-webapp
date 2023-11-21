pipeline {
    /*
    * TODO: Implement pipeline stages/steps
    *   See documentation: https://www.jenkins.io/doc/book/pipeline/syntax/#stages
    */
    agent any
    stages {
        stage("build") {
            steps {
                /* I don't know how this works so I need to check that the building actually works */
                echo "Building..."
                ./gradlew assemble
            }
        }

        stage("test") {
            steps {
                /* the same as for the building comment */
                echo "Testing..."
                ./gradlew test
            }
        }

        /* there may be a deploy stage that would need to be made
        stage("deploy") {
            steps {
                // do something here to make the deployment work
            }
        }
        */
    }
}
