# terraform-aws
```
terraform init
terraform plan
terraform apply -auto-approve
```
After 5 mins run "terraform refresh" to make sure the FQDN of the EC2 instance hasn't changed.
ssh into the EC2 instance:
```
ssh -i ~/.ssh/my-key-pair.pem ec2-user@ec2-44-218-157-174.compute-1.amazonaws.com
```
When you are done, destroy the env:
```
terraform destroy -auto-approve
```
