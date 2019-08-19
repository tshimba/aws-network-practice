# aws-network-practice

```
tshimba:~/environment $ aws configure
AWS Access Key ID [****************RYVL]: 
AWS Secret Access Key [****************N9mx]: 
Default region name [ap-southeast-1]: 
Default output format [None]: 
```

```
aws cloudformation create-stack --stack-name openshift-vpc --template-body file://01_create_vpc.yaml
aws cloudformation delete-stack --stack-name openshift-vpc
aws cloudformation describe-stacks --stack-name openshift-vpc
```
