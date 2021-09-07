pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World from tarendra'
            }
        }
        stage('bash script'){
            steps {
                sh(script:
               '''#!/bin/bash
               echo "hi again"
               ''')
            }
        }
    }
}
