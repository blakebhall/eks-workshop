---
title: "Pre-Conditions"
date: 2022-03-10T00:00:00-00:00
weight: 9
draft: false
---

### General Preconditions for Running this Lab

Before we get started there are a few accounts that are required to make this work.

1. Account with AWS
2. Account with [Spot.io](https://console.spotinst.com/spt/auth/signUp?utm_campaign=eskworkshop&utm_source=eksworkshop)

### Setting up Sample EKS Cluster

#### eksctl
Information taken from [EKS Done Right – From Control Plane To Worker Nodes](https://spot.io/blog/eks-done-right-from-control-plane-to-worker-nodes/)

1. Ensure you have eksctl installed
```bash
eksctl version
```

2. Ensure you have your AWS Credentials configured
```bash
echo $AWS_ACCESS_KEY_ID
echo $AWS_SECRET_ACCESS_KEY
```
Keep in mind that these credentials are for your account, if they are not set you can run this command to set them:

For your Access Key:
```bash
export AWS_ACCESS_KEY_ID=<aws_access_key>
```
For your Secret:
```bash
export AWS_SECRET_ACCESS_KEY=<aws_secret_access_key>
```

 

#### Terraform
terraform test

#### Cloudformation
cloudformation
