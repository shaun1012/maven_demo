pipeline
{
agent any
	
	stages
	{
		stage ('SCM Checkout') 
		{
			git 'https://github.com/shaun1012/maven_project.git'
		}
	}
	{
	
stage ('code test')
	{
	steps
		{
		withMaven(maven: 'LocalMaven')
	{
	sh 'mvn test'
	}
}

}
}
