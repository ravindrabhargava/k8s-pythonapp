# hello-python
Very simple hello world python Flask application.

Here we will deploy a simple python app into kubernetes system 

Here are some requirement from the app 

migrate application from OnPrem Data Centre to GCP
Application on GCP should be Highly Available
Application on GCP should be Scalable
Application on GCP should be Highly Fault Tolerant
Application logs and stastics must be visible in ELK/EFK stack
Write scripts and yaml files, in order to run this application on a Kubernetes cluster, i.e. Helm charts or Kubernetes manifests.
Add security as a pipeline in your deployment pipeline. i.e. SAST, DAST.
You can use any public code to develop application and deploy it on Kubernetes cluster. Need to make sure about using ENV variables in 12Factor style, create Dockerfile.
You have to write documentation and/or instructions about what you have done. This documents must detail steps for other DevOps to understand how to deploy this application and maintain it.
Do not make your code public.
Architect and Design new application diagram for Cloud Native Implementation
Present Diagram in Draw.io
Present few options on architecture and design
From multiple options use one in terraform code
Describe migration plan for huge database which maybe on diffrent engine i.e. MSSQL required to migrate to Cloud SQL
Describe how can you make whole project secure. Including Infra, System and Application.
Write Infrastructure as Code in terraform 0.12
use remote state
terraform code should be promotable Dev > Staging > Production
terraform code should be managed in source control system
