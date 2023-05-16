# Deploying a Linux EC2 Instance and Connecting via SSH
This GitHub repository is dedicated to providing various methods for connecting to Amazon Web Services Elastic Compute Cloud (AWS EC2) instances. EC2 is a scalable computing platform that allows users to rent virtual servers in the cloud to run their applications.

Step 1: Sign in to the AWS Management Console and navigate to the EC2 service

step 2: From the EC2 Dashboard go and select Launch instance.

Step 3: Choose an Amazon Machine Image (AMI) for the Linux server. You can choose from various Linux distributions available.

Step 4: Select the instance type that suits your requirements. Consider the CPU, memory, storage, and network capacity you need.

Step 5: In Key pair select Create new key pair. This key pair will be used to securely connect to the instance via SSH.(make sure to download and securely store the private key file (.pem) in a safe location.)

Step 6: Configure Network setting including subnet, security group, etc. If you're not sure, you can use the default settings.(Allow SSH (port 22) access. By default, incoming SSH traffic is blocked for security reasons.)

Step 7: Configure the storage options for your instance. You can specify the size of the root volume and add any additional volumes if needed.

Step 8: Review all the configuration details you've set for the instance.
If everything looks good, click on "Launch" to start the instance. 

Step 9: Once the instance is running, you can connect to it using the CLI. Open your terminal or command prompt and navigate to the directory where your key pair file is stored.

Step 10: Set the appropriate permissions for the key pair file using the command 

Step 11: Go to the Ec2 instance. At the bottom of the screen, you will see a section called "Connect". Click on the "Connect" button. In the connection dialog, you will see different options for connecting to your instance, such as EC2 Instance Connect, Session Manager, and SSH. Select the "SSH client" tab. Here, you will find the SSH command that you can copy and paste into your CLI. and then press Enter to connect to your EC2 instance.
