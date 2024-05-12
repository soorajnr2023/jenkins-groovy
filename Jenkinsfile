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
   echo"package is deploying"
  }
}
}
