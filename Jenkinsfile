node ('nginx-app-server1'){
   
   stage('Deploy App on nginx-app-server1') {
              
       dir('/var/lib/jenkins/app') {
        sh './deploy.sh'
           
       }
      
   }
   
}

node ('nginx-app-server-2'){
   
   stage('Deploy App on nginx-app-server-2') {
       
       dir('/var/lib/jenkins/app') {
        sh './deploy.sh'
           
       }

   }
   
}

