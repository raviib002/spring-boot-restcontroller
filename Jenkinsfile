pipeline {
    agent { any { image 'maven:3.3.3' } }
    stages {
        stage('build') {
            steps {
               sh 'mvn clean install'
            }
        }
        
        stage('predeployment-test')
        {
            steps { 
              
               sh  'ls -ltr'
               sh 'sudo ./testjar.sh'
                
            }
        
        }
           
    }
}
