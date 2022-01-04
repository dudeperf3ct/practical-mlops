# Practical MLOps

Book: [Practical MLOps By Noah Gift, Alfredo Deza](https://learning.oreilly.com/library/view/practical-mlops/9781098103002/)

## Notes

`notes` folder contains notes corresponding to each chapter from the book.

## Exercies

`exercies` folder implements exercies from different chapters.

1. [Makefile](exercises/1-makefile) : In this exercise, we will automate the task of installing packages, linting, formatting and testing using Makefile.

   **Technologies : Pytest, Make**

2. [Github Actions Makefile](exercises/2-github-actions-makefile): In this exercise, we will automate the task of installing packages, linting, formatting and testing using github actions.

   **Technologies: Pytest, Make, Github Actions**

3. [Github Actions Docker](exercises/3-github-actions-docker):  In the exercise, we will implement the following : 

   - Containerize a GitHub project by integrating a Dockerfile and automatically registering new containers to a Container Registry. 
   - Create a simple load test for your application using a load test framework such as locust or loader io and automatically run this test when you push changes to a staging branch

   **Technologies: Docker, Github Actions, Locust**

4. [FastAPI Azure](exercises/4-ml-fastapi-azure-serverless): In this exercise, we will build a fastapi ML application and deploy it with continuous delivery on Azure using Azure App Services and Azure DevOps Pipelines.

   **Technologies: Docker, FastAPI, Continuous Delivery using Azure App Services, Azure DevOps Pipelines**

5. [FastAPI GCP](exercises/5-ml-fastapi-gcp-serverless): In this exercise, we will build a fastapi ML application and deploy it with continuous delivery on GCP using Cloud Run and Cloud Build.

   **Technologies: Docker, FastAPI, Continuous Delivery using GCP Cloud Run and Cloud Build**

6. [FastAPI AWS](exercises/6-ml-fastapi-aws-serverless): In this exercise, we will build a fastapi ML application and deploy it with continuous delivery on AWS using AWS using Elastic Beanstalk and Code Pipeline.

   **Technologies: Docker, FastAPI, Continuous Delivery using Elastic Beanstalk and Code Pipeline**

7. [FastAPI GKE](exercises/8-fastapi-tests-gcp-gke): In this project, we will deploy a sentiment analyser model using fastapi on GCP using GKE.

   - Containerizing different components of projects
   - Writing tests and testing individual modules using `pytest`
   - Using [trunk](https://docs.trunk.io/) for automatic code checking, formatting and liniting
   - Deploying application on GKE

   **Technologies: Docker, FastAPI, Pytest, Trunk, GKE**

8. [FastAPI Kubernetes Monitoring](exercises/9-fastapi-kubernetes-monitoring): In this exercise, we will introduce Kubernetes. Using Kubernetes deploy fastapi application and monitor this application using `Prometheus` and `Grafana`, following best practices of writing tests and trigger a CI workflow using github actions.

   **Technologies: Docker, Pytest, Continuous Integration using Github Actions, Kubernetes, Prometheus, Grafana**

9. [BentoML Deploy](exercises/10-bentoml-deploy.git): In this exercise, we will use BentoML library to deploy the sentiment classification model from Hugging Face :hugs: on following services. 

   - [AWS Lambda Deployment](exercises/10-bentoml-deploy.git/aws%20lambda/Readme.md)
   - [Azure Functions Deployment](exercises/10-bentoml-deploy.git/azure%20functions/Readme.md)
   - [Kubernetes Cluster Deployment](exercises/10-bentoml-deploy.git/kubernetes/Readme.md)

   **Technologies: Docker, Pytest, AWS Lambda, Azure Functions, Kubernetes** 



