node {
   stage('SCM Checkout') {
   git 'https://github.com/maheshwagh1402/maven-hello-world.git'
}
   stage('Build') {
     def mvnHome = tool name: 'maven', type: 'maven'
      echo 'Hello World'
       sh 'date'
       sh 'pwd'
       sh 'java -version'
      sh 'mvn --version'
       sh "${mvnHome}/bin/mvn package"
      

    }


}
