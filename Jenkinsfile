pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
                sh 'echo "here is another command"'
                sh 'echo "Howdy here is more information"'
                sh 'echo "Can we get another ping to Jenkins firing"'
                sh 'echo "and here is one more"'
            }
        }
    }
}
