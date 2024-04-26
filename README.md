# AWS-EC2

 ## Steps To Lunch An AWS EC2 Instance

Log in to AWS Management Console:
Access the console at https://aws.amazon.com/ and log in with your credentials. Select a region close to you.

Navigate to the EC2 Dashboard:
Once logged in, locate the "Services" menu at the top of the console and select "EC2" to open the EC2 Dashboard.

Launch Instance:
Click the "Launch Instance" button to start the instance setup process.

Choose an Amazon Machine Image (AMI):
Select an AMI that serves as the template for your instance. AWS provides a variety of AMIs pre-configured with different operating systems and software setups.

Choose an Instance Type:
Select the appropriate instance type based on your computing, memory, and storage needs. You can choose from general purpose, compute-optimized, or memory-optimized options, among others.

Configure Instance:
Set up the network and subnet, and configure other settings like IAM roles, monitoring (enable CloudWatch), and shutdown behavior.

Add Storage:
Configure the storage for your instance. You can add additional Elastic Block Store (EBS) volumes or adjust the size of the default volume.

Configure Security Group:
Set up firewall rules to control network traffic to and from your instance. You can select an existing security group or create a new one, specifying the type of traffic and protocol allowed.

Review and Launch:
Review your configuration settings. Make any necessary changes, and then click "Launch".

Key Pair for Access:
Upon launching, you’ll be prompted to select a key pair for SSH access to the instance. You can use an existing key pair or create a new one. If you create a new key pair, download and save it securely; you’ll need it to access the instance.

Launch and Connect:

Finish the launch process. Once the instance is running, you can connect to it using its public DNS or IP address, typically through SSH (for Linux) or Remote Desktop (for Windows).


See below for screenshort of Instance running and stop state. 

<img width="1427" alt="Screenshot 2024-04-26 at 13 21 21" src="https://github.com/Ebube-E/AWS-EC2/assets/98676503/8b484453-a9d4-4f4a-844b-681735f9f3c8">
<img width="1412" alt="Screenshot 2024-04-26 at 13 23 15" src="https://github.com/Ebube-E/AWS-EC2/assets/98676503/7b44b87f-d626-4ec5-a4de-0bd6e291485a">
