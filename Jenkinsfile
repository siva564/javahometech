node
{
   stage('SCM Checkout')
   {
     git 'https://github.com/javahometech/my-app'
   }
   stage('docker build')
   {
     sh  'docker build -t sivareddy564/siva .'
   }
}
