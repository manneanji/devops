pipeline{
  agent any

tools {
JDK 'java'
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



