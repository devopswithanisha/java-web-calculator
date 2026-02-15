pipeline {
     any agent 

     tools {
        maven 'maven-3'
     }

     stages {

      stage('Build') {

         steps {

          sh 'mvn clean package & java'
}
}

      stage('Deploy') {

        steps {
           sh 'java -jar /target/*.jar &'
}
}
}
}
