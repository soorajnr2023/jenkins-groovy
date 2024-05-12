pipeline{
agent any
stages{
 stage('Printing a message '){
steps{
    echo"Job is building"
    sh 'mvn --version'
}
 }
  stage('second stage starting'){
   steps{
    echo"package is deploying"
   }
  }
 stage('second stage starting'){
   steps{
    echo"docker is deployed...successfully"
   }
  }
 
}
}
