pipeline{
    agent any

    stages{

        stage("cloning github repo to Jenkins"){
            steps{
                script{
                    echo "cloning github repo to Jenkins.........."
                    checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: 'github-token', url: 'https://github.com/Ruan-vd-Merwe/mlops-project1']])
                
                }
            }
        }

    }
}