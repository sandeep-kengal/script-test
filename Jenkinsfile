pipeline {
    parameters {
  string defaultValue: 'built-in', description: 'to select node to run', name: 'label', trim: true
}
    agent { label $'{params.label}' }

     environment {
       Name="Sandeep"
       Tool="Jenkins"
    }
stages {
    stage ('deploy'){
     parallel {
        stage ('SERVER1'){
            steps {
                sh ''' echo "$Name" '''

            }
        }
         stage ('SERVER2') {

          
          steps {
            sh ''' echo "$Tool" '''
          }
     }
     }
}

}
}
