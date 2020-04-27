node('master')
{
   stage('ContinuousDownload-loans') 
   {
       git 'https://github.com/intelliqittrainings/maven.git'
   }
   stage('ContinuousBuild-loans') 
   {
       sh label: '', script: 'mvn package'
   }
  }
