
properties([parameters([choice(choices: 'master\nnewbranch\nnewbranch-1', description: 'Select a branch to build', name: 'branch')])])

pipeline {
    agent any

    stages {

        stage ('scm checkout){
               echo "pulling changes from the branch ${params.branch}"
               git url: 'https://github.com/kirankittu1996/jenkins-example.git', branch: "${params.branch}"
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
