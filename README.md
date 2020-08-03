# CloudDevOpsUdacityProject02
This project contains CloudFormation scripts that will orchestrate the whole Infrastructure for a highly available WebApp.


# Steps to Run the below code Using AWS CLI

1. Create an AWS account and configure the same in you CLI.Use the below link for help.
https://docs.aws.amazon.com/cli/latest/userguide/cli-configure-quickstart.html

2. Run the below commands for windows to run the script.
> create.bat Project2Stack Project02_CF_Script.yml Project02_Parameters.json

3. Creation will take several minutes once done your webApp will be up and running.

# Changes to be made before running the code 

1. Create an S3 bucket with the public access. 
2. Now make changes in yml script with correct path and name for your created s3 bucket and the source code.

