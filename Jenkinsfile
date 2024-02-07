pipeline {
  agent any
  
  stages{
     
   
    stage('SSH into the server') {
        steps {
               script {
                            def remote = [:]
                            remote.name = 'K8S Node2'
                            remote.host = '172.20.5.68'
                            remote.user = 'patiwat'
                            remote.password = 'patiwat#123'
                            remote.allowAnyHosts = true
                 
                 
                 echo 'SSH Success...!!'
                 
                 stage('Using Command Docker Bulid && Tag') {

                        sh 'pwd'
                        echo ''

                 }
     
               }
              
            
            }
    }
  
    }//steps

}//pipeline
