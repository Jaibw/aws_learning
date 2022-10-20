# AWS CLI - CloudShell 
## type q to exit when you see scrolling 
aws --version
aws ec2 describe-instances
aws ec2 run-instances --image-id ami-078296f82eb463377 --instance-type t2.micro --key-name YOURNAME 
aws ec2 describe-instances --output text
aws ec2 describe-instances --output table
aws ec2 describe-instances --output json

aws ec2 describe-instances --output text  ## copy instanceid 
aws ec2 terminate-instances --instance-ids i-################
aws ec2 run-instances help
