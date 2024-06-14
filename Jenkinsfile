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
                    sh ' "D:\\kubectl\\kubectl" create deployment busybox --image=busybox'
            }
        }

    }
}