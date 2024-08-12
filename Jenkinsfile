if (env.BRANCH_NAME == 'master') {
    load 'Jenkinsfile.ci/Jenkinsfile.build'
} else if (env.BRANCH_NAME == 'dev') {
    load 'Jenkinsfile.cd/Jenkinsfile.deploy'
}
