pipeline{
agent any
tools{
   mvn 'MyMaven'
   }
   stages{
   stage('Build & Compile'){
   steps{
   sh 'mvn clean package'
   }
   }
   stage('Run'){
   steps{
   sh 'java -jar target/*.jar'
   }
   }
   }
   }
   
