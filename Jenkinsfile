node
{
   stage('SCM Checkout')
   {
     git 'https://github.com/javahometech/my-app'
   }
   stage('dokcer login')
   {
      sh 'docker login -u sivareddy564 -p sivareddy@564'
   }
   stage('docker build')
   {
     sh  'docker build -t sivareddy564/siva .'
   }
}
