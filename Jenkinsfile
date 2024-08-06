pipeline{
    agent any
    stages{
        stage("Build"){
            steps{
                sh '-DskipTests clean package'
            }
        }
        stage("Test"){
            steps{
                sh 'mvn test'
            }
        }
    }
}
