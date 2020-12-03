pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh '/srv/maven/bin/mvn -B -DskipTests clean package'
            }
        }


    }
}
