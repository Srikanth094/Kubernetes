pipeline {
    agent any 
    
    stages {
        stage('Deploy to Minikube') {
            environment {
                // Set kubeconfig file path
                KUBECONFIG = '/c/Users/Admin/.kube'
            }
            steps {
                    // Run kubectl command
                    sh 'kubectl create deployment busybox --image=busybox'
            }
        }

    }
}