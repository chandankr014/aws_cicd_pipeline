## End to End MAchine Learning Project

1. Docker Build checked
2. Github Workflow
3. Iam User In AWS

## Docker Setup In EC2 commands to be Executed

#optinal

sudo apt-get update -y

sudo apt-get upgrade

#required

curl -fsSL https://get.docker.com -o get-docker.sh

sudo sh get-docker.sh

sudo usermod -aG docker ubuntu

newgrp docker

## Configure EC2 as self-hosted runner:

## Setup github secrets:

AWS_ACCESS_KEY_ID=AKIAW3IFYIRJ3VBFJ7OH

AWS_SECRET_ACCESS_KEY=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

AWS_REGION = ap-south-1

AWS_ECR_LOGIN_URI = demo>>  470847865939.dkr.ecr.ap-south-1.amazonaws.com/spi-cicd-pipeline

ECR_REPOSITORY_NAME = spi-cicd-pipeline
