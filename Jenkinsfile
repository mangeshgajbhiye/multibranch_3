node('built-in') 
{
    stage('Continuous Download') 
	{
    git 'https://github.com/mangeshgajbhiye/Classmate.git'
	}
    stage('Continuous Build') 
	{
    sh label: '', script: 'mvn package'

     }
}
