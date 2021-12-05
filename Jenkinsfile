pipeline
{
	agent any
	stages
{
	stage('SCM checkout')
	{
	steps {sh 'echo code-is-downloading'}
	}

	stage('create deployable package')
	{
	steps {sh 'echo created-artifacts'}
	}
	
	stage('deploying to developer')
	{
	steps {sh 'echo deploying-artifacts-to-server'}
	}
	
	stage('deploying to QA')
	{
	steps {sh 'echo Quality-analysis-done'}
	}
	
}
}
