pipeline {
    agent any

    stages {
		stage ('Build trigger') {
			
			steps {
			
					 echo "Hello, new changes are added new changes"

				}

		}
		
        stage ('Compile Stage') {

            steps {
                
                     bat "mvn clean compile"
                }
            
        }

        stage ('Testing Stage') {

            steps {
                
                     bat "mvn test"
                }
            
        }

        stage ('Deployment Stage') {
            steps {
                
                     bat "mvn deploy"
                }
            
        }
    }
}