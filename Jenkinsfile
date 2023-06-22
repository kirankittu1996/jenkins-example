pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {
                 
                    echo 'Hello World'
                
            }
        }

        stage ('Testing Stage') {

            steps {
                 
                    echo 'mvn test'
                
            }
        }


        stage ('Deployment Stage') {
            steps {
                
                    echo 'mvn deploy'
                
            }
        }
    }
}
