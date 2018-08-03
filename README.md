# Create AWS IoT Thing using python and boto3

This project will create a thing on AWS IoT platform using boto3 and python and download the certificates.

## Requirements

* AWS Credentials, if you have installed AWS CLI, then you can use it to configure your credentials file:

      aws configure

  if don't you can create a credentials by creating credentials file under `~/.aws/` (`~/.aws/credentials`) and put:
  
      aws_access_key_id = YOUR_ACCESS_KEY
      aws_secret_access_key = YOUR_SECRET_KEY
      
* Python
* Boto3, you can find more information about it [here](https://boto3.readthedocs.io/en/latest/guide/quickstart.html#installation)
* Create a policy named `GGTest_Group_Core-policy` or change `defaultPolicyName` value in source code to your appropriate policy.

## Getting Started

* Clone the repository

      git clone https://github.com/keivanK1/aws-create-thing-boto3.git
* Run it

      python createThing-Cert.py

Enjoy:-)
