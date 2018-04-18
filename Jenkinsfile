
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
	           'bundle install'
  		   'bundle exec rspec testPokemonAPI.rb'

		 }
	}
    }
    
}
