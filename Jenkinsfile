pipeline {
    agent any 
    
    stages {
        stage('Deploy to Minikube') {
            environment {
                // Set kubeconfig file path
                KUBECONFIG = 'C:\\Users\\Admin\\.kube'
            }
            steps {
                    // Run kubectl command
                    sh 'C:\\Program Files\\Docker\\Docker\\resources\\bin\\kubectl.exe create deployment busybox --image=busybox'
            }
        }

    }
}