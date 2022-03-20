# Create ECS cluster based on EC2

Command to apply the CloudFormation template

Launchtype _EC2_:  

```bash
aws cloudformation create-stack --stack-name ecs-ec2 --capabilities CAPABILITY_IAM --template-body file://./ecs-cluster-ec2.yml
```

Launchtype _Fargate_:  

```bash
aws cloudformation create-stack --stack-name ecs-fargate --capabilities CAPABILITY_IAM --template-body file://./ecs-cluster-fargate.yml
```
