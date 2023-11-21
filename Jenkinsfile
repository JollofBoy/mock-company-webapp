pipeline {
    /*
    * TODO: Implement pipeline stages/steps
    *   See documentation: https://www.jenkins.io/doc/book/pipeline/syntax/#stages
    */
    agent any
    stages {
        stage("build") {
            steps {
                echo "Building..."
                ./gradlew assemble
            }
        }

        stage("test") {
            steps {
                echo "Testing..."
                ./gradlew test
            }
        }

//         // there may be a deploy stage that would need to be made
//         stage("deploy") {
//             steps {
//                 // do something here to make the deployment work
//             }
//         }
//
    }
}
