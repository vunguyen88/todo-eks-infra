# todo-eks-infra (Terraform AWS EKS Deployment)

This repository contains Terraform configurations for deploying an Amazon EKS (Elastic Kubernetes Service) cluster on AWS.
The repository has 2 pipelines for manually deploy on selected branch and automatically deploy on pull request for main branch.
The deployment utilizes github actions with github secrets in appox 20-25 minutes with minimun of 3 nodes for 3 available zones on selected region.

## Prerequisites

Before you begin, ensure you have the following installed:

- [Terraform](https://www.terraform.io/downloads.html) v1.0.0 or later
- [AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html) configured with appropriate access
- [kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/) for managing Kubernetes clusters
- [aws-iam-authenticator] using access key and secret key
