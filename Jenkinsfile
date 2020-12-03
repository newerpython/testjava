pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh '/root/apache-maven-3.1.1/bin/mvn -B -DskipTests clean package'
            }
        }


    }
}
