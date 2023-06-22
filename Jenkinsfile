pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {
                withMaven(maven : 'mymaven') {
                    echo 'Hello World'
                }
            }
        }

        stage ('Testing Stage') {

            steps {
                withMaven(maven : 'mymaven') {
                    sh 'mvn test'
                }
            }
        }


        stage ('Deployment Stage') {
            steps {
                withMaven(maven : 'mymaven') {
                    sh 'mvn deploy'
                }
            }
        }
    }
}
