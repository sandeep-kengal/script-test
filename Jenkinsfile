pipeline {
      agent { label 'built-in' }
      environment {
      Name="Sandeep"
      Tool="jenkins"      
      }
         stages { 
               
         stage ('build') {
                 parallel {
            steps {
               sh ''' free -h
                     echo "$Name" ''' 
               }
         }
         }
               stage ('test') {
                     parallel {
                     steps {
                          sh ''' echo "tool is $Tool" ''' 
                     }
               } 
               }
        }
   } 
}  
