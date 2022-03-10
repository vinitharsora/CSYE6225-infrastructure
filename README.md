# infrastructure/aws

#This assignment will focus on setting up our networking resources such as Virtual Private Cloud (VPC), Internet Gateway, Route Tables, and Routes from previous assignment and add a application security group and an EC2 instance to deploy our Web Application. We will use AWS CloudFormation for infrastructure setup and tear down.

# Tasks Accomplished:

1. Created a Stack using Amazon CloudFormation

2. Deleted a Stack using Amazon CloudFormation

# What you need:

1. Install AWS CLI on your System.

2. IDE

3. 2 new profiles, not the default one.

# Useful Commands:

* aws cloudformation deploy --profile dev  --template-file csye6225-infra.yml --capabilities CAPABILITY_NAMED_IAM --parameter-overrides KeyName=testkey AMIImage =ami-09e0000a6d87cbfb1 --stack-name demo1

* pm2 restart all --update-env





