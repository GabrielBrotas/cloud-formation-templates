## Basic CloudFormation Comands

Create Stack
```
aws cloudformation create-stack --capabilities CAPABILITY_IAM --stack-name <stack name> --template-body file://<template path>
```

Delete Stack
```
aws cloudformation delete-stack --stack-name <stack name>
```


Update Stack
```
aws cloudformation update-stack --stack-name <stack-name> --template-body file://<file path>
```
