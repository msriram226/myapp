node{
  stage('SCM Checkout') {
    git 'https://github.com/msriram226/myapp'
  }
  stage('Compile-Package') {
    sh 'mvn package'
  }
}
