# Setup
This repository houses resources required for setting up Otterize in your infrastructure, such as CloudFormation templates.

Currently includes:
1. The CloudFormation template for setting up AWS IAM support for Otterize. This CloudFormation template creates AWS IAM roles and policies to allow AWS IRSA to function for a specific cluster.
  - Also publicly available here - [https://otterize-cloudformation-template.s3.amazonaws.com/aws-iam-operator-setup-template.yaml](https://otterize-cloudformation-template.s3.amazonaws.com/aws-iam-operator-setup-template.yaml)
3. The CloudFormation template for setting up Otterize's AWS Visibility integration. This CloudFormation template creates an AWS IAM role with limited read-only permissions to be used by Otterize to collect resource metadata.
  - Also publicly available here - [https://otterize-cloudformation-template.s3.amazonaws.com/aws-visibility-integration-setup-template.yaml](https://otterize-cloudformation-template.s3.amazonaws.com/aws-visibility-integration-setup-template.yaml)
