pipeline {
     agent any 

     tools {
        maven 'maven-3'
     }

     stages {

      stage('Build') {

         steps {

          sh 'mvn clean package'
}
}

      stage('Deploy') {

        steps {
           sh 'java -jar target/*.jar &'
     }
   }
  }
}
