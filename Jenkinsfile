pipeline {
    agent any
    environment{
     /*   PATH = "C:\\Program Files\\Git\\bin:$PATH:c:\\Users\\venpr\\code\\spring-petclinic"
	M2_HOME = "C:\\Users\\venpr\\code\\spring-petclinic"
        JAVA_HOME="C:\\Program Files\\java\\jdk-17" */
    }
    stages {
        stage("Maven Build") {
            steps {
                echo "PATH = ${PATH}"
                echo "M2_HOME = ${M2_HOME}"
		sh 'mvnw clean package'

	          }     
             }
	 }
	 }
