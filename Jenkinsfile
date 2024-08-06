pipeline{
    agent any
    stages{
        stage("Build"){
            steps{
                cmd_exec('bat "mvn -DskipTests clean package"')
            }
        }
        stage("Test"){
            steps{
                cmd_exec('bat "mvn test"')
            }
        }
    }
}
