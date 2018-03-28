pipeline {
  agent any
  stages {
    stage('Stage One') {
      steps {
        echo 'Hello world! Testing Jenkins Pipeline Test 19'
	sh"""#!/bin/bash -l
           nvm use
        """
        echo 'Sleeping...'
        sleep 30 
      }
    }
  }
}
