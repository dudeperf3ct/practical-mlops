# Practical MLOps

Book: [Practical MLOps By Noah Gift, Alfredo Deza](https://learning.oreilly.com/library/view/practical-mlops/9781098103002/)

## Notes

`notes` folder contains notes corresponding to each chapter from the book.

## Exercies

`exercies` folder implements exercies from different chapters.

1. [Makefile](exercises/1-makefile) : In this exercise, we will automate the task of installing packages, linting, formatting and testing using Makefile.

   **Technologies : Pytest, Make**

2. [Github Actions Makefile](https://github.com/dudeperf3ct/2-github-actions-makefile): In this exercise, we will automate the task of installing packages, linting, formatting and testing using github actions.

   **Technologies: Pytest, Make, Github Actions**

3. [Github Actions Docker](https://github.com/dudeperf3ct/3-github-actions-docker):  In the exercise, we will implement the following:

   - Containerize a GitHub project by integrating a Dockerfile and automatically registering new containers to a Container Registry.
   - Create a simple load test for your application using a load test framework such as locust or loader io and automatically run this test when you push changes to a staging branch

   **Technologies: Docker, Github Actions, Locust**

4. [FastAPI Azure](https://github.com/dudeperf3ct/4-ml-fastapi-azure-serverless): In this exercise, we will build a fastapi ML application and deploy it with continuous delivery on Azure using Azure App Services and Azure DevOps Pipelines.

   **Technologies: Docker, FastAPI, Continuous Delivery using Azure App Services, Azure DevOps Pipelines**

5. [FastAPI GCP](https://github.com/dudeperf3ct/5-ml-fastapi-gcp-serverless): In this exercise, we will build a fastapi ML application and deploy it with continuous delivery on GCP using Cloud Run and Cloud Build.

   **Technologies: Docker, FastAPI, Continuous Delivery using GCP Cloud Run and Cloud Build**

6. [FastAPI AWS](https://github.com/dudeperf3ct/6-ml-fastapi-aws-serverless): In this exercise, we will build a fastapi ML application and deploy it with continuous delivery on AWS using AWS using Elastic Beanstalk and Code Pipeline.

   **Technologies: Docker, FastAPI, Continuous Delivery using Elastic Beanstalk and Code Pipeline**

7. AWS Terraform Deploy: To be implemented

8. [FastAPI GKE](https://github.com/dudeperf3ct/8-fastapi-tests-gcp-gke): In this project, we will deploy a sentiment analyser model using fastapi on GCP using GKE.

   - Containerizing different components of projects
   - Writing tests and testing individual modules using `pytest`
   - Using [trunk](https://docs.trunk.io/) for automatic code checking, formatting and liniting
   - Deploying application on GKE

   **Technologies: Docker, FastAPI, Pytest, Trunk, GKE**

9. [FastAPI Kubernetes Monitoring](https://github.com/dudeperf3ct/9-fastapi-kubernetes-monitoring): In this exercise, we will introduce Kubernetes. Using Kubernetes deploy fastapi application and monitor this application using `Prometheus` and `Grafana`, following best practices of writing tests and trigger a CI workflow using github actions.

   **Technologies: Docker, Docker-compose, Pytest, FastAPI, Continuous Integration using Github Actions, Kubernetes, Prometheus, Grafana**

10. [BentoML Deploy](https://github.com/dudeperf3ct/10-bentoml-deploy): In this exercise, we will use BentoML library to deploy the sentiment classification model from Hugging Face :hugs: on following services.

   - [AWS Lambda Deployment](https://github.com/dudeperf3ct/10-bentoml-deploy/blob/main/aws%20lambda/Readme.md)
   - [Azure Functions Deployment](https://github.com/dudeperf3ct/10-bentoml-deploy/blob/main/azure%20functions/Readme.md)
   - [Kubernetes Cluster Deployment](https://github.com/dudeperf3ct/10-bentoml-deploy/blob/main/kubernetes/Readme.md)

   **Technologies: Docker, Pytest, FastAPI, AWS Lambda, Azure Functions, Kubernetes**

11. [Cortex Deploy](https://github.com/dudeperf3ct/11-cortex-deploy): In this exercise, transformers sentiment classifier fastapi application is deployed using Cortex two different APIs.

    - [Realtime API](https://github.com/dudeperf3ct/11-cortex-deploy/blob/main/realtime/Readme.md)
    - [Async API](https://github.com/dudeperf3ct/11-cortex-deploy/blob/main/async/Readme.md)

   **Technologies: Docker, Cortex, FastAPI, Continuous Integration using Github Actions, Trunk.io linter**

12. [Serverless Deploy](https://github.com/dudeperf3ct/12-serverless-deploy): In this exercise, transformers sentiment classifier fastapi application is deployed using two ways i.e., Serverless Framework and Serverless Cloud.

    - [Serverless Framework]()
    - [Serverless Cloud]()
