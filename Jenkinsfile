node('built-in') 
{
    stage('Continuous Download_card') 
	{
    git 'https://github.com/tsri010203/mycode.git'
	}
    stage('Continuous Build_card') 
	{
    sh label: '', script: 'mvn package'
	}
}
