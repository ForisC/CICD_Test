properties([pipelineTriggers([githubPush()])])
node {
    checkout scm
    // git url: 'https://github.com/foris323/CICD_Test.git',
    branch: 'master'
    stage('Collect data') {
        sh 'echo randread.json'

    }
}
