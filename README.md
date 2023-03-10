# mireilledib-devops2-project

Project for DevOps 2. Includes a trigger to a Jenkins CI/CD pipeline for every push on this repo (webhooks don't work so it will be a manual build for my machine) instructing the jenkinsfile to build the project and create a Dockerfile, build the docker image and pushe the Dockerfile image to Docker hub.

Project components:

- github project

- python file

- CI/CD Pipeline

  - web hook

- Jenkinsfile

- Dockerfile
