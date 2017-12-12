# project-template

The bash scripts in this directory can be used to build and launch a server in the Amazon AWS cloud.  Before running them, set these environment vairables:

* AWS_CLI_PROJECT_NAME - the name of your project
* AWS_CLI_WORK_DIR     - work directory

Example:

   export AWS_CLI_PROJRCT_NAME=myproject
   export AWS_CLI_WORK_DIR=/home/tom/aws-work      

##List of Scripts:
| Script Name                 | Function                            |
| --------------------------- |---------------------------------------------|
| check-aws-cli-connection    | Test connectivity to your AWS account.      |
