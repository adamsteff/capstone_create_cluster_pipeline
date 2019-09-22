
# Create cluster pipeline
This GitHub repository was created as part of my Udacity Capstone - Cloud DevOps project. This repository was used to create a Jenkins Pipeline.

## Jenkins Pipeline Step 1
The first in the pipeline was used to spin up an AWS EKS Cluster using `eksctl create cluster` command. AWS Cloudformation then created the cluster and nodes.

## Jenkins Pipeline Step 2
The second step of this pipeline created a kubectl configuration file using the command `aws eks --region ap-southeast-2 update-kubeconfig --name capstonecluster` so I could interact with the cluster later.

## Blue Green Pipeline Repository
You can find my Blue Green Pipeline Repository which was used to create my Jenkins Blue Green Pipeline [Here](https://github.com/adamsteff/capstone_create_blue_green_pipeline)
- (https://github.com/adamsteff/capstone_create_blue_green_pipeline) 








