node{
   stage('SCM Checkout'){
     git 'https://github.com/javahometech/my-app'
   }
   stage('docker build')
   {
      app = docker.build("siva564/login :${env.BUILD_NUMBER}")
   }
}
