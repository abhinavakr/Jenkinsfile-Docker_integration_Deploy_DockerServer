#Project: Jenkins Integration with Docker Server and Application Deployment
Project Title: Jenkins Integration with Docker Server and Application Deployment

Project Description:
Successfully implemented a full-stack DevOps project involving the integration of Jenkins with Docker to automate the deployment of a Java-based application. The project showcases proficiency in continuous integration and continuous deployment (CI/CD) practices by using Jenkins to build, containerize, and deploy the application on an AWS EC2 Ubuntu server.

Key Steps and Responsibilities:
1. Integrating Jenkins with Git:

Setup Git Repository:

Created a Git repository to host the application’s source code.
Configured access for Jenkins to clone the repository.
Checkout Code in Jenkins Pipeline:

Used the git plugin in Jenkins to checkout the latest code from the repository.
Ensured that Jenkins can pull the code updates automatically or through webhooks.
2. Building the Application with Maven:

Configure Maven in Jenkins:

Installed and configured the Maven plugin in Jenkins.
Specified the Maven goals to clean, compile, and package the application.
Build the Package:

Defined stages in the Jenkins pipeline to execute Maven commands.
Managed dependencies and ensured the application is built successfully.
3. Containerizing the Application with Docker:

Create Dockerfile:

Authored a Dockerfile to containerize the application, defining the base image and necessary steps to run the application in a container.
Build Docker Image:

Integrated Docker commands in the Jenkins pipeline to build the Docker image using the Dockerfile.
Tagged the Docker image appropriately for version control.
4. Pushing the Docker Image to DockerHub:

DockerHub Configuration:

Set up DockerHub repository to store the Docker images.
Configured Jenkins with DockerHub credentials to enable pushing images.
Push Image:

Added pipeline steps to push the Docker image to DockerHub.
Verified the successful upload of the image to the DockerHub repository.
5. Deploying to Docker Server on AWS EC2:

AWS EC2 Setup:

Launched an EC2 instance running Ubuntu on AWS to host the Docker server.
Installed Docker on the EC2 instance and configured it to run Docker containers.
Pull and Run Docker Image:

SSH into the EC2 instance from Jenkins using the SSH plugin or command line.
Pulled the Docker image from DockerHub to the EC2 instance.
Deployed the Docker container on the EC2 instance using docker run commands.
