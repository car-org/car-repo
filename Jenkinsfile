pipeline {
    agent any

    stages {
        stage('Build.') {
            steps {
                echo 'Building.'
            }
        }
        stage('Test..') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy.') {
            steps {
                echo 'Deploying.....'
                lastChanges format: 'LINE', matchWordsThreshold: '0.25', matching: 'NONE', matchingMaxComparisons: '1000', showFiles: true, since: 'PREVIOUS_REVISION', specificBuild: '', specificRevision: '', synchronisedScroll: true, vcsDir: ''
            }
        }
    }
}
