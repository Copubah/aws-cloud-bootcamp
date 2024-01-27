## Generate Credentials,AWS CLI,Budget and Billing alarm via CLI
## AWS CLI INSTALLATION
- In this documentation i shall be using the documentation for Linux OS
## Steps
1. curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"(to download)
2. unzip awscliv2.zip(to unzip the installer)
3. sudo ./aws/install

## Steps to configure your AWS account
- sudo apt update
- sudo apt install python3
- sudo apt inststall python3-pip
- sudo pip3 install awscli
- After installation run; aws--version
- Run;aws configure
- Enter the access Key ID and Secret access key and enter your preferred region(to be generated in the web management console)
- Type ;aws sts get-caller-identity(to confirm)