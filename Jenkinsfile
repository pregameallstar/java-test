pipeline{
    agent{
        docker{
            image 'maven:3-alpine'
            args '-v C:\Users\taddenbrooke\Documents\Github\java-test\plugins:/root/.m2'
        }
    }
    stages{
        stage('Build'){
            steps{
                sh 'mvn -B -DskipTests clean package'
            }
        }
    }
}
