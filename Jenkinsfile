pipeline {  
    agent any  
        stages {  
       	    stage("git_checkout") {  
           	    steps {  
              	    sh '''mvn validate
                          mvn compile
                          mvn test
                          mvn package'''
              	    }  
         	    } 
        }
}
