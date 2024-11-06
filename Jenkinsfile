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
                 script {
                    powershell '''
                        Write-Output "Hello World!"
                        $date = Get-Date
                        Write-Output "Current Date add time :$date"
                    '''
                }
            }
        }

    }
}