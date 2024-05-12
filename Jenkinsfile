pipeline{
agent any
stages{
 stage('Printing a message '){
steps{
    echo"Job is building"
    sh 'mvn --version'
}
  step{
   echo"package is deploying"
}
}
}
