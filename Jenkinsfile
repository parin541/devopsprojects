pipeline{
  
  agent any
  
  stages{
   stage {"Build it"}{
    steps{
      echo "Building the Projefct"
    }
}
  post{
    success{
      emailext body: '''Hello, This is test mail from pipeline ,Thank you''', subject: 'Test Email from Jenkins Pipeline', to: 'pmistry9296@gmail.com'
      }
    }
 }  
}
