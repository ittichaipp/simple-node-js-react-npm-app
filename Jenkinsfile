pipeline{
    agent any
    stages {
        stage('build'){
            steps{
                bat 'npm install'
                echo 'Start Executing'
				script {
                    powershell '''C:\\Tutorial\\testscript\\myscript.ps1'''
                } 
            }
        }

    }
}