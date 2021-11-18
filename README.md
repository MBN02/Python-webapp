# Build a Docker Jenkins Pipeline to Implement CI/CD Workflow

In this project I have used a simple python-based application to demonstrate the CI/CD pipeline using Jenkins. 
Jenkins will pull the source code from GitHub repository, build a docker image, push it to docker hub and create a container out of the newly build image. Jenkins will check for running container and stop it before creating a new container every time a build is triggered.  

![jenkins](https://user-images.githubusercontent.com/89718858/142464120-b63c4031-7f76-4df7-9918-8095bcdc8270.JPG)

# Tools Used: 

- Docker: To build the application from a Dockerfile and push it to Docker Hub
- Docker Hub: To store the Docker image
- GitHub: To store the application code and track its revisions
- Git: To connect and push files from the local system to GitHub
- Linux (Ubuntu): As a base operating system to start and execute the project
- Jenkins: To automate the deployment process during continuous integration

