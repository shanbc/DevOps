pipeline{
    agent any
    stages{
        stage("Build"){
            steps{
                echo '-DskipTests clean package'
            }
        }
        stage("Test"){
            steps{
                echo 'mvn test'
            }
        }
    }
}
