pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                dotnet restore
                dotnet build --no-restore
            }
        }
    }
}