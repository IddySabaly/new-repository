pipeline {
  agent any
  stages {
    stage('\'copy file to aws ec2 ') {
      steps {
        sh ''' // copy files from local_machine 


                sh \'scp -r iddy@172.30.1.95:/home/iddy/Downloads/files/  ec2-3-238-39-33.compute-1.amazonaws.com\' 
'''
      }
    }

  }
}