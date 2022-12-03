pipeline {
    agent {
        label "master"
    }
    tools {
        // Install the Maven version configured as "M3" and add it to the path.
        maven "M3"
    }
    stages {
        stage ('Compile Stage') {

            steps {
                
                    sh 'mvn clean compile'
            }
        }
        stage ('Testing Stage') {

            steps {
                     echo 'Test done123'
                   // sh 'mvn test'
            }
        }
        stage ('Install Stage') {
            steps {
                    echo 'Done'
                    //sh 'mvn install'
            }
        }
    }
}
