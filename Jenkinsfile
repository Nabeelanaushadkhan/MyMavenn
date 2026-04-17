pipeline{
agent any
tools{
   maven 'MyMaven'
   }
   stages{
   stage('Build & Compile'){
   steps{
   sh 'mvn clean package'
   }
   }
   stage('Test'){
   steps{
   sh 'mvn test'
   }
   }
   stage('Run'){
   steps{
   sh 'java -jar target/*.jar'
   }
   }
   }
   }
   
