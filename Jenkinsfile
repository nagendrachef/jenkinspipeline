pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
		    uptime;date
		    ls -ltr
		    echo "test well & got success"
		    echo "installed new git bash"
                '''
            }
        }
    }
}
