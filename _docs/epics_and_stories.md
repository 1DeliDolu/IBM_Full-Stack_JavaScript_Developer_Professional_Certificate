# Epics and Stories

## Epic
- Title: Modernise Tax Calculator
- Description: The Tax Calculator currently runs as a manually deployed static application and lacks a robust pipeline in place. This epic focuses on modernizing the application to deploy it on IBM Cloud. But the web application will not just be simply lifted and shifted to cloud. The application will be containerized using Docker container. The deployment will be managed through a pipeline, which will also ensure that all unit tests pass before deployment.

## User Stories
1) Title: Containerizing the application  
   Description: To ensure that each unit of code performs as expected, run unit tests. And if the unit tests pass, deploy the application to a docker container.

2) Title: Deploying on IBM Cloud  
   Description: Instead of hosting on self-managed or in-house virtual machines, deploy the application on IBM Cloud, using IBM Cloud Code Engine.

3) Title: Creating a pipeline for packaging and deploying the application  
   Description: The current process of packaging and deploying involves too many manual steps. Use a Tekton pipeline to automate the build, test, and packaging stages of the application.
