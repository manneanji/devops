pipeline{
  agent any

tools {
java 'java'
Maven 'mvn-mine'
}

stages {
stage('git clone'){
   steps{
   git "https://github.com/manneanji/devops.git"
}
}
stage('maven package'){
steps{
sh "mvn package"
}
}
}



}



