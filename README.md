## Getting Started

### Set Up

1.  Install AWS CLI

        curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o  "awscliv2.zip"
        unzip awscliv2.zip
        sudo ./aws/install
        aws --version

2.  Create a user for deploying functions in AWS Management Console
3.  Configure AWS CLI

        aws configure
        # set access and secret access keys to those attached to user in AWS Management Console

4.  Install serverless

        npm install -g serverless

5.  Deploy service

        sls deploy --account_id <your_account_id>
