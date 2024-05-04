# terraform-eks
A sample repository to create 'EKS on AWS using Terraform'.

### Install AWS CLI 

Begin by installing the AWS CLI to seamlessly connect Terraform with AWS. Follow the simple steps outlined in the AWS CLI Installation Guide.

Follow the below link to Install AWS CLI.
```
https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html
```

### Install Terraform

Next, Install Terraform using the provided 'link' in the Terraform Installation Guide.
```
https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli
```

### Connect Terraform with AWS

Easily link Terraform with AWS by executing the aws configure command and inputting your AWS Security credentials. 

### Initialize Terraform

Clone the repository and initialize Terraform by running terraform init. This step sets up the Terraform environment, downloading necessary modules, providers, and configurations.

### Optionally review the terraform configuration
```
terraform plan
```
For clarity, you can run 'terraform plan' to preview the configuration before execution.

### Finally, Apply terraform configuation to create EKS cluster with VPC 
```
terraform apply
```
Finally, apply the Terraform configuration to create the EKS cluster within the VPC by executing 'terraform apply'. This straightforward process simplifies the creation of your EKS infrastructure on AWS.

### Cleanup
```
terraform destroy
```
command is a convenient way to destroy all remote objects managed by a particular Terraform configuration.
