[![CircleCI](https://dl.circleci.com/status-badge/img/gh/jainsmailbox/Proj5/tree/main.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/jainsmailbox/Proj5/tree/main)

# Anurag's Udacity Project 5 (Capstone)
*******************************************************************************************
Project Name: Anurag's Udacity Project 5 (Capstone)

Programe: Udacity Cloud DevOps Nano-Degree 

Developed By: Anurag Jain
*******************************************************************************************
This project has used below listed tools:

AWS
GitHUB: version control tool
CircleCI to Implement Continuous Integration and Continuous Deployment
Building Docker containers in pipelines
Building Kubernetes clusters
Python (Flask) 

************************ Steps to Deply my Application ************************************

1) Lint Python and docker files using pylint and hadolint respectively 

2) Build a Docker image for python flask app and upload it to docker Hub repository 

3) Use cloudformation to create Kubernetes cluster in AWS (EKS) 

4) Create Service as loadbalancer for high availability

5) Deploy a docker container create in step 2 from the docker HUB

5) Application is deployed and running on EKS cluster

6) Use rolling update strategy to re-deploy updates to the application. This will allow me to minimsse the downtime for the users. This strategy allows to update Kubernetes system with no downtime. 
In this strategy, the Deployment selects a Pod with the old programming, deactivates it, and creates an updated Pod to replace it.

7) Use the version tagging approach to TAG the docker image as V1,V2,V3 etc. This will help to revert back to previous version if needed. 

8) v1 & v2 progression is demonstraed in the screenshots



Anurag Jain 
