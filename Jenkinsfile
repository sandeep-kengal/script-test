pipeline {
    agent any

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
