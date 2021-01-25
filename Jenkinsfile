pipeline {
    agent 
    { 
        dockerfile true
    }
    stages {
        stage('Get Report') {
            steps {
                checkout([$class: 'GitSCM', branches: [[name: '*/main']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/sachinrawat1111/Project']]])
            }
        }
    }
}
