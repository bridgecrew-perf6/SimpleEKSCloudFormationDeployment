# Deploying to AWS

## Requirements

- Have aws cli and sam cli installed.
- AWS Account configured on machine, credentials and config files

Step 1: Open the
'SimpleEKSCloudFormationDeployment' directory in the terminal

Step 2: run the following command:
```cmd
sam deploy --capabilities CAPABILITY_NAMED_IAM --guided
```