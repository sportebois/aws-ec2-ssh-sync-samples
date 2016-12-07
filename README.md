
These small sets of recipes are lightweight provisioning companions for SSH key sync with IAM users, as illustrated in the demo [aws-ec2-ssh-sync](https://github.com/sportebois/aws-ec2-ssh-sync) repo which shows various technics for synchronizinf IAM users ssh keys with local users on EC2 instances.

From these Terraform recipes (for the no key) options, you could then setup your host from these recipes to separate your Terraform provisionning sources (which will contains details about your infra)  from the ec2 instances scripts dealing with the sync which can be open sources easily.
