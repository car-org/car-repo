pipeline {
    agent any
    stages {
        stage('1') {
            steps {
                lastChanges format: 'LINE', matchWordsThreshold: '0.25', matching: 'NONE', matchingMaxComparisons: '1000', showFiles: true, since: 'PREVIOUS_REVISION', specificBuild: '', specificRevision: '', synchronisedScroll: true, vcsDir: ''
            }
        }
    }
}
