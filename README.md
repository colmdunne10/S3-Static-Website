# S3-Static-Website
In this project, I hosted a static website in an S3 bucket using Terraform.

## Overview
The end goal of this project was to deploy AWS resources such as an S3 bucket and host a static website using Terraform. To begin, I installed Terraform and the AWS CLI. This allowed me to connect my AWS account with Terraform without hardcoding any credentials in my code. I then used the Terraform documentation to guide me through this process which involved creating the S3 bucket, making the bucket public, uploading the index/error.html files to the bucket and adding a website configuration to the bucket. In the end, I successfully deployed the bucket and hosted a static website all through Terraform.

## Architecture/What was created.
- S3 Bucket.
- S3 website configuration.
- Uploaded 2 objects to the bucket (index.html & error.html).
- Made the bucket public.
- Added ownership controls to the bucket.
- Created a public ACL.


## Technologies used
- Terraform
- AWS S3
- HTML/CSS
- Git/Github
- AWS CLI


## Prerequisites
- AWS Account.
- Install AWS CLI.
- Install Terraform.
- Create an IAM user and generate access credentials (access key & secret access key).

## How to deploy
Run the following Terraform commands:
```
terraform init
terraform plan
terraform apply
```
  
