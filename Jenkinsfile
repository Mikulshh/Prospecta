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
               var = 123456
               echo $var
               ''')
            }
        }
    }
}
