node{
  stage('SCM Checkout'){
     git 'https://github.com/vishnu2198/python-jenkins-helloworld.git'
     }
   stage('Installing Dependencies'){
    sh  "ssh  ec2-user@54.167.84.225 ' python autoimport.py' "
    }
    stage('Deploying python file in other instance'){
     sh  "ssh  ec2-user@54.167.84.225 'python app.py' "
     }
     }
