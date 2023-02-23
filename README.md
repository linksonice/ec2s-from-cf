# ec2s-from-cf

EC2s made to various specifications, with Cloudformation. Don't bother wasting valuable time creating these at work - just copy these instead, and make any adaptations as required.

Here's how to order:

aws cloudformation deploy --template-file ./ec2.3.yaml --stack-name ec2v3

Here's how to destroy:

aws cloudformation delete-stack --stack-name ec2v3

Here's how to list all you got:

aws cloudformation list-stacks --stack-status-filter CREATE_COMPLETE
