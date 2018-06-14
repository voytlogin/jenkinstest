node
{
	checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/voytlogin/jenkinstest.git']]])
	
	stage('stage 1') 
	{
		bat 'mkdir www'
		echo 'Hello World %WORKSPACE%'
	}

	stage('stage 2') 
	{
		echo 'stage 2'
	}
}