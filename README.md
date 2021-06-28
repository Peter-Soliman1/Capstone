# Capstone

Project Description

Implemengin HTML using the below:

    AWS
    Circle CI to implement CICD
    Building pipelines
    Working CloudFormation to deploy clusters
    Building Kubernetes clusters
    Building Docker containers in pipelines

Tasks and Procedures

    Lint html  and Dockerfile

    Push the built Docker container to the Docker repository 

    Deploy these Docker container to a small Kubernetes cluster. 

    Create EKS Cluster on AWS by

    ./createEKS.sh

    Setup Project with Circleci

Linting

    lint index.html
    hadolint Dockerfile
    Build Docker image
    Push docker image to DockerHub

Apply on Kubernetes

    Apply Blue server
    Apply Green Server when user approve
    Get app url from cluster

    kubectl get services --all-namespaces -o wide
