# terraform-aws
terraform init
terraform plan
terraform apply -auto-approve
terraform refresh

ssh into the EC2 instance:
ssh -i ~/.ssh/my-key-pair.pem ec2-user@ec2-44-218-157-174.compute-1.amazonaws.com

When you are done, destroy the env:
terraform destroy -auto-approve
