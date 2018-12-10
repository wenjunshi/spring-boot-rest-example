pipeline {
  agent any
  stages {
    stage('sprtest') {
      steps {
        sh '''echo \'Start build\'
/data/maven3/apache-maven-3.1.1/bin/mvn clean install

echo \'OKOK!\''''
      }
    }
  }
}