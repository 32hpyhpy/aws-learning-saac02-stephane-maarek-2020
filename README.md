# aws-learning-saac02-stephane-maarek-2020
This is the notes created from Stephane Maarek course - AWS SAACO2 2020
 - The course link is [Ultimate AWS CSA Associate 2020](https://www.udemy.com/share/102CPBAEYTdFxbQ3Q=/)

- [Section 1: Introduction - AWS Certified Solutions Architect Associate](https://github.com/Aamir-Meman/aws-learning-saac02-stephane-maarek-2020#section-1-introduction---aws-certified-solutions-architect-associate)
- [Section 3 AWS Fundamentals: IAM and EC2](https://github.com/Aamir-Meman/aws-learning-saac02-stephane-maarek-2020#section-3-aws-fundamentals-iam-and-ec2)
   - [3.1 AWS Regions and AZs](https://github.com/Aamir-Meman/aws-learning-saac02-stephane-maarek-2020#31-aws-regions-and-azs)
   - [3.2 IAM Introduction](https://github.com/Aamir-Meman/aws-learning-saac02-stephane-maarek-2020#32-iam-introduction)
   - [3.5 EC2 Introduction](https://github.com/Aamir-Meman/aws-learning-saac02-stephane-maarek-2020#35-ec2-introduction)
   - [3.12 Introduction to Security Groups](https://github.com/Aamir-Meman/aws-learning-saac02-stephane-maarek-2020#312-introduction-to-security-groups)
   - [3.14 Private vs Public vs Elastic IP](https://github.com/Aamir-Meman/aws-learning-saac02-stephane-maarek-2020#314-private-vs-public-vs-elastic-ip)
   - [3.16 EC2 User Data](https://github.com/Aamir-Meman/aws-learning-saac02-stephane-maarek-2020#316-ec2-user-data)
   - [3.17 EC2 Instance Launch Types](https://github.com/Aamir-Meman/aws-learning-saac02-stephane-maarek-2020#317-ec2-instance-launch-types)
   - [3.18 Spot Instances & Spot Fleet](https://github.com/Aamir-Meman/aws-learning-saac02-stephane-maarek-2020#318-spot-instances--spot-fleet)
   - [3.19 EC2 Instance Types Deep Dive](https://github.com/Aamir-Meman/aws-learning-saac02-stephane-maarek-2020#319-ec2-instance-types-deep-dive)
   - [3.20 EC2 AMIs](https://github.com/Aamir-Meman/aws-learning-saac02-stephane-maarek-2020#320-ec2-amis)
   - [3.21 Cross Account AMI Copy (FAQ + Exam Tip)](https://github.com/Aamir-Meman/aws-learning-saac02-stephane-maarek-2020#321-cross-account-ami-copy-faq--exam-tip)
   - [3.22 EC2 Placement Groups](https://github.com/Aamir-Meman/aws-learning-saac02-stephane-maarek-2020#322-ec2-placement-groups)
   - [3.23 Elastic Network Interfaces (ENI) with hands On](https://github.com/Aamir-Meman/aws-learning-saac02-stephane-maarek-2020#323-elastic-network-interfaces-eni-with-hands-on)
   - [3.24  EC2 Hibernate](https://github.com/Aamir-Meman/aws-learning-saac02-stephane-maarek-2020#324-ec2-hibernate)
- [Section 4 High Availability and Scalability: ELB and ASG](https://github.com/Aamir-Meman/aws-learning-saac02-stephane-maarek-2020#section-4-high-availability-and-scalability-elb-and-asg)
   - [4.1 High Availability and Scalability](https://github.com/Aamir-Meman/aws-learning-saac02-stephane-maarek-2020#41-high-availability-and-scalability)
   - [4.2 Elastic Load Balancing (ELB) Overview](https://github.com/Aamir-Meman/aws-learning-saac02-stephane-maarek-2020#42-elastic-load-balancing-elb-overview)
   - [4.3 Classic Load Balancer(CLB) with Hands On](https://github.com/Aamir-Meman/aws-learning-saac02-stephane-maarek-2020#43-classic-load-balancerclb-with-hands-on)
   - [4.4 Application Load Balancer (v2)](https://github.com/Aamir-Meman/aws-learning-saac02-stephane-maarek-2020#44-application-load-balancer-v2)
   - [4.5 Network Load Balancer](https://github.com/Aamir-Meman/aws-learning-saac02-stephane-maarek-2020#45-network-load-balancer)
   - [4.6 Load Balancer Stickiness](https://github.com/Aamir-Meman/aws-learning-saac02-stephane-maarek-2020#46-load-balancer-stickiness)
   - [4.7 Cross-Zone Load Balancing](https://github.com/Aamir-Meman/aws-learning-saac02-stephane-maarek-2020#47-cross-zone-load-balancing)
   - [4.8 SSL/TLS - Basics](https://github.com/Aamir-Meman/aws-learning-saac02-stephane-maarek-2020#48-ssltls---basics)
   - [4.9 ELB - Connection Draining](https://github.com/Aamir-Meman/aws-learning-saac02-stephane-maarek-2020#49-elb---connection-draining)
   - [4.10 Auto Scaling Groups(ASG) Overview](https://github.com/Aamir-Meman/aws-learning-saac02-stephane-maarek-2020#410-auto-scaling-groupsasg-overview)
   - [4.12 Auto Scaling Group - Scaling Policies](https://github.com/Aamir-Meman/aws-learning-saac02-stephane-maarek-2020#412-auto-scaling-group---scaling-policies)
   - [4.13 ASG for Solutions Architect](https://github.com/Aamir-Meman/aws-learning-saac02-stephane-maarek-2020#413-asg-for-solutions-architect)
- [Section 5 EC2 Storage- EBS and EFS](https://github.com/Aamir-Meman/aws-learning-saac02-stephane-maarek-2020#section-5-ec2-storage---ebs-and-efs)  
   - [5.1 EBS Intro](https://github.com/Aamir-Meman/aws-learning-saac02-stephane-maarek-2020#51-ebs-intro)
   - [5.3 EBS Volume Types Deep Dive](https://github.com/Aamir-Meman/aws-learning-saac02-stephane-maarek-2020#53-ebs-volume-types-deep-dive)
   - [5.4 EBS Operations: Snapshots](https://github.com/Aamir-Meman/aws-learning-saac02-stephane-maarek-2020#54-ebs-operations-snapshots)
   - [5.5 EBS Operations: Migrations](https://github.com/Aamir-Meman/aws-learning-saac02-stephane-maarek-2020#55-ebs-operations-migrations)
   - [5.6 EBS Operations: Volume Encryption](https://github.com/Aamir-Meman/aws-learning-saac02-stephane-maarek-2020#56-ebs-operations-volume-encryption)
   - [5.7 EBS vs Instance Store](https://github.com/Aamir-Meman/aws-learning-saac02-stephane-maarek-2020#57-ebs-vs-instance-store)
   - [5.8 EBS RAID Configuration](https://github.com/Aamir-Meman/aws-learning-saac02-stephane-maarek-2020#58-ebs-raid-configuration)
   - [5.9 EFS Overview](https://github.com/Aamir-Meman/aws-learning-saac02-stephane-maarek-2020#59-efs-overview)
   - [5.12 EBS vc EFS - Elastic Block Storage](https://github.com/Aamir-Meman/aws-learning-saac02-stephane-maarek-2020#512-ebs-vc-efs---elastic-block-storage)
# Section 1: Introduction - AWS Certified Solutions Architect Associate
## 1.0 What is AWS
- Amazon Web Services is a Cloud Provider.
- They provide you with servers and services that you can use on demand and scale easily.
- AWS has revolutionized IT over time.
- AWS powers some of the biggest websites in the world
  - Amazon.com
  - Netflix

# Section 3 AWS Fundamentals: IAM and EC2

## 3.1 AWS Regions and AZs 
**Q=1 What are AWS Regions?**
- AWS has Regions all around the world.
- Names can be: us-east-1 , eu-west-3
- A region is a cluster of data centers
- Most AWS services are region-scoped.
---
**Q=2 What are AWS Availaibilty Zones?**
- Each region has many availability zones :- (usually 3, min is 2, max is 6)
   For example:- 1) ap-southeast-2a 2)ap-southeast-2b and 3)ap-southeast-2c
- Each Availaibilty Zone(AZ) is one or more discrete data centers with redundant power, networking and connectivity.
- They are seperate from each other, so that they are isolated from disasters.
- They are connected with high bandwidth, ultra-low latency networking.

## 3.2 IAM Introduction

**Q=1 What is an IAM**
- IAM (Identity and Access Management)
- Your whole AWS security is there:
  - Users :- Usually a physical person
  - Groups :- Functions(admins, devops) , Teams(engineering,design..) Contains users!
  - Roles :- **Internal usage within AWS resources**
- Root account should never be used (and shared)
- Users must be created with proper permissions
- IAM is at the center of AWS
- Policies are written in JSON(JavaScript Object Notation)
- **Policies (JSON Documents) Defines what each of the above can and cannot do.**
- IAM has a **global** view.
- Permissions are governed by Policies(JSON).
- MFA (Multi Factor Authentication) can be setup
- IAM has predefined "managed policies"
- **It is best to give users the minimal amount of permissions they need to perform their job** (least privilege principles)
---
**Q=2 What are IAM Federation**
- Big enterprises usually integrate their **own repository** of users with IAM.
- This way, one can login into AWS using their company credentials.
- Identity Federation uses the SAML standard (Active Directory).
---
**Q=3 IAM 101 Brain Dump**
- One IAM **User** per PHYSICAL PERSON
- One IAM **Role** per Application
- IAM credentials should NEVER BE SHARED
- Never,ever, ever,ever, write IAM credntials in code. EVER.
- And even less, NEVER EVER EVER COMMIT YOUR IAM credentials.
- Never use the ROOT account except for initial setup.
- Never use ROOT IAM Credentials.

## 3.5 EC2 Introduction

**Q=1 What is EC2 (Elastic Compute Cloud)**
- EC2 is one of the most popular of AWS offering.
- It mainly consist in the capability of:
  - Renting Virtual Machines (EC2)
  - Storing data on virtual drives (EBS)
  - Distributing load across machines(ELB)
  - Scaling the services using an auto-scaling group (ASG)

## 3.12 Introduction to Security Groups

**Q=1 What is SG's?**
- Security Groups are the fundamental of network security in AWS.
- They control **how traffic is allowed into or out of our EC2 Machines**.
- It is the most **fundamental skill to learn to troubleshoot networking issues**.
---
**Q=2 What are SG's i.e. Deeper Dives?**'
- Security Groups are acting as a "firewall" on EC2 instances.
- They regulate
   - Access to Ports
   - Authorised IP ranges - IPv4 and IPv6
   - Control of inbound network (from other to the instance)
   - Control of outbound network (from the instance to other)
---
**Q=3 Security Groups Good to know ?**
- It can be attached to multiple instances.
- Locked down to a region/VPC combination.
- Does **live "outside" the EC2** - if traffic is blocked the EC2 instance won't see it
- **It's good to maintain one seperate security group for SSH access**
- If your application is not accessible (time out), then it's a security group issue.
- If your application gives a "connection refused" error, then it's an application error or it is not launched.
- All **inbound** traffic is blocked by default.
- All **outbound** traffic is authorised by default.

## 3.14 Private vs Public vs Elastic IP

**Q=1 Fundamental Difference between Private and Public IP (IPv4)**
- Public IP
  - Public IP **means the machine can be identified on the internet (www)**
  - Must be **unique across the whole web (not two machines can have the same public IP).**
  - Can be **geo-located easily**
- Private IP
  - Private IP **means the machine can only be identified on a private network only.**
  - The IP must be unique across the private network.
  - But **two different private networks (two companies) can have the same IPs.**
  - Machines **connect to WWW using an internet gateway (a proxy)**
  - Only a **specified range of IPs can be used as private IP.**
---
**Q=2 What is an Elastic IP's?**
- When you **stop and then start an EC2 instance, it can change its public IP.**
- If you need to have a **fixed public IP** for your instance, you need an Elastic IP.
- An Elastic IP is a public IPv4 IP you own as long as you don't delete it.
- You can attach it to one instance at a time.
- With an Elastic IP address,you can mask the failure of an instance or software by rapidly remapping the address to another instance in your account.
- You can only have **5 Elastic IP** in your account (you can ask AWS to increase that).
- Overall, try to avoid using Elastic IP:
  - They often **reflect poor architetural decisions**.
  - Instead, use a random public IP and register a DNS name to it
  - Or, as well see later, use a Load Balancer and don't use a public IP.
---
**Q=3 Private vs Public IP (IPv4)**
- By default, your EC2 machine comes with:
  - A private IP for th internal AWS Network
  - A public IP for the WWW.
- When we are doing SSH into our EC2 machines:
  - We can't use a private IP, because we are not in the same network
  - We can only use the public IP
- If your machine is stopped and then started, the public IP can change.

## 3.16 EC2 User Data

**Q=1 What is EC2 User Data?**
- It is possible to bootstrap our instances using an EC2 User data script.
- bootstrapping means launching commands when a machine starts
- The **script is only run once at the instance first start**
- EC2 user data is used to automate boot tasks such as:
  - Installing updates
  - Installing software
  - Downloading common files from the internet
  - Anything you can think of
- The **EC2 User Data Script runs with the root user**

## 3.17 EC2 Instance Launch Types

**Q=1 What are EC2 Instance Launch Types?**
- **On Demand Instances**:- short workload, predictable pricing
- Reserved: **(MINIMUM 1 year)**
  - Reserved Instances: long workloads
  - Convertible Reserved Instances:  Long workloads with flexible instances
  - Scheduled Reserved Instances: example every Thursday between 3 and 6 pm
- Spot Instances: short workload, **for cheap**, can lose instances (less reliable)
- Dedicated Instances: no other customer will share your hardware
- Dedicated Hosts: **book an entire physical server**, control instance placement.
---
**Q=2 What is EC2 On Demand?**
- Pay for what you use (billing per second, after the first minute)
- Has the highest cost but no upfront payment.
- No long term commitment
- **Recommended for short-term and un-interrupted workloads, where you can't predict how the application will behave.**
---
**Q=3 What are EC2 reserved Instances?**
- Up to **75% discount** compared to On-demand.
- Pay upfront for what you use with long term commitment.
- Reservation period can be 1 or 3 years.
- Reserve a specific instance type.
- **Recommended for steady state usage applications(think database)**
---
**Q=4 What are Convertible Reserved Instance?**
- It can change the EC2 instance type.
- Up to 54% discount.
---
**Q=5 What are Scheduled Reserved Instances?**
- Launch within time window you reserve.
- When you require a fraction of day/ week/ month.
---
**Q=6 What are EC2 Spot Instances?**
- It can get a discount of up to 90% compared to On-demand.
- Instances that you can "lose" at any point of time if your max price is less than the current spot price.
- The **MOST** efficient instances in AWS
- Useful for workloads that are resilient to failure
   - Batch jobs
   - Data analysis
   - Image processing
   - ...
- Not great for critical jobs or databases
- Great Combo:- Reserved Instances for baseline + On-Demand & Spots for peaks.
---
**Q=7 What are EC2 Dedicated Hosts?**
- Physical dedicated EC2 server for your use.
- Full control of EC2 Instance placement.
- Visibility into the underlying sockets/ physical cores of the hardware.
- Allocated for your account for a 3 year period reservation.
- More Expensive

- Useful for software that have complicated licensing model(BYOL - Bring Your Own License)
- Or for companies that have strong regulatory or compliance needs.
---
**Q=8 What are EC2 Dedicated Instances?**
- Instances running on hardware that's dedicated to you.
- May **share hardware with other instances in same account**.
- No control over instance placement ( can move hardware after Stop/Start)

## 3.18 Spot Instances & Spot Fleet

**Q=1 What is EC2 Spot Instance Requests?**
- It can get a discount of up to 90% compared to On-demand
- Define max spot price and get the instance while current spot price < max
  - The hourly spot price varies based on offer and capacity
  - If the current spot price > you max price you can choose to stop or terminate your instance with a 2 minutes grace period.
- Other Strategy: **Spot Block**
   - "block" spot instance during a specified time frame (1 to 6 hours) without interruptions
   - In rare situations, the instance may be reclaimed
- **Used for batch jobs, data analysis or workloads that are resilent to failures**.
- Not great for critical jobs or databases.
---
**Q=2 How to terminate Spot Instances?**
- You can only cancel Spot Instance requests that are open, active or disabled.
- **Cancelling a Spot Request does not terminate instances**.
- You must first cancel a Spot Request, and then terminate the associated Spot Instances.
---
**Q=3 What are Spot fleets?**
- **Spot Fleets = set of Spot Instances + (optional) On-Demand Instances.**
- The Spot Fleet will try to meet the target capacity with price constraints
   - Define possible launch pools: instance type(m5.large), OS, AZ.
   - Can have multiple launch pools, so that the fleet can choose
   - Spot Fleet stops launching instances when reaching capacity or max cost.
- Strategies to allocate Spot Instances:
   - lowestPrice: from the pool with the lowest price (cost optimization, short workload)
   - diversified: distributed across all pools (great for availaibility, long workloads)
   - capacityOptimized: pool with optimal capacity for the number of instances
- Spot Fleets allow us to automatically request Spot Instances with the lowest price.

## 3.19 EC2 Instance Types Deep Dive

**Q=1 The EC2 Instance Types = Mains ones**
- R: applications **that needs a lot of RAM** - in-memory caches.
- C: applications **that needs good CPU** - compute/databases.
- M: applications **that are balanced (think "medium")** - general/ web app
-  I: applications **that need good local I/O (instance storage)** - databases
- G: applications **that need a GPU** - video rendering / machine learning.
- T2/T3: burstable instances (up to a capacity)
- T2/T3 - unlimited: unlimited burst 
---
**Q=2 What are Burstable Instances (T2/T3)?**
- AWS has concept of burstable instances (T2/T3) machines.
- Burst means that overall, the instance has OK CPU performance.
- When **the machine needs to process something unexpected ( a spike in load for example), it can burst, and CPU can be VERY good**.
- if the machine bursts, it utilizes "burst credits"
- If all the credits are gone, **the CPU becomes BAD**
- If the machine stops bursting, credits are accumulated over time.
- Burstable instances can be amazing to handle unexpected traffic and getting the insurance that it will be handled correctly.
- If your **instance consistently runs low on credit, you need to move to a different kind of non-burstable instance.**
---
**Q=3 What is T2/T3 Unlimited?**
- On Nov 2017: **It is possible to have an "unlimited burst credit balance"**
- You pay extra money if you go over your credit balance, but you don't lose in performance
- Overall, **it is a new offering, so be careful, costs could go high if you are not monitoring the health of your instances.**

## 3.20 EC2 AMIs

**Q=1 What's an AMI**
- As we saw, AWS comes with base images such as:
  - Ubuntu
  - Fedora
  - RedHat
  - Debian
  - Windows
  - Etc...
- These images can be customized at runtime using EC2 User data
- But what if we could create our own image, ready to go?
- **That's an AMI - an image use to create our instances**
---
**Q=2 Why would you use a custom AMI?**
- Using a custom built AMI can provide the following advantages:
  - Pre-installed packages needed
  - Faster boot time (no need for ec2 user data at boot time)
  - Machine comes configured with monitoring/enterprise software
  - Security concerns - control over the machines in the network
  - Control of maintenance and updates of AMIs over time
  - Active Directory Integration out of the box
  - Installing your app ahead of time (for faster deploys when auto-scaling)
  - Using someone else's AMI that is optimised for running an app,DB etc..
- **AMI are built for a specific AWS region (!)**
---
**Q=3 Using Public AMIs**
- You can leverage AMIs from other people
- You can also pay for other people's AMI by the hour
  - These people have optimised the software
  - The machine is easy to run and configure
  - You basically rent "expertise" from the AMI creator
- **AMI can be found and published on the Amazon Marketplace**
- **Warning**
  - Do not use an AMI you don't trust.
  - Some AMIs might come with malware or may not be secure for enterprise.
---
**Q=4 AMI Storage**
- Your AMI take place and they live in Amazon S3.
- Amazon S3 is a durable, cheap and resilient storage where most of your backups will live(but you won't see them in the S3 console).
- **By default, your AMIs are private, and locked for your account/region**
- You can also make your AMIs public and share them with other AWS accounts or sell them on the AMI Marketplace
----------
**Q=5 AMI Pricing**
- AMIs live in Amazon S3, **so you get charged for the actual space in takes in Amazon S3**.
- Overall it is **quite inexpensive** to store private AMIs
- Make sure to remove the AMIs you don't use.
-------
## 3.21 Cross Account AMI Copy (FAQ + Exam Tip)
**Q=1 What are the permissions for cross account AMIs copy?**
- You can share an AMI with another AWS account.
- Sharing an AMI does not affect the ownership of the AMI.
- If you **copy** an AMI that has been shared with your account, you are the **owner** of the target AMI in your account.
- To copy an AMI that was shared with you from another account, **the owner of the source AMI must grant you read permissions for the storage that backs the AMI, either the associated EBS snapshot(for an Amazon EBS-backed AMI) or an associated S3 bucket(for an instance store-backed AMI)**.
- **Limits**:
  - You can't copy an encrypted AMI that was shared with you from another account. Instead, if the underlying snapshot and encryption key were shared with you, you can copy the snapshot while re-encrypting it with a key of your own. You own the copied snapshot, and can register it as a new AMI.
  - You can't copy an AMI with an associated **billingProduct** code that was shared with you from another account.This includes Windows AMIs and AMIs from the AWS Marketplace. To copy a shared AMI with a **billingProduct** code, launch an EC2 instance in your account using the shared AMI and then create an AMI from the instance.
 
## 3.22 EC2 Placement Groups
**Q=1 What are EC2 Placement Groups?**
- Sometime you want control over the EC2 Instance placement strategy.
- That strategy can be defined usig placement groups.
- When you create a placement group, you specify one of the following strategies for the group:
  - **Cluster** - clusters instances into a low-latency group in a single Availability Zone.
  - **Spread** - spread instances across underlying hardware (max 7 instances per group per AZ)**critical applications**.
  - **Partition** -spread instances across many **different partitions** (which rely on different sets of racks)within an AZ. Scales to 100 of EC2 instances per group (Hadoop, Cassandra, Kafka)
---
**Q=2 What is EC2 Cluster Placement Groups?**
 - Pros:- Great network (10 - Gbps badnwidth between instances)
 - Cons:- If the rack fails, all instances fails at the same time
 - Use case:
   - **Big Data job that needs to complete fast**
   - **Application that needs extremely low latency and high network throughput**
---
**Q=3 What is EC2 Spread Placement Groups**
- Pros:
  - Can span across Availability Zones (AZ)
  - Reduced risk is simultaneous failure
  - EC2 Instances are on different physical hardware
- Cons:
  - Limited to 7 instances per AZ per placement group
- Use Case:
  - **Application that needs to maximize high availability**
  - **Critical Applications where each instance must be isolated from failure**
---
**Q=4 What is EC2 Partition Placement Groups**
 - Up to **7** partitions per AZ.
 - Up to **100s** of EC2 instances
 - The instances in a partition do not share racks with the instances in the other partitions.
 - A partition failure can affect many EC2 but won't affect other partitions.
 - EC2 instances get access to the partition information as metadata
 - Use cases:
   - **HDFS, HBase, Cassandra, Kafka**

## 3.23 Elastic Network Interfaces (ENI) with hands On
**Q=1 What is Elastic Network Interfaces(ENI)?**
 - Logical component in a VPC that represents a **virtual network card**
 - The ENI can have the following attributes:
   - **Primary private IPv4, one or more secondary private IPv4**
   - One Elastic IP (IPv4) per private IPv4
   - One Public IP (IPv4)
   - One or more security groups
   - A MAC address
 - **You can create ENI independently and attach them on the fly(move them) on EC2 instances for failover**
 - Bound to a specific availability zone (AZ)

## 3.24 EC2 Hibernate
**Q=1 What are EC2 Hibernate**
 - We know we can stop, terminate instances
   - Stop: The data on disk(EBS) is kept intact in the next start.
   - Terminate: any EBS volumes(root) also set-up to be destroyed is lost.
 - On start, the following happens:
   - First start: the OS boots and the EC2 User Data script is run
   - Following starts: the OS boots up.
   - **Then your application starts, caches get warmed up, and that can take time!**
 - Introducing **EC2 Hibernate**:
   - The in-memory(RAM) state is preserved.
   - The instance boot is much faster!(the OS is not stopped/restarted)
   - **Under the hood: the RAM state is written to a file in the root EBS volume**
   - **The root EBS volume must be encrypted**
 - Use cases:
   - **long-running processing**
   - **saving the RAM state**
   - **services that take time to initialize**

**Q=2 EC2 Hibernate - Good to know**
 - Supported instance families - C3,C4,C5,M3,M4,M5,R3,R4 and R5
 - Instance RAM Size - must be less than 150 GB.
 - Instance size - not supported for bare metal instances.
 - AMI - Amazon Linux 2, Linux AMI, Ubuntu and Windows
 - Root Volume - must be **EBS**,encrypted,not instance store and **large**
 - Avaialaible for On-Demand and Reserved Instances
 - An instance cannot be hibernated more than 60 days.

# Section 4 High Availability and Scalability: ELB and ASG

## 4.1 High Availability and Scalability
**Q=1 What does it mean by Scalability and High Availability**
 - Scalability means that an application can handle greater loads by adapting
 - There are 2 kinds of scalability:
   - Vertical Scalability
   - Horizontal Scalability(= elasticity)
 - **Scalability is linked but different to High Availability**

 **Q=2 What is Vertical Scalability?**
  - Vertically Scalability means increasing the size of the instance
  - For example, your application runs on a t2.micro
  - Scaling that application vertically means running it on a t2.large
  - Vertical Scalability is very common for non distributed systems such as Database.
  - **RDS,ElasticCache are service that can scale vertically.**
  - There's usually a limit to how much you can vertically scale(hardware limit)

**Q=3 What is Horizontal Scalability?**
 - Horizontal Scalability means **increasing the number of instances / systems for your application**
 - Horizontal scaling implies distributed systems
 - This is very common for web applications/ modern applications.
 - It is easy to horizontally scale thanks the cloud offerings such as **Amazon EC2** 

**Q=4 What is High Availability?**
 - High Availability usually goes hand in hand with **horizontal scaling**.
 - High Availability means running your application / system in at least 2 data centers (== Availability Zones)
 - The goal of high availability is to survive a data center loss.
 - **The high availability can be passive (for RDS Multi AZ for example)**.
 - **The high availability can be active (for horizontal scaling)**

**Q=5 High Availability and Scalability for EC2**
 - Vertical Scaling: Increase instance size **(= scale up / down)**
 - Horizontal Scaling: Increase number of instances **(= scale out / in)**
   - ASG(Auto Scaling Group)
   - Load Balancer
 - **High Availability: Run instances for the same application across Multi AZ**
   - Auto Scaling Group multi AZ
   - Load Balancer multi AZ

## 4.2 Elastic Load Balancing (ELB) Overview
**Q=1 What is Load Balancing?**
 - Load balancers are servers that forward internet traffic to multiple servers (EC2 Instances) downstream.

**Q=2 Why use a Load Balancer**
 - Spread load across multiple downstream instances.
 - Expose a single point of access (DNS) to your application.
 - Seamlessly handle failures of downstream instances.
 - Do regular health checks to your instances.
 - Provide SSL termination (HTTPS) for your websites.
 - Enforce stickiness with cookies.
 - High availability across zones.
 - Seperate public traffic from private traffic.

 **Q=3 Why use an EC2 Load Balancer?**
  - An ELB(EC2 Load Balancer) is a **managed load balancer**
    - AWS guarantees that it will be working
    - AWS takes care of upgrades, maintenance, high availability
    - AWS provides only a few configuration knobs
  - It costs less to setup your own load balancer but it will be a lot more effort on your end.
  - It is integrated with many AWS offerings/ services.

 **Q=4 What is a Health Check?**
  - Health Checks are crucial for Load Balancers
  - They enable the load balancer to know if instances it forwards traffic to are available to reply to requests.
  - The health check is done on a **port** and a **route** (/health is common)
  - If the response is not 200 (OK), then the instance is unhealthy

**Q=5 Types of Load Balancer**
 - AWS has 3 kinds of managed load balancers:
   - Classic Load Balancer(v1 - old generation) - 2009
     - HTTP, HTTPS, TCP
   - Application Load Balancer (v2 - new generation) - 2016
     - **HTTP, HTTPS, WebSocket**
   - Network Load Balancer (v2- new generation) - 2017
     - **TCP, TLS (secure TCP) & UDP (secure UDP)**
 - Overall, it is recommended to use the newer/v2 generation load balancers as they provide more features.
 - You can setup **internal(private) or external(public) ELBs**.

**Q=6 Load Balancer Good to Know**
 - LBs can scale but not instantaneously - contact AWS for a "warm-up"
 - Troubleshooting
   - 4xx errors are client induced errors
   - 5xx errors are application induced errors
   - Load Balancer Errors 503 means at capacity or no registered target
   - If the LB cannot connect to your application, check your security groups.
 - Monitoring
   - ELB access logs will log all access requests (so you can debug per request)
   - CloudWatch Metrics will give you aggregate statistics (ex: connections count)

## 4.3 Classic Load Balancer(CLB) with Hands On
**Q=1 Why Classic Load Balancer(v1)**
 - Support TCP (Layer 4), HTTP and HTTPS (Layer 7)
 - **Health checks are TCP or HTTP based**
 - Fixed hostname
   - xxx.region.elb.amazonaws.com

## 4.4 Application Load Balancer (v2)
**Q=1 What is an application load balancer(ALB)?**
 - Application Load Balancers is Layer 7 (HTTP).
 - Load Balancing to **multiple HTTP applications** across machines(target groups)
 - Load Balancing to **multiple applications** on the same machine (ex:containers)
 - Support for HTTP/2 and WebSocket
 - Support redirects (from HTTP to HTTPS for example)
 - Routing tables to different target groups:
   - Routing based on **path** in URL (example.com/users & example.com/posts)
   - Routing based on **hostname** in URL (one.example.com & other.example.com)
   - Routing based on Query String, Headers (example.com/users?**id=123&order=false**)
 - ALB are a great fit for microservices and container-based application(example: Docker and Amazon ECS)
 - Has a port mapping feature to redirect to a dynamic port in ECS
 - **In comparison, we'd need multiple Classic Load Balancer per application**

**Q=2 What are the Target groups**
 - EC2 instances (can be managed by an Auto Scaling Group) - HTTP
 - ECS tasks (managed by ECS itself) - HTTP
 - Lambda functions - HTTP request is translated into a JSON event.
 - IP Addresses - must be **private IPs** 
 - ALB can route to multiple target groups.
 - Health checks are at the target group level. 

**Q=3 Good to know**
 - Fixed hostname (xxx.region.elb.amazonaws.com)
 - The application servers don't see the IP of the client directly.
   - The true IP of the client is inserted in the header X-Forwarded-For
   - We can also get Port (X-Forwarded-Port) and proto (X-Forwarded-Proto)

## 4.5 Network Load Balancer
**Q=1 What is NLB(v2)?**
 - NLB's(Layer 4) allow to:
   - **Forward TCP & UDP traffic to your instances**
   - Handle millions of request per seconds
   - Less latency ~100ms (vs 400 ms for ALB)
 - NLB has **one static IP per AZ**, and supports assigning Elastic IP (helpful for whitelisting specific IP)
 - NLB are used for **extreme performance, TCP or UDP traffic**

## 4.6 Load Balancer Stickiness
**Q=1 What is Load Balancer Stickiness?**
 - It is possible to implement stickiness so that the same client is always redirected to the same instance behind a load balancer.
 - This works for Classic Load Balancers & Application Load Balancers.
 - The "cookie" used for stickiness has an expiration date you control.
 - Use case: make sure the user doesn't lose his session data
 - Enabling stickiness may bring imabalance to the load over the backend EC2 instances.

## 4.7 Cross-Zone Load Balancing
**Q=1 What is Cross-Zone Load Balancing?**
 - **With Cross-Zone Load Balancing: each load balancer instance distributes evenly across all registered instances in all AZ**
 - Otherwise, each load balancer node distributes requests evenly across the registered instances in its Availability Zone only.
 - Classic Load Balancer
   - Disabled by default
   - No charges for inter AZ data if enabled
 - Application Load Balancer
   - Always on (can't be disabled)
   - No charges for inter AZ data 
 - Network Load Balancer
   - Disabled by default
   - **You pay charges($) for inter AZ data if enabled**

## 4.8 SSL/TLS - Basics
**Q=1 What is a SSL/TLS?**
 - An SSL Certificate allows traffic between your clients and your load balancer to be encrypted in transit (in-flight encryption)
 - **SSL** refers to Secure Sockets Layer, used to encrypt connections
 - **TLS** refers to Transport Layer Security, which is a newer version
 - Nowadays, **TLS certificates are mainly used**, but people still refer as SSL
 - Public SSL certificates are issued by Certificate Authorities (CA)
 - Comodo, Symantec, GoDaddy, GlobalSign, Digicert, Letsencrypt, etc
 - SSL certficates have an expiration date (you set) and must be renewed

**Q=2 What is the Load Balancer - SSL Certificates** 
 - The load balancer uses an X.509 certificate (SSL/TLS server certificate)
 - You can manage certificates using **ACM** (AWS Certificate Manager)
 - You can create upload your own certificates alternatively
 - HTTPS listener:
   - You must specify a default certificate
   - You can add an optional list of certs to support multiple domains
   - **Clients can use SNI (Server Name Indication) to specify the hostname they reach**
   - Ability to specify a security policy to support older versions of SSL /TLS (legacy clients)

**Q=3 What is the SSL - Server Name Indication(SNI)**
 - SNI solves the problem of loading **multiple SSL certificates onto one web server** (to serve multiple websites)
 - It is a "newer" protocol, and requires the client to **indicate** the hostname of the target server in the initial SSL handshake
 - The server will then find the correct certificate, or return the default one
 - Note: 
   - Only works for **ALB** and **NLB** (newer generation), CloudFront
   - Does not work for CLB (older generation)

**Q=4 What is Elastic Load Balancers - SSL Certificates**
 - Classic Load Balancer
   - Support only one SSL certificate
   - Must use multiple CLB for multiple hostname with multiple SSL certificates
 - Application Load Balancer (v2)
   - Supports multiple listeners with multiple SSL certificates
   - Uses Server Name Indication (SNI) to make it work
 - Network Load Balancer (v2)
   - Supports multiple listeners with multiple SSL certificates
   - Uses Server Name Indication (SNI) to make it work

## 4.9 ELB - Connection Draining
**Q=1 What is an ELB connection Draining?**
 - Feature nameing:
    - CLB: Connection Draining
    - Target Group: Deregisteration Delay (for ALB & NLB)
 - **Time to complete "in-flight requests" while the instance is de-registering or unhealthy**
 - Stops sending new requests to the instance which is de-registering
 - Between 1 to 3600 seconds, default is 300 seconds
 - Can be disabled (set value to 0)
 - **Set to a low value if your requests are short**

## 4.10 Auto Scaling Groups(ASG) Overview
**Q=1 What is an Auto Scaling Group?**
 - In real-life, the load on your websites and application can change
 - In the cloud, you can create and get rid of servers very quickly
 - The goal of an Auto Scaling Group(ASG) is to:
   - Scale out(add EC2 instance) to match an increased load
   - Scale in (remove EC2 instance) to match a decreased load
   - Ensure we have a minimum and a maximum number of machines running.
   - Automatically Register new instances to a load balancer

**Q=2 What is the attribute used in defining ASGs** 
 - A launch configuration
   - AMI + Instance Type
   - EC2 User Data
   - EBS Volumes
   - Security Groups
   - SSH Key Pair
 - Min Size/ Max Size / Initial Capacity
 - Network + Subnets Information
 - Load Balancer Information
 - Scaling Policies 

**Q=3 What is an Auto Scaling Alarms**
 - It is possible to scale an ASG based on CloudWatch alarms.
 - An Alarm monitors a metric (such as average cpu)
 - **Metrics are computed for the overall ASG instances**
 - Based on the alarm:
   - We can create scale-out policies (increase the number of instances)
   - We can create scale-in policies (decrease the number of instances)

**Q=4 What is an Auto Scaling New Rules**
 - It is now possible to define "better" auto scaling rules that are directly managed by EC2 instances
   - Target Average CPU Usage
   - Number of requests on the ELB per instance
   - Average Network In
   - Average Network Out
 - These rules are easier to set up and can make more sense 

**Q=5 What are Auto Scaling Custom Metrics**
 - We can auto scale based on a custom metric (ex: number of connected users)
 - 1. Send custom metric from application on EC2 to CloudWatch (PutMetricAPI)
 - 2. Create CloudWatch alarm to react to low/ high values
 - 3. Use the CloudWatch alarm as the scaling policy for ASG

**Q=6 What is an ASG Brain Dump**
 - Scaling policies can be on CPU, Network...and can even be on custom metrics or based on a schedule (if you know your visitors patterns)
 - ASGs use Launch configurations or Launch Templates(newer)
 - To update an ASG, you must provide a new launch configuration / launch template
 - IAM roles are attached to an ASG will get assigned to EC2 instances
 - **ASG are free**. You pay for the underlying resources being launched.
 - Having instances under an ASG means that if they get terminated for whatever reason, the ASG will automatically **create new ones as a replacement**. Extra safety!
 - ASG can terminate instances marked as unhealthy by a LB (and hence replace them)

## 4.12 Auto Scaling Group - Scaling Policies
**Q=1 What are ASG - Scaling Policies?**
 - **Target Tracking Scaling**
    - Most simple and easy to set-up
    - Example: I want the average ASG CPU to stay at around 40% 
 - **Simple/Step Scaling**
    - When a CloudWatch alarm is triggered (example CPU > 70%), then add 2 units
    - When a CloudWatch alarm is triggered (example CPU < 30%), then remove 1 unit
 - **Scheduled Actions**
    - Anticipate a scaling based on known usage patterns
    - Example: increase the min capacity to 10 at 5 pm on Fridays

**Q=2 What are ASG - Scaling Cooldowns?**
 - **The cooldown period helps to ensure that your ASG does not launch or terminate additional instances before the previous scaling activity takes effect**
 - In addition to default cooldown for ASG, we can create cooldowns that apply to a specific **simple scale policy**
 - A scaling-specific cooldown period overrides the **default** cooldown period.
 - One common use for scaling-specific cooldowns is with a **scale-in** policy - a policy that terminates instances based on a specific criteria or metric. Because this policy terminates instances, Amazon EC2 Auto Scaling needs less time to determine whether to terminate additional instances.
 - **if the default cooldown period of 300 seconds is too long - you can reduce costs by applying a scaling-specific cooldown period of 180 seconds to the scale-in policy.**
 - If you application is scaling up and down multiple times each hour, modify the ASG cool-down timers and the CloudWatch Alarm Period that triggers the scale in.

 ## 4.13 ASG for Solutions Architect
 **Q=1 What points are important in terms of ASG's**
  - ASG Default Termination Policy (simplified version):
    - Find the AZ which has the most number of instances
    - If there are multiple instances in the AZ to choose from, delete the one with the oldest launch configuration
  - **ASG tries the balance the number of instances across AZ by default**

**Q=2 What is the Lifecycle Hooks for ASG**
 - By default as soon as an instance is launched in an ASG it's in service.
 - You have the ability to perform extra steps before the instance goes in service (Pending state).
 - You have the ability to perform extra actions before the instance is terminated (Terminating state).

**Q= Difference between Launch Template and Launch Configuration**
 - Both
   - ID of the Amazon Machine Image (AMI), the instance type, a key pair, security groups, and the other parameters that you use to launch EC2 instances (tags, EC2 user-data...)
 - Launch Configuration(Legacy)
   - Must be re-created every time 
 - Launch Template(newer)
   - Can have multiple versions
   - Create parameters subsets (partial configuration for re-use and inheritance)
   - Provision using both On-Demand and Spot instances (or a mix)
   - Can use T2 unlimited burst feature
   - Recommend by AWS going forward

# Section 5 EC2 Storage - EBS and EFS
## 5.1 EBS Intro
**Q=1 What is an EBS Volume**
 - An EC2 machine loses its root volume(main drive) when it is manually terminated.
 - Unexpected terminations might happen from time to time (AWS would email you)
 - Sometimes, you need a way to store your instance data somewhere
 - An EBS (Elastic Block Store) Volume is a **network** drive you can attach to your instances while they run 
 - It allows your instances to persist data
 - It's a network drive (i.e. not a physical drive)
   - It uses the network to communicate the instance, which means there might be a bit of latency.
   - **It can be detached from an EC2 instance and attached to another one quickly.**
 - It's locked to an Availability Zone(AZ)
   - **An EBS Volume in us-east-1a cannot be attached to us-east-1b.**
   - **To move a volume across, you first need to snapshot it.**
 - Have a provisioned capacity (size in GBs, and IOPS)
   - **you get billed for all the provisioned capacity**
   - **You can increase the capacity of the drive over time.**

**Q=2 What are types of EBS volumes**
 - EBS Volumes comes in 4 types:
   - **GP2(SSD)**: General Purpose SSD volume that balances price and performance for a wide variety of workloads
   - **IO1(SSD)**: Highest performance SSD volume for mission-critical low-latency or high throughput workloads
   - **ST1(HDD)**: Low cost HDD volume designed for frequently accessed, throughput intensive workloads
   - **SC1(HDD)**: Lowest cost HDD volume designed for less frequently accessed workloads
 - EBS volumes are characterized in Size | Throughput | IOPS (I/O Ops Per Sec)
 - When in doubt alway consult the AWS documentation - it's good 
 - **Only GP2 and IO1 can be used as boot volumes** 

## 5.3 EBS Volume Types Deep Dive
**Q=1 EBS Volume Types Use cases - GP2 - General Purpose Volumes(cheap)** 
 - It is recommended for most workloads
 - System boot volumes
 - Virtual desktops
 - Low-latency interactive apps
 - Development and test environments
 - **1 GiB - 16 TiB** 
 - Small gp2 volumes can **burst IOPS to 3000**
 - **Min 100 IOPS and Max IOPS is 16,000...**
 - 3 IOPS per GB, means at 5,334GB we are at the max IOPS

**Q=2 EBS Volume Types Use cases - IO1 - Provisioned IOPS (expensive)**
 - Critical business applications that require sustained IOPS performance, or more than 16,000 IOPS per volume (gp2 limit)
 - large database workloads such as:
   - MongoDB, Cassandra, Microsoft SQL Server, MySQL, PostgreSQL, Oracle
 - **4GiB - 16 TiB** 
 - **IOPS is provisioned - MIN 100 - MAX 64,000 (Nitro instances) else MAX 32,000 (other instances)**
 - The maximum ratio of provisioned IOPS to requested volume size (in GiB) is **50:1** 
 - **Size of volume and IOPS are independent**

**Q=3 EBS Volume Types Use cases - ST1 - Throughput Optimized HDD**
 - Streaming workloads requiring consistent, fast throughput at a low price.
 - Big Data, Data Warhouses, Log Processing
 - Apache kafka
 - Cannot be a boot volume 
 - **500 GiB - 16 TiB**
 - Max throughput of **500 MiB/s** - can burst

**Q=4 EBS Volume Types Use cases - SC1 - Cold HDD, Infrequently accessed data**
 - Throughput oriented storage for large volumes of data that is infrequently accessed
 - Scenarios where the lowest storage cost is important 
 - Cannot be a boot volume 
 - **500 GiB - 16 TiB**
 - Max throughput is **250 MiB/s** - can burst 

## 5.4 EBS Operations: Snapshots
**Q=1 What are EBS snapshots?**
 - Incremental - only backup changed blocks
 - EBS backups use IO and you shouldn't run them while your application is handling a lot of traffic.
 - Snapshots will be stored in S3 (but you won't directly see them)
 - Not necessary to detach volume to do snapshot, but recommended
 - Max 100,000 snapshots 
 - Can copy snapshots across AZ or Region
 - Can make Image(AMI) from snapshot
 - **EBS volumes restored by snapshots need to be pre-warmed (using fio or add command to read the entire volume)**
 - **Snapshots can be automated using Amazon Data Lifecycle Manager**

## 5.5 EBS Operations: Migrations
**Q=1 What is an EBS Migration**
 - EBS volumes are only locked to a specific AZ
 - To migrate it to a different AZ (or region):
   - Snapshot the volume 
   - (Optional) Copy the volume to a different region
   - **Create a volume from the snapshot in the AZ of your choice**

## 5.6 EBS Operations: Volume Encryption
**Q=1 What is an EBS Encryption?**
 - When you create an encrypted EBS volume, you get the following:
   - Data at rest is encrypted inside the volume
   - All the data in flight moving between the instance and the volume is encrypted.
   - All snapshots are encrypted
   - All volumes created from the snapshot.
 - Encryption and decryption are handled transparently (you have nothing to do)
 - Encryption has a minimal impact on latency
 - EBS Encryption leverages keys from KMS (AES-256)
 - **Copying an unencrypted snapshot allows encryption**.
 - **Snapshots of encrypted volumes are encrypted**

**Q=2 How do you encrypt an unencrypted EBS volumes?**
 - Create an EBS snapshot of the volume
 - Encrypt the EBS snapshot (using copy)
 - Create new ebs volume from the snapshot (the volume will also be encrypted)
 - Now you can attach the encrypted volume to the original instance

## 5.7 EBS vs Instance Store 
**Q=1 What is mean by EBS vs Instance Store?**
 - Some instance do not come with Root EBS volumes.
 - Instead, they come up with "Instance Store"(= ephemeral storage)
 - Instance store is physically attached to the machine (EBS is a network drive)
 - Pros:
   - Better I/O performance
   - Good for buffer/ cache / scratch data / temporary content
   - Data survives reboots
 - Cons: 
   - On stop or termination, the instance store is lost 
   - You can't resize the instance store 
   - Backups must be operated by the user

**Q=2 What is Local EC2 Instance Store**
 - **Physical disk attached to the physical server where your EC2 is**
 - Very high IOPS (because physical)
 - Disks up to 7.5TiB (can change over time), stripped to reach 30 TiB (can change over time...)
 - Block Storage (just like EBS)
 - Cannot be increased in size 
 - Risk of data loss if hardware fails

 ## 5.8 EBS RAID Configuration
 **Q=1 What are an EBS RAID Options?**
  - EBS is already reduntant storage(replicated within an AZ)
  - But what if you want to increase IOPS to say 100 000 IOPS?
  - What if you want to mirror your EBS volumes?
  - You would mount volumes in parallel in RAID settings!
  - Some RAID options are: 
    - RAID 0 
    - RAID 1
    - RAID 5 (not recommended for EBS)
    - RAID 6 (not recommended for EBS)
  - We will explore RAID 0 and RAID 1 

**Q=2 What is RAID 0 (increase performance)**
 - Combining 2 or more volumes and getting the total disk space and I/O
 - But one disk fails, all the data is failed.
 - Use cases would be: 
   - An application that needs a lot of IOPS and doesn't need fault-tolerance.
   - A database that has replication already built-in
 - **Using this, we can have a very big disk with a lot of IOPS**
 
 **Q=3 What is RAID 1 (increase fault tolerance)**
  - RAID 1 = Mirroring a volume to another
  - If one disk fails, our logical volume is still working
  - We have to send the data to two EBS volumes at the same time (2x network)
  - Use case: 
    - Application that need increase volume fault tolerance 
    - Application where you need to service disks

## 5.9 EFS Overview
**Q=1 What is Elastic File System**
 - Managed NFS (network file system) that can be mounted on many EC2.
 - EFS works with EC2 instances in multi-AZ
 - Highly available, scalable, expensive (3x gp2), pay per use

**Q=2 What are EFS use cases?**
 - Use cases: content management, web serving, data sharing, wordpress
 - Uses NFSv4.1 protocol
 - Uses Security group to control access to EFS
 - **Compatible with Linux based AMI (not Windows)**
 - Encryption at rest using KMS
 - POSIX file system(~Linux) that has a standard file API
 - File system scales automatically, pay-per-use, no capacity planning 

**Q=3 What are EFS- Performance and Storage Classes**
 - **EFS Scale**
    - 1000s of current NFS clients, 10 GB+ /s throughput
    - Grow to Petabyte-scale network file system, automatically
 - **Performance mode (set at EFS creation time)**
    - General purpose (default): latency-sensitive use cases (web server, CMS, etc...)
    - Max I/O - higher latency, throughput, highly parallel (big data, media processing)
 - **Storage Tiers (lifecycle management feature - move file after N days)**
    - Standard: for frequently accessed files
    - Infrequent access (EFS-IA): cost to retrieve files, lower price to store.

## 5.12 EBS vc EFS - Elastic Block Storage
**Q=1 What is difference between EBS vs EFS**
 - EBS volumes
   - can be attached to only one instance at a time
   - are locked at the Availability Zone (AZ) level
   - gp2: IO increases if the disk size increases
   - io1: can increase IO independently
 - To migrate an EBS volume across AZ
   - Take a snapshot
   - Restore the snapshot to another AZ
   - EBS backups use IO and you shouldn't run them while your application is handling a lot of traffic
 - Root EBS Volumes of instances get terminated by default if the EC2 instance gets terminated(you can disable that).

 - EFS volumes
   - Mounting 100s of instances across AZ
   - EFS share website files (WordPress)
   - only for Linux Instances (POSIX)
   - EFS has a higher price point than EBS
   - Can leverage EFS-IA for cost savings


