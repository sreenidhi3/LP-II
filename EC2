**Amazon EC2 (Elastic Cloud Compute)**

Amazon EC2 provides scalable computing capacity in the AWS cloud.
Leveraging it enables organizations to develop and deploy applications faster, without needing to invest in hardware upfront. 
Users can launch virtual servers, configure security and networking, and manage cookies from an intuitive dashboard. 
EC2 makes life easier for developers by providing secure, and resizable compute capacity in the cloud.
It greatly eases the process of scaling up or down, can be integrated into several other services, and comes with a plan where you only pay for how much you use it. 

**Instance**
An instance is a virtual server in the cloud. Its configuration at launch is a copy of the AMI that you specified when you launched the instance.

**AMI**
An AMI is a template that is used to create a new instance—or virtual machine—based on user requirements.
The AMI will contain information about the software, operating system, volume, and access permissions. There are two types of AMIs:
i) **Predefined AMIs:** Amazon creates these, and the user can modify them.
ii) **Custom AMIs:** The user also creates these, and they can be reused. These AMIs are also available in the AMI Marketplace 
An Amazon Machine Image (AMI) is a template that contains a software configuration (for example, an operating system, an application server, and applications).
From an AMI, you launch an instance, which is a copy of the AMI running as a virtual server in the cloud. You can launch multiple instances of an AMI.

When an instance is stopped, the instance performs a normal shutdown, and then transitions to a stopped state.
All of its Amazon EBS volumes remain attached, and you can start the instance again at a later time.

When an instance is terminated, the instance performs a normal shutdown.
The root device volume is deleted by default, but any attached Amazon EBS volumes are preserved by default, determined by each volume's deleteOnTermination attribute setting.
The instance itself is also deleted, and you can't start the instance again at a later time.

**Instance type**
Each instance type offers different compute, memory, and storage capabilities, and is grouped in an instance family based on these capabilities.
Instance types belong to five main families:

i) Compute-optimized: For situations that require a lot of processing power 

ii) Memory-optimized: For setting up something to do with your in-memory cache

iii) GPU optimized: For setting up a gaming system, or something with the requirement of a large graphic

iv) Storage optimized: When you need to set up a storage server

v) General-purpose: When everything is equally balanced
Select an instance type based on the requirements of the application or software that you plan to run on your instance.

**Configuring security groups:**
A *security group* is a virtual firewall which is controlling the traffic to your EC2 instances.
Security group consists of inbound rules, and the inbound rules are created by us only. Suppose I add three inbound rules, i.e., HTTP, SSH, and HTTPS.
These are used to specify rules based on which users are given access to the EC2 instance.
You set up the type of security, protocol, the port range, and source (from where the incoming traffic is coming from). 
Incoming traffic has to be explicitly specified, and outgoing traffic is open.

**EBS stands for Elastic Block Store**
EC2 is a virtual server in a cloud while EBS is a virtual disk in a cloud.
Amazon EBS allows you to create storage volumes and attach them to the EC2 instances.
