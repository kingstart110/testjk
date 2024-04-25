pipeline {
    agent any
    stages {
        stage('Example Stage') {
            steps {
                // 执行一些自动化步骤
                echo 'This will run automatically.'
            }
        }
     
        // 只有在人工审核通过后才会执行的步骤
        stage('Deployment') {
            steps {
                echo 'Deployment will run after approval.'
            }
        }
    }
}
