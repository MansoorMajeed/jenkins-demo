pipeline {
    agent any
    stages {
        stage('test') {
            when {
                branch 'master'
            }
            steps {
                    sh '''#!/usr/bin/env sh
                    whoami
                    ls
                    pwd
                    echo "Yass"
                    '''
            }
        }
    }
}

