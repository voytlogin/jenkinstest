node
{
	checkout([$class: 'GitSCM', branches: [[name: '*/mastero']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/voytlogin/jenkinstest.git']]])
	
	stage('stage 1') 
	{
		echo 'Hello World'
	}

	stage('stage 2') 
	{
		echo 'stage 2'
	}
}