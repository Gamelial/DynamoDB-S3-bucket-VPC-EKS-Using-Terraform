# DynamoDB-S3-bucket-VPC-EKS-Using-Terraform

To create DynamoDB and S3 Bucket Using Terraform Backend Code

Git clone https://github.com/iam-veeramalla/ultimate-devops-project-aws.git

Log in to AWS

CREATE ACCESS KEY & SECRET ACCESS KEY
Access key: YOUR_ACCESS_KEY_ID
Secret acess key: YOUR_SECRET_ACCESS_KEY

On terminal
Run
Aws configure

Enter your keys and region:
AWS Access Key ID [None]: YOUR_ACCESS_KEY_ID
AWS Secret Access Key [None]: YOUR_SECRET_ACCESS_KEY
Default region name [None]: us-east-1         ← or your region
Default output format [None]: json

cd ultimate-devops-project-aws
Ls
cd eks-install/

ls
Cd backend
ls main.tf

Change the resource AWS S3 bucket variable to your own unique one

To Initialise terraform
Run
terraform init

To see the configuration
Run
Terraform plan

Run
Terraform apply

Option
Choose yes

AWS DynamoDB and S3 bucket will be created.

TO CREATE VPS & EKS

cd..
ls 
nano main.tf
Change the S3 bucket variables to newly created one
Change the DynamoDB table variables to newly created one
Change the provider AWS region variables to the current region in the console 

Run

Terraform init
Terraform plan
Terraform apply

Cluster endpoint, cluster name, and vpc_id will be created.
