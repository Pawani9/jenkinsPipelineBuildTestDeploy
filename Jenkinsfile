node('master') {
  
   stage 'Git Checkout'
     git 'https://github.com/Pavani/spring-petclinic.git'
         echo 'checkout done'

   stage('Maven Build'){
      echo 'Maven Project Compile'
      maven 'clean install' 
      junit 'target/surefire-reports/**/*.xml' 
   }


   stage 'Deploy'
        echo 'Deploying Docker Image'

   stage 'Testing'
        echo 'Testing Getting Creating'

   stage 'Job Status Status'
        echo 'Notification Sending'
}
