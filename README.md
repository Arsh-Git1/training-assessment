# training-assessment.

## Project Overview
You are tasked with setting up a CI/CD pipeline for a microservices-based application. The 
application will be containerized using Docker and orchestrated using Kubernetes. Ansible 
will be used for configuration management and deployment. The entire setup should be 
managed using Git for version control, and Jenkins will be used to automate the CI/CD 
process.

## Assessment Criteria

### 1. Git:

○ Repository setup
○ Branching strategies
○ Commit and merge practices


### 2. Jenkins:

○ Pipeline creation using Jenkinsfile
○ Integration with Git
○ Automated build, test, and deployment stages


### 3. Docker:

○ Dockerfile creation
○ Image building and management
○ Containerization of microservices


### 4. Kubernetes:
○ Pod and service creation
○ Deployments and replica sets
○ ConfigMaps and Secrets


### 5. Ansible:
○ Playbook creation
○ Use of variables and templates
○ Inventory management

## Use Case Scenario
Your company is developing a new e-commerce application consisting of several 
microservices: a front-end service, a product catalog service, and an order processing 
service. The goal is to automate the deployment and configuration of these services across 
development, testing, and production environments using Ansible, Docker, Kubernetes, and 
Jenkins.


## Tasks and Deliverables

### Task 1: Git Repository Setup
1. Create a Git repository to store all project files, including Ansible playbooks, 
Dockerfiles, and Kubernetes manifests.

2. Branching Strategy:
○ Create branches for development, testing, and production.
○ Implement a strategy for merging changes from development to testing and 
production.


![alt text](<Screenshot from 2024-08-02 15-26-14.png>)

![alt text](<Screenshot from 2024-08-02 15-26-29.png>)

Task 2: Dockerize Microservices

1. Create Dockerfiles for each microservice (front-end, product catalog, order 
processing).
2. Build Docker images for each microservice and push them to a container registry 
(e.g., Docker Hub).
3. Deliverables:
○ Dockerfiles for each microservice
○ Built Docker images in a container registry

![alt text](<Screenshot from 2024-08-02 17-27-28.png>)

![alt text](<Screenshot from 2024-08-02 17-28-07.png>)

![alt text](<Screenshot from 2024-08-02 17-28-32.png>)

![alt text](<Screenshot from 2024-08-02 17-34-23.png>)


Task 3: Kubernetes Deployment

1. Create Kubernetes manifests for deploying each microservice.
○ Define Pods, Services, Deployments, and ReplicaSets.
○ Use ConfigMaps and Secrets for configuration management.
2. Deploy the microservices to a Kubernetes cluster.
3. Deliverables:
○ Kubernetes manifests (YAML files)
○ Successful deployment of microservices in the Kubernetes cluster

![alt text](<Screenshot from 2024-08-02 17-25-34.png>)

![alt text](<Screenshot from 2024-08-02 17-31-10.png>)

![alt text](<Screenshot from 2024-08-02 17-32-02.png>)






