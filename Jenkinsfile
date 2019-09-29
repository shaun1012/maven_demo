pipeline
{
agent any
	{
		stage "scm checkout" 
		{
			git 'https://github.com/shaun1012/maven_project.git'
		}
	}
stage "code test"

withMaven(maven: 'LocalMaven')
	{
	sh 'mvn test'
	}
}
