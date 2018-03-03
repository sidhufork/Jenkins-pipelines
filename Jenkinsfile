pipeline{
    agent any
    stages{
        stage('build'){
            steps{
                sh "env"
                echo "compilation"
            }
        }
        stage('test'){
            steps{
                echo "testing step"
                echo "step-2"
            }
        }
        stage('deploy'){
            steps{
                echo "deploy the artifacts"
            }
        }
    }
}
