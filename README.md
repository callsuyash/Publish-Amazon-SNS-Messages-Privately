# Publish-Amazon-SNS-Messages-Privately

The general steps are as follows:

Use an AWS CloudFormation template to automatically create a temporary private network in your AWS account.

Create a VPC endpoint that connects the VPC with Amazon SNS.

Log in to an Amazon EC2 instance and publish a message privately to an Amazon SNS topic.

Verify that the message was delivered successfully.

Delete the resources that you created during this process so that they don't remain in your AWS account.
