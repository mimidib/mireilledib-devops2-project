# mireilledib-devops2-project
Project for DevOps 2. Includes a Jenkins CI/CD pipeline that triggers a build for every push on this repo (webhooks don't work so it will be a manual build for my machine) then it executes the jenkinsfile which instructs the creation of a Dockerfile, and pushes the Dockerfile to Docker hub. 
