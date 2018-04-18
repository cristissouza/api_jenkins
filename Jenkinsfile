
pipeline {
	agent any
    stages {
        stage('build') {
            steps {
                sh 'ruby --version'
            }
        }
	stage('Test') {
	   steps {
	          sh 'bundle install'
  		  sh 'bundle exec rspec testPokemonAPI.rb'

		 }
	}
    }
    
}
