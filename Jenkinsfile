pipeline{
    agent any
    stages{
        stage("Build"){
            steps{
                mvn '-DskipTests clean package'
            }
        }
        stage("Test"){
            steps{
                echo 'mvn test'
            }
        }
    }
}
