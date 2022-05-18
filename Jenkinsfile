properties([pipelineTriggers([pollSCM('*/15 * * * *')])])
pipeline {
    agent any

    stages {
        stage('Stage1') {
            steps {
                bat "dir"
                bat "python mySoftware.py"
            }
        }
    }
}
