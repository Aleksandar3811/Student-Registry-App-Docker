pipeline {
 agent any
 stages {
 stage('NPM Install') {
 steps {
 bat 'npm install'
 }
 }
 stage('Run test') {
 steps {
 bat 'npm test'
 }
 }
}
}
