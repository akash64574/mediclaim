
pipeline {
agent any

stages {
stage('SCM Checkout') {
steps {
git url:'https://github.com/akash64574/mediclaim.git'
}
}
stage('Build') {
steps {
         sh"/opt/apache-maven-3.6.3/bin/mvn clean package -Dmaven.test.skip=true "
}
}
}
}
