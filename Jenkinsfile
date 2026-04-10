pipeline {
    agent any
    stages {
        stage('Concat files') {
            steps {
                sh '''
                    echo "Concatenating files..."
                    cat 1 2 3 4 > merged.txt
                    echo "Files merged into merged.txt"
                '''
            }
        }
    }
}
