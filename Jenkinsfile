pipeline {
    
    agent none
    
   stages {
        
        stage('Build'){
            
            agent {
                label "mymavenslave"
            }
          
          steps {
             
                echo "my master branch"
          }
        }
   }
}
