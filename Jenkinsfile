pipeline {
    agent any 
    stages {
        stage('Clone the repo') {
            steps {
                echo 'clone the repo'
                sh 'git clone https://github.com/akashkumar0711/webapp1.git'
            }
        }
        stage('copy to html folder') {
            steps {
                echo 'copy to html folder'
                sh 'cp /var/lib/jenkins/workspace/webapp/webapp1/* /var/www/html/'
            }
        }
        
    }
}
