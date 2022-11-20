pipeline {
      agent { label 'built-in' }
      environment {
      Name="Sandeep"
      Tool="jenkins"      
      }
         stages { 
               parallel {
         stage ('build') {
            steps {
               sh ''' free -h
                     echo "$Name" ''' }
               }
              
               stage ('test') {
                     steps {
                          sh ''' echo "tool is $Tool" ''' 
                     }
               
             }
            } 
}  
