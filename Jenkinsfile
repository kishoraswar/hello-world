node{
     stage('code-checkout')
     {
         
          checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '0758c869-6710-4f7f-98a2-1dd43570d58d', url: 'https://github.com/kishoraswar/hello-world.git']]])         
          def workspace    
     }
     stage('Build')
     {
         echo "build succesfull"
     }
     stage('test')
     {
         echo "test succesfully"
     }
     stage('deploy')
     {
         echo "deploy succesfully"
     }
    
}
