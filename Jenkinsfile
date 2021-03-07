node{
  stage('SCM Checkout') {
    git branch: 'main', url: 'https://github.com/msriram226/myapp'
  }
  stage('Compile-Package') {
    sh 'mvn package'
  }
}
