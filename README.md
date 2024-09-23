# Project Title
12 Microservices Application Deployment on Docker Desktop Kubernetes with CI/CD using GitHub, Jenkins, DockerHub, and Helm
## Description:

This project showcases the deployment of a 12-microservice application on a local Kubernetes cluster using Docker Desktop. Each microservice is containerized using Docker and orchestrated by Kubernetes. The development and deployment process is managed using GitHub for source control and Jenkins for CI/CD automation. DockerHub serves as the registry for container images, while Helm is used to deploy and manage the Kubernetes resources. The application is accessible locally on localhost for testing and development purposes.

## Tools and Technologies Used
- GitHub
- Jenkins
- Docker
- DockerHub
- Docker Desktop Kubernetes
- Helm


## Pipeline Flow Diagram
![P05](https://github.com/user-attachments/assets/e5eed3b2-c221-4fba-8462-2c282922a15b)






# Components and Tools Used

## 12 Microservices Architecture:
The application consists of 12 independent microservices, each responsible for a specific functionality.

Each microservice is containerized using Docker, allowing for modular and isolated deployments.

Microservices communicate with each other using internal networking provided by Kubernetes, ensuring seamless service-to-service communication.

## Local Kubernetes Cluster on Docker Desktop:

The microservices are deployed on a Kubernetes cluster running locally via Docker Desktop.

Docker Desktop provides a lightweight Kubernetes environment suitable for local development and testing, enabling developers to mimic cloud-based deployments on their local machines.



## CI/CD Pipeline with GitHub and Jenkins:

GitHub is used for source code management, allowing developers to collaborate, manage version control, and track code changes.

Jenkins automates the CI/CD process, including:

- **Building Docker images** for each microservice.
- **Running tests** to ensure application functionality and quality.
- **Pushing Docker images** to DockerHub.
- **Deploying the updated microservices** to the local Kubernetes cluster.
Jenkins ensures continuous integration and continuous deployment, making the development process efficient and streamlined.

## Containerization with Docker:
Each microservice is packaged in a Docker container, ensuring that all dependencies and environment configurations are consistent across environments.

Docker containers allow for modular, scalable, and isolated deployment of microservices.

## DockerHub for Container Registry:
DockerHub serves as the container registry, where Docker images for each microservice are stored.

Jenkins pushes new Docker images to DockerHub whenever changes are made in GitHub, ensuring that the latest versions of the microservices are always available for deployment.

## Kubernetes Deployment:
The microservices are deployed as Kubernetes pods on the local cluster.

Kubernetes manages the orchestration of these pods, ensuring that they are running, scaling them when needed, and providing networking between them.

Kubernetes services are used to expose the microservices internally and externally.

## Kubernetes Resource Management with Helm:
Helm is used to manage the Kubernetes resources needed for deploying the microservices.

Helm charts define the configurations for the deployments, services, and other Kubernetes objects, simplifying the deployment process.

This allows the application to be easily deployed and managed in Kubernetes.

## Accessing the Application via localhost:
The entire application is accessible on localhost, allowing developers to interact with the microservices as they would in a production environment.

Port forwarding is used to expose the Kubernetes services on localhost, enabling direct access to the application via a web browser or API client.

# Project Workflow
## Development and Local Testing:
Developers write and test code for individual microservices locally.

Each microservice is containerized using Docker to ensure consistent runtime environments.

## Source Control with GitHub:
The code for each microservice is stored in GitHub, with branches used to manage feature development and updates.

Developers push changes to GitHub, which triggers the CI pipeline.

## CI/CD Pipeline with Jenkins:
Jenkins is used to automate the build and deployment process:

The pipeline builds Docker images for each microservice.

It runs tests to validate functionality.

The images are pushed to DockerHub, ensuring they are ready for deployment.

Jenkins then deploys the microservices to the local Kubernetes cluster on Docker Desktop.

## Kubernetes Deployment and Orchestration:
Each microservice is deployed as a Kubernetes pod on the local cluster.

Kubernetes manages the deployment, scaling, and networking of these pods, ensuring they communicate efficiently.

The services are exposed through localhost using Kubernetes port forwarding, allowing the developer to test the application locally.

## Accessing the Application on localhost:
The user accesses the microservices-based application through localhost in a web browser or API client.

Each service is available via a specific port on localhost, simulating a production-like environment for testing.

# OUTPUT
## jenkins pipeline 
![Screenshot (305)](https://github.com/user-attachments/assets/426c4eb5-17e4-4bd3-ac2a-f39413a42866)
![Screenshot (303)](https://github.com/user-attachments/assets/46cd8dbe-f0b2-408a-bd28-f6e0c11add48)
![Screenshot (304)](https://github.com/user-attachments/assets/9ce4f03d-b805-422d-a211-30b6c3537f01)

## docker hub
![Screenshot (306)](https://github.com/user-attachments/assets/71e7cde2-f9b4-48bd-a7bd-92268875f213)

## Docker Desktop Kubernetes OUTPUT
![Screenshot (2)](https://github.com/user-attachments/assets/d6d3cdfa-7e70-4b71-b884-aa7da9e5e437)
![Screenshot (3)](https://github.com/user-attachments/assets/c837d8d1-b427-468c-b5b1-119b2eaf69c3)
![Screenshot (4)](https://github.com/user-attachments/assets/8dae8c16-ec1b-44f4-be11-31465d9df121)
## Vulnerability Testing
![Screenshot (6)](https://github.com/user-attachments/assets/38fbe672-c79b-40cb-a185-e0e76ee46b7b)

## Application OUTPUT
![Screenshot (7)](https://github.com/user-attachments/assets/de727cd4-4dda-4097-9322-8e9801e4adfb)
![Screenshot (8)](https://github.com/user-attachments/assets/c8038743-3823-4331-9c55-16791cacf952)
![Screenshot (9)](https://github.com/user-attachments/assets/d9c57b23-c3d4-41bc-b571-1f1d8bb33729)
![Screenshot (10)](https://github.com/user-attachments/assets/64ca843a-16ce-4608-9185-ac7737819e8e)
![Screenshot (11)](https://github.com/user-attachments/assets/20c961e7-437e-4848-b650-59f9410066ca)
![Screenshot (12)](https://github.com/user-attachments/assets/ad8a34c9-959b-4e95-861a-1e64a60dac59)
![Screenshot (13)](https://github.com/user-attachments/assets/1aef3a2b-7419-425e-bf6c-106bd10892ee)
![Screenshot (14)](https://github.com/user-attachments/assets/96dd5826-78d8-4a43-8b47-033c54b72ff0)
![Screenshot (17)](https://github.com/user-attachments/assets/45d3b827-bb87-44f9-8213-95f5d3dfa558)
![Screenshot (18)](https://github.com/user-attachments/assets/fd849275-efd4-4803-8a35-e6f613e57c34)

**This project demonstrates the deployment of a 12-microservice application on a local Kubernetes cluster using Docker Desktop. By leveraging GitHub for source control, Jenkins for CI/CD automation, DockerHub for container storage, and Helm for Kubernetes resource management, the project ensures a smooth and efficient development-to-deployment workflow. The application is fully accessible via localhost, providing a seamless testing environment.**


# **Thank you.......**
