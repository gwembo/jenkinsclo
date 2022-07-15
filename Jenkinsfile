node('master') 
{
    stage('Continuous Download_loans') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_ loans') 
	{
    sh label: '', script: 'mvn package'
	}
    
}
