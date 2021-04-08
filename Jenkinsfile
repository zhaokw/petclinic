node {
  stage('checkout') {
    git 'https://github.com/zhaokw/petclinic'
  }
  stage('compile') {
    sh 'mvn package'
  }
}
