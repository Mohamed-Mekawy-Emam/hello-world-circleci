# hello-world-circleci
Your First circleci Green Build 

# IaC Through AWS CF
Added Create IaC through AWS CF

Set up Environment variables
To use the AWS CLI in your jobs you'll need to the following environment variables to the in Circle CI > Project Settings > environment variables. The value of these variables can be fetched from the AWS IAM user.

If not already, create an AWS IAM user with programmatic access, and it will generate these credentials.

AWS_ACCESS_KEY_ID
AWS_DEFAULT_REGION
AWS_SECRET_ACCESS_KEY
Note - While saving the environment variables in the Circle CI project settings, use capital case

reference: Setting an environment variable in a project. Do read about the various types of environment variables and their relative priorities.

https://circleci.com/docs/2.0/env-vars/#setting-an-environment-variable-in-a-project


