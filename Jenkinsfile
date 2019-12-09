 node ('MAVEN')
     {
         stage ('SCM') {
             git 'https://github.com/ramesh44557/spring-petclinic.git'
         }

         stage ('build the code ') {
             sh 'mvn package'
         }
     }