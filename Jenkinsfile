pipeline {
	  agent {
	    node {
	      label 'master'
	    }
	  }
	  stages {
	    stage('DEV') {
	      steps {
	        echo 'Build Docker'
	        echo 'Deploy Image'
		echo 'Test Application' 
	      }
	    }
	    stage('TEST') {
	      steps {
	        echo 'Create TEST env in AWS'
	        echo 'Deploy Image'
                echo 'Test Application'
	      }
	    }
	}
      }
