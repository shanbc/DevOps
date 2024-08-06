pipeline{
    agent any
    stages{
        stage("Build"){
            steps{
                bat '-DskipTests clean package'
            }
        }
        stage("Test"){
            steps{
                bat 'mvn test'
            }
        }
    }
}
