# BoschAssessmentDevOps

* assesment folder contains all the required files to deploy the application:

- Dockerfile = used to create the docker image for the todo application

- ansible.cfg = used locally to edit ansible configuration

- inventory = is the inventory file used for ansible, it indicates the server ip and the login method

- run_app.yaml = used to run the docker images for the application and the database using docker-compose

- assessment.yaml = contains all the instructions given to ansible to deploy the application
