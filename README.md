# kubernetes

# Commands
    - Create:
        kubectl create deploy [NAME] --image=[image-name] --replicas=[number-images] --dry-run=client -o yaml > [filename].yaml
        kubectl create namespace [name] --image=[image-name] --dry-run=client > [file-name].yaml
        kubectl create deployment [name] --image=[image-name] --dry-run=client > [file-name].yaml
    - Apply:
        kubectl apply -f [file-name].yaml
    -Describe:
        kubectl describe deployments [file-name].yaml
    - Get
        kubectl get deployments
        kubectl get pods
        kubectl get namespaces
    - Delete
        kubectl delete deployment [Deployment-name]
        kubectl delete pod [pod-name]
