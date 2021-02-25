
pipeline {
  agent any 
   
   stages {
   
     stage('checkout'){
        steps{
          checkout changelog: false, poll: false, scm: [$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/HenokKeraga/jenkinespipeline.git']]]
        }
     
     }
   
   
   }

}
