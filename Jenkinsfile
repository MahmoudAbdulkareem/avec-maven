pipeline {
    agent any
    tools {
        maven 'M2_HOME'
    }
    stages {
        stage('GIT') {
            steps {
                    git branch: 'master',
                    url:'https://github.com/mhassini/avec-maven.git'
            }
        }
    }
}
