pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Test') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Hello World'
            }
        }
    }
  
post 
  {
    always 
    {
      emailext body: 'summary', replyTo: 'swapnil05sahu@gmail.com', subject: 'pipeline - notify', to: 'swapnil05sahu@gmail.com'
    }
  }
}
