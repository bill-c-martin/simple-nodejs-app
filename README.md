# simple-nodejs-app

A simple Node.js app and `Dockerfile` for:

1. Pushing code to an AWS CodeCommit (or Github) repo 
2. Publishing the code and `Dockerfile` to an image on AWS Elastic Container Registry
3. Setting up a deployment pipeline through AWS CodePipeline
4. Deploying code to EC2 instances through AWS Elastic Container Service

by following [Ivan Polovyi](https://polovyiivan.medium.com/)'s guides:

- [AWS CodePipeline for Amazon ECS, Part 1: A Rolling Updates Deployment Type](https://aws.plainenglish.io/aws-codepipeline-for-ecs-with-rolling-updates-deployment-type-53aacd03b8e5)
- [How to Push a Docker Image to the AWS ECR](https://aws.plainenglish.io/how-to-push-an-image-to-aws-ecr-b2be848c2ef)

## Localhost

1. Clone this repo
2. Run `docker-compose up -d`
3. Go to http://localhost:8080
