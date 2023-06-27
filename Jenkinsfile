
properties([parameters([choice(choices: 'master\nnewbranch\nnewbranch-1', description: 'Select a branch to build', name: 'branch')])])

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
