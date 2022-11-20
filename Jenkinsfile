pipeline {
      agent { label 'built-in' }
      environment {
      Name=Sandeep
      }
         stages { options {
         stage ('build') {
            steps {
               sh ''' free -h
                     echo "$Name" ''' }
               }
              }
             }
            } 
               
