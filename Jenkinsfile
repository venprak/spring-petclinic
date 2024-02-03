pipeline {
    agent any
    environment{
        PATH = "$PATH:c:\Users\venpr\code\spring-petclinic"
	M2_HOME = "c:\Users\venpr\code\spring-petclinic"
        JAVA_HOME="C:\Program Files\Common Files\Oracle\Java"
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
