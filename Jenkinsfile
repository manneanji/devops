pipeline{
  agent any

tools {
java "java-mine"
maven "mvn-mine"
}

stages {
stage{
   steps{
   git "https://github.com/manneanji/devops.git"
}
}
stage{
steps{
sh "mvn package"
}
}
}



}
