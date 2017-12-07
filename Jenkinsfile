
	#!/usr/bin/env groovy

    [$class: 'GithubProjectProperty',
    displayName: 'naveen_task',
    projectUrlStr: 'https://github.com/Demo-project4/task7.git']
    pipelineTriggers([githubPush()])])

pipeline {
    agent any 

    stages {
        stage('Build') { 
            steps { 
                sh 'pwd' 
            }
        }
        stage('Test'){
            steps {
                sh 'java -version'
                
            }
        }
        stage('Deploy') {
            steps {
                sh 'ls'
                sh 'pwd'
            }
        }
    }
}
