node{
   stage('SCM Checkout'){
     git 'https://github.com/suresh47686/my-app'
   }
   stage('Compile-Package'){
      // Get maven home path
     // def mvnHome =  tool name: 'maven-3', type: 'maven'   
      sh "mvn package"
   }
 /*  stage('Email Notification'){
      mail bcc: '', body: '''Hi Welcome to jenkins email alerts
      Thanks
      Hari''', cc: '', from: '', replyTo: '', subject: 'Jenkins Job', to: 'hari.kammana@gmail.com'
   }
   stage('Slack Notification'){
       slackSend baseUrl: 'https://hooks.slack.com/services/',
       channel: '#jenkins-pipeline-demo',
       color: 'good', 
       message: 'Welcome to Jenkins, Slack!', 
       teamDomain: 'javahomecloud',
       tokenCredentialId: 'slack-demo'
   }*/
}
