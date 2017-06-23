# Description #
Ansible playbook to create and clean aws enviroment.
Playbook creates desired vpc, ec2 instance and s3 bucket.
Ec2 instance sends test file to s3 bucket every 5 minutes.

# Requirements #
 - ansible 2.4.0
 - python 2.7.10
 - boto3

# Set up #
In order to use this paybook you must set following enviroment variables:
AWS_ACCESS_KEY_ID
AWS_SECRET_ACCESS_KEY

# Architecture #
![Architecture](/images/architecture.png)

# Known Issues # 