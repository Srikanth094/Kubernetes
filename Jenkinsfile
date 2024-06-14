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
                    sh '/c/Program Files/Docker/Docker/resources/bin/kubectl create deployment busybox --image=busybox'
            }
        }

    }
}