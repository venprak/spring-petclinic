pipeline {
    agent any
    environment{
        PATH = "$PATH:/c/Users/venpr/code/spring-petclinic"
	M2_HOME = "/c/Users/venpr/code/spring-petclinic"
    }
    stages {
        stage("Maven Build") {
            steps {

	   
                echo "PATH = ${PATH}"
                echo "M2_HOME = ${M2_HOME}"
                 
		bat 'mvnw  clean package'
            

	          }     
             }
	 }
	 }
