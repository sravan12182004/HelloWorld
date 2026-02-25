pipeline {
    agent any

    stages {
        stage('build html site') {
            steps {
               publishHTML([allowMissing: false, alwaysLinkToLastBuild: false, icon: '', keepAll: false, reportDir: '', reportFiles: 'HelloWorld.html', reportName: 'HTML Report', reportTitles: '', useWrapperFileDirectly: true])
            }
        }
    }
}
