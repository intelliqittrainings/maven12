node('master') 
{
    stage('ContinuousDownload_LOANS') 
    {
         git 'https://github.com/intelliqittrainings/maven.git'
    }
     stage('ContinuousBuild_LOANS') 
    {

        sh label: '', script: 'mvn package'
    }
    
    
    
}
