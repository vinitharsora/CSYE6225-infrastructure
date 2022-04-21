# infrastructure/aws

#This assignment will focus on setting up our networking resources such as Virtual Private Cloud (VPC), Internet Gateway, Route Tables, Routes, application security group an EC2 instance, creating S3 bucket, RDS instance, IAM policies, Load Balancing, Auto Scaling, JMeter and CI/CD, CodeDeploy, Logging and Metrics, Lambda function and SSL to build our infrastructure. We will use AWS CloudFormation for infrastructure setup and tear down.

# Tasks Accomplished:

1. Created a Stack using Amazon CloudFormation

2. Deleted a Stack using Amazon CloudFormation

# What you need:

1. Install AWS CLI on your System.

2. IDE

# Useful Commands:

* aws cloudformation deploy --profile demo --template-file csye6225-infra.yml --capabilities CAPABILITY_NAMED_IAM --parameter-overrides KeyName=testkey AmiID=ami-01300e13abca0950e --stack-name assignment7

* pm2 restart all --update-env

* $ aws acm import-certificate --certificate fileb://Certificate.pem \
      --certificate-chain fileb://CertificateChain.pem \
      --private-key fileb://PrivateKey.pem 	
