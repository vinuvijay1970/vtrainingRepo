pipeline {
    agent any
    triggers {
        GenericTrigger(
            genericVariables: [
                [key: 'ref', value: '$.ref']
            ],
            token: 'TestGitHub',
            printContributedVariables: true,
            printPostContent: true
        )
    }
    stages {
        stage('Build') {
            steps {
                echo 'Hello World from jenkins to git hub'
            }
        }
    }
}
