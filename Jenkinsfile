pipeline { 
    agent {
        node {
            label 'agent-1'
        }
    }

    stages {
         stage('deploy') {
            steps {
               echo 'deploying'
               echo "${params.version}"
            }
        }
    }
}