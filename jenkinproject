pipeline{
    agent any
    stages{
        stage("checkout code"){
            steps{
                sh "git clone https://github.com/shreyakothawale/javaproject.git"
            }
    }
        stage(" check docker version"){
            steps{
                sh "sudo docker version"
            }
        }
    }
}
