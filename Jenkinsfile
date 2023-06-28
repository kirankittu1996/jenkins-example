


pipeline {
    agent any

    stages {

        stage ('scm checkout){
               echo "pulling changes from the branch"
               git url: 'https://github.com/kirankittu1996/jenkins-example.git'
               }
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
