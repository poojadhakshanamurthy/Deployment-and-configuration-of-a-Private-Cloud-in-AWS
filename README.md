# Deployment-and-configuration-of-a-Private-Cloud-in-AWS
Ex.4 Deployment and configuration of a Private Cloud  in AWS

### Aim:
To set up of a Private Cloud  in AWS.
         Setting up of a private cloud in AWS:
Setting up a private cloud within AWS, also known as a Virtual Private Cloud (VPC),
involves creating a logically isolated virtual network that you can use to launch AWS
resources. This provides you with full control over your virtual networking environment,
including resource placement, connectivity, and security.
Amazon Virtual Private Cloud (Amazon VPC) gives you full control over your virtual
networking environment, including resource placement, connectivity, and security. Get
started by setting up your VPC in the AWS service console. Next, add resources to it such as
Amazon Elastic Compute Cloud (EC2) and Amazon Relational Database Service (RDS)
instances. Finally, define how your VPCs communicate with each other across accounts,
Availability Zones, or AWS Regions.
### Procedure:
1. Plan Your VPC:
● Determine your needs:
Define your use case, including application requirements, security needs, and
compliance standards.
● Plan IP address ranges:
Choose appropriate IP address ranges for your VPC and subnets to avoid conflicts.
● Select Availability Zones:
Decide which Availability Zones (AZs) you'll use for your resources, considering
redundancy and performance.
● Plan internet connectivity:
Determine if you need public internet access and how to configure it.
● Define security:
Plan your security groups, network ACLs, and access controls to ensure a secure
environment.
2. Create Your VPC:
•	Sign in to AWS Management Console: Access the VPC console and navigate to the VPC dashboard.
•	 Choose "Create VPC": Initiate the VPC creation process.
•	Configure VPC details: Enter the VPC name, CIDR block, Availability Zones, and
•	other necessary settings.
•	Create subnets: Define subnets within your VPC to isolate different parts of your
•	network.
•	Create route tables: Specify how traffic is routed within and outside the VPC.
•	 Create security groups: Define access control rules for your resources.
3. Deploying Resources:
•	Launch EC2 instances: Create and launch virtual machines within your VPC.
•	 Set up RDS instances: Deploy databases for your applications.
•	Configure networking: Connect your resources to the appropriate subnets, security
groups, and route tables.
•	Deploy other AWS services: Integrate other services like S3 for storage and Lambda for serverless computing.
4.Managing and Monitoring:
•	Use AWS CloudWatch: Monitor your VPC and resources for performance and
health.
•	Configure logging and auditing: Track access and activity within your VPC for
security and compliance.
•	Implement security best practices: Regularly review and update your security
configuration.
•	Scale and adjust as needed: Adjust your VPC infrastructure to meet changing
demands.

Snap Shot:

Snapshot 1: Create VPC
<img width="1920" height="1080" alt="Screenshot 2026-11-02 102859" src="https://github.com/user-attachments/assets/afbedaa0-9e2d-479e-a371-0bfd7d973ca4" />
<img width="1920" height="1080" alt="Screenshot 2026-11-02 102909" src="https://github.com/user-attachments/assets/4483bc81-661d-42ab-b3ee-954376a14c46" />
<img width="1920" height="1080" alt="Screenshot 2026-11-02 103256" src="https://github.com/user-attachments/assets/6af599e2-05b7-4445-a644-022d7bea4f28" />

Snapshot 2: Configuring Subnets
<img width="1920" height="1080" alt="Screenshot 2026-11-02 104029" src="https://github.com/user-attachments/assets/9d913678-038b-414a-a634-ae9b943988b0" />
<img width="1920" height="1080" alt="Screenshot 2026-11-02 104205" src="https://github.com/user-attachments/assets/a1ab1379-0594-49ff-824f-71fcfb67abfa" />
<img width="1920" height="1080" alt="Screenshot 2026-11-02 104259" src="https://github.com/user-attachments/assets/d138a37f-d975-4053-bd94-e4ae6769626a" />

 Snapshot 3: Configure Subnets
 <img width="1920" height="1080" alt="Screenshot 2026-11-02 104409" src="https://github.com/user-attachments/assets/b2d771bf-d288-41db-ac0c-036bd9b4eb21" />
<img width="1920" height="1080" alt="Screenshot 2026-11-02 104420" src="https://github.com/user-attachments/assets/db03dc32-0e77-4a7c-98a3-63d04792587e" />
<img width="1920" height="1080" alt="Screenshot 2026-11-02 104435" src="https://github.com/user-attachments/assets/bab361dd-aeeb-4966-8ee5-127f1222c2be" />


Snapshot 4: Setting Internet gateway
<img width="1920" height="1080" alt="Screenshot 2026-11-02 104857" src="https://github.com/user-attachments/assets/37219262-6e87-4a88-97da-46df1f48b520" />

<img width="1920" height="1080" alt="Screenshot 2026-11-02 104934" src="https://github.com/user-attachments/assets/9fd1d4eb-37c8-4847-89a0-62bd037fee9b" />

<img width="1920" height="1080" alt="Screenshot 2026-11-02 105442" src="https://github.com/user-attachments/assets/a00d5170-db5c-4e6c-8a31-031babf32454" />
 
Snapshot 5: Setting Internet gateway

<img width="1920" height="1080" alt="Screenshot 2026-11-02 110134" src="https://github.com/user-attachments/assets/87da970a-5fe3-488b-94a3-1189b70918dd" />


<img width="1920" height="1080" alt="Screenshot 2026-11-02 110335" src="https://github.com/user-attachments/assets/e2d74b5d-a291-43a5-a663-c01001095345" />
 
<img width="1920" height="1080" alt="Screenshot 2026-11-02 110419" src="https://github.com/user-attachments/assets/35b8ec3d-f54d-484d-8f29-385b64f17ae5" />

Snapshot 6: Setting Internet gateway
<img width="1920" height="1080" alt="Screenshot 2026-11-02 110450" src="https://github.com/user-attachments/assets/fe82e33a-03f8-410c-9e86-16386f261707" />

<img width="1920" height="1080" alt="Screenshot 2026-11-02 110508" src="https://github.com/user-attachments/assets/33c48401-c5ad-4832-a03a-1932b204c2b8" />

<img width="1920" height="1080" alt="Screenshot 2026-11-02 110930" src="https://github.com/user-attachments/assets/e64d8502-45ca-4fe9-843f-f3867210ea64" />
 
Snapshot 7: Creating route table

<img width="1920" height="1080" alt="Screenshot 2026-11-02 110939" src="https://github.com/user-attachments/assets/299cacae-ae92-4cce-84a7-770677ba0a10" />

<img width="1920" height="1080" alt="Screenshot 2026-11-02 103303" src="https://github.com/user-attachments/assets/2cf5ec29-b12c-404d-b2a4-e07f9f05020b" />

<img width="1920" height="1080" alt="Screenshot 2026-11-02 104029" src="https://github.com/user-attachments/assets/f026c4c9-845b-4aeb-96fa-7cb9f665b95a" />

Snapshot 8: Configuring route table
<img width="1920" height="1080" alt="Screenshot 2026-11-02 104708" src="https://github.com/user-attachments/assets/43dd6c5f-9769-4bac-9fc9-14244cc72c74" />

<img width="1920" height="1080" alt="Screenshot 2026-11-02 104828" src="https://github.com/user-attachments/assets/6d839a91-f33d-46c2-990f-0955c7495732" />


<img width="1920" height="1080" alt="Screenshot 2026-11-02 105001" src="https://github.com/user-attachments/assets/91f225a4-67c7-4a5e-beb7-6760ad730adf" />

 
Snapshot 9: Editing routes
<img width="1920" height="1080" alt="Screenshot 2026-11-02 110147" src="https://github.com/user-attachments/assets/c74caac6-8722-4d61-bb45-95b7cd6dd91a" />


<img width="1920" height="1080" alt="Screenshot 2026-11-02 110253" src="https://github.com/user-attachments/assets/3edd82f6-bc50-4c49-857b-95b16722d703" />


<img width="1920" height="1080" alt="Screenshot 2026-11-02 110314" src="https://github.com/user-attachments/assets/24e97697-1d4e-4251-bbff-f1d63ea1fe59" />

Snapshot 10: Creating route table
<img width="1920" height="1080" alt="Screenshot 2026-11-02 110657" src="https://github.com/user-attachments/assets/8a71f868-0576-47a4-98b3-8d98f58e7693" />

<img width="1920" height="1080" alt="Screenshot 2026-11-02 110723" src="https://github.com/user-attachments/assets/f8f5807c-2296-4f63-8d92-df1a36cb163d" />

<img width="1920" height="1080" alt="Screenshot 2026-11-02 110733" src="https://github.com/user-attachments/assets/b04dffa7-19a6-4a9e-a37a-0934e2e37b88" />

Result:
Thus, a  private cloud on AWS involves using VPCs has been created for  a dedicated, isolated network where we can manage our resources and control access according to our requirements.
 
