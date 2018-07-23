pipeline {
    agent any
    triggers { 
        upstream(upstreamProjects: 'Questionnaire', threshold: hudson.model.Result.SUCCESS) 
    }
    stages {
        stage('Running integration tests') {
            steps {
                echo 'Hello World'
            }
        }
    }
}