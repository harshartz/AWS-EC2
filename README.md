# Deploying a Linux EC2 Instance and Connecting via SSH
This GitHub repository is dedicated to providing various methods for connecting to Amazon Web Services Elastic Compute Cloud (AWS EC2) instances. EC2 is a scalable computing platform that allows users to rent virtual servers in the cloud to run their applications.

Step 1: Sign in to the AWS Management Console and navigate to the EC2 service
![1ss](https://github.com/harshartz/AWS-EC2/assets/130890384/fc60c0ef-6898-4974-aabc-cba05b71e4a6)
step 2: From the EC2 Dashboard go and select Launch instance.
![2ss](https://github.com/harshartz/AWS-EC2/assets/130890384/903dabb1-ba8e-4f54-b602-20b1fe739a35)
Step 3: Choose an Amazon Machine Image (AMI) for the Linux server. You can choose from various Linux distributions available.
![3ss](https://github.com/harshartz/AWS-EC2/assets/130890384/c8676b90-5b95-44b0-ba8f-2190f1572b50)
Step 4: Select the instance type that suits your requirements. Consider the CPU, memory, storage, and network capacity you need.
![4ss](https://github.com/harshartz/AWS-EC2/assets/130890384/7359d520-e78f-4c65-afc6-e129b900cc2c)
Step 5: In Key pair select Create new key pair. This key pair will be used to securely connect to the instance via SSH.(make sure to download and securely store the private key file (.pem) in a safe location.)
![5ss](https://github.com/harshartz/AWS-EC2/assets/130890384/01dc1a51-1e21-497c-b9b7-c4610eceffa5)
![8ss](https://github.com/harshartz/AWS-EC2/assets/130890384/ec393e0b-5404-4ca3-8988-f72132cb05ac)
Step 6: Configure Network setting including subnet, security group, etc. If you're not sure, you can use the default settings.(Allow SSH (port 22) access. By default, incoming SSH traffic is blocked for security reasons.)
![6ss](https://github.com/harshartz/AWS-EC2/assets/130890384/d3d4d2e3-6695-4789-a1d9-551642f62080)
Step 7: Configure the storage options for your instance. You can specify the size of the root volume and add any additional volumes if needed. Review all the configuration details you've set for the instance. If everything looks good, click on "Launch" to start the instance. 
![7ss](https://github.com/harshartz/AWS-EC2/assets/130890384/92bf940e-9c12-42f3-9a05-ed3f681f698d)
Step 8: Once the instance is running, you can connect to it using the CLI. Open your terminal or command prompt and navigate to the directory where your key pair file is stored.
![10sss](https://github.com/harshartz/AWS-EC2/assets/130890384/0f6d4cab-9493-4e99-983e-d93694a22111)
Step 9: Go to the Ec2 instance. At the bottom of the screen, you will see a section called "Connect". Click on the "Connect" button. In the connection dialog, you will see different options for connecting to your instance, such as EC2 Instance Connect, Session Manager, and SSH. Select the "SSH client" tab. Here, you will find the SSH command that you can copy and paste into your CLI. and then press Enter to connect to your EC2 instance.
![9ss](https://github.com/harshartz/AWS-EC2/assets/130890384/f7fdc728-8877-4e85-ba11-aa410352f6a7)
![10ss](https://github.com/harshartz/AWS-EC2/assets/130890384/df834266-d133-41c8-ad7e-cb2f3ec638aa)
![11ss](https://github.com/harshartz/AWS-EC2/assets/130890384/7dadbfaa-07cb-45de-8080-d479226181ec)
