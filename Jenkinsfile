pipeline {
    agent any
    stages {
	stage('myStage'){
      	    steps {
        	sh 'ls -la' 
            }
        }
        stage('build') {
            steps {
                sh 'mvn --version'
		sh 'ls'
            }
        }
    }
}
