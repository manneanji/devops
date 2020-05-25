pipeline{
  agent any

tools {
jdk 'java'
maven 'mvn'
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



