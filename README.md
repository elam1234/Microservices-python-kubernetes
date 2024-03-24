"  PYTHON MICROSERVICES APPLICATION   DEPLOYMENT INTO KUBERNETES "

"  Python video to audio converter microservice application "
INTRODUCTION :
Hello everyone, I Elamparithi M, am a DevOps engineer, I am very passionate about doing innovative projects in the cloud as well as DevOps, especially am a Kubernetes enthusiast, recently I have done end-to-end microservices application deployment into Kubernetes cluster using Helm for component deployment. This document outlines my project's details, including its objectives, components, and challenges I faced during deployment.

PROJECT OBJECTIVES:
Deploy a Python-based microservices application in an EKS cluster.
Utilize Helm for deploying components like MongoDB, RabbitMQ, and PostgreSQL.
Implement an API gateway with endpoints for user authentication, video upload, and audio download.
Utilize Kubernetes services for queueing video-to-audio conversion tasks.
Ensure secure authentication and storage of user credentials and media files.

PROJECT COMPONENTS:
Microservices:
Authentication Service
Converter Service
Gateway Service
Notification Service
       2 . Technologies Used:
Python for application development
Helm for Kubernetes deployment
MongoDB, RabbitMQ, and PostgreSQL for data storage
JWT for authentication
Kubernetes for container orchestration
DEPLOYMENT STEPS :
      1. Write Dockerfiles for Microservices:
Create a Dockerfile for each microservice (Authentication Service, Converter Service, Gateway Service, and Notification Service).
Use a base Python image and install the necessary dependencies for each microservice in their respective Dockerfiles.
Configure Dockerfiles to expose required ports, set environment variables, and define startup commands.
    2 . Kubernetes Cluster Setup:
Configured EKS cluster and worker nodes.
Installed Helm for managing Kubernetes applications.
    3 . Component Deployment:
Deployed MongoDB, RabbitMQ, and PostgreSQL using Helm charts.
Configured services and endpoints for microservices.
    4 . Authentication and Authorization:
Implemented JWT-based authentication for user access.
Stored user credentials securely in MongoDB.
     5 . Queueing and Conversion:
Utilized RabbitMQ as a queue service for video-to-audio conversion tasks.
Converter service converts uploaded videos to audio files and stores them in PostgreSQL.
CHALLENGES  I FACED:
Authentication Setup:
Ensuring secure authentication mechanisms with JWT and MongoDB.
Queue Service Configuration:
Setting up RabbitMQ for efficient task queuing and processing.
Storage Management:
Storing media files securely in PostgreSQL and managing file conversions.
LESSONS LEARNED:
Importance of secure authentication and authorization mechanisms.
Efficient use of queue services for background tasks.
Proper management of data storage and conversions in a microservices architecture.
GITHUB LINK : [ https://github.com/elam1234/microservices-python-Kubernetes.git ]

CONCLUSION:
In conclusion, the deployment of the Python microservices application into Kubernetes using Helm showcases expertise in DevOps and cloud technologies. Challenges I faced, such as authentication setup and queue service configuration, provided valuable learning experiences. For more details, please refer to the project's GitHub repository: https://github.com/elam1234/microservices-python-Kubernetes.git.











