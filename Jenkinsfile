pipeline{
agent any
stages{
stage('one'){
steps{
echo "hi"
}
}
stage('four'){
steps{
echo "welcome"
}
}
}
pipeline {
    agent any
    stages {
        stage('display') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
