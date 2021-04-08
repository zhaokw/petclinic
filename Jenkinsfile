node {
  stage('checkout') {
    git 'https://github.com/zhaokw/petclinic'
  }
  stage('compile') {
    def mvnHome = tool name: 'maven-3', type: 'maven'
    sh "${mvnHome}/bib/mvn package"
  }
}
