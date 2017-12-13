# project-template

The bash scripts in this directory can be used to build and launch a server in the Amazon AWS cloud.  Before running the scripts, you can set some default parameters:

* AWS_CLI_PROJECT_NAME - the name of your project
* AWS_CLI_WORK_DIR     - local work directory 

Example:
```
   export AWS_CLI_PROJRCT_NAME=myproject
   export AWS_CLI_WORK_DIR=/home/tom/aws-work      
```

## List of Scripts:

| Script Name                 | Function                                    | 
| --------------------------- | ------------------------------------------- | 
| check-aws-cli-connection    | Test connectivity to your AWS account.      | 
| create-keypair              | Create root key pair for an account.        |
| create-vpc                  | Create VPC for project.                     |
| create-security-group       | Create security group.                      |
| add-port-to-security-group  | Open incoming port in security group.       |
| get-elastic-ip              | Get public static IP.                       |
| assign-elastic-ip           | Tie elastic IP to an instance.              |
| launch-instance             | Create and start a virtual machine.         |
| connect-to-instance         | SSH to running instance.                    |


Note: All the scripts have a -h help option to get usage information.  
