# BFF AWS Infrastructure

This is an example deployment for a custom Backend for Frontend module (URL available soon).

## Infrastructure details
0. Security group
1. Logging: CloudWatch alerts + S3 bucket
2. Application
    a) ECR - Repository
    b) ELB - Load Balancer
    c) ECS - Cluster

## Working steps
1. Edit `vars.yml` according to your AWS account
2. Edit `image_creation.sh` according to your AWS account
3. Run `ansible-playbook deploy.yml`