# City-Taskers-Connect-Empowering-Local-Services-with-AWS-Scalability-and-Reliability

In this project, the aim was to develop a Local Services Marketplace Web Application, facilitating the exchange of various local services such as gardening, plumbing, and electrical repairs. The architecture of the system relies on key AWS services to ensure scalability, reliability, and efficient data management. Compute resources, specifically Amazon EC2 instances, are utilized for hosting the web application, with the incorporation of EC2 Auto Scaling to dynamically adjust instance numbers based on user traffic. For user data storage, service requests, and relational information, Amazon RDS (Relational Database Service) is employed, leveraging a suitable database engine like MySQL or PostgreSQL. The RDS deployment adopts a Multi-AZ (Availability Zone) configuration to enhance high availability and reliability. 

Amazon S3 (Simple Storage Service) is employed for file storage, managing multimedia content associated with service requests, and ensuring expandable and durable object storage. The entire infrastructure is defined and provisioned using Infrastructure as Code (IaaC), with the choice of AWS CloudFormation or AWS CDK. This approach allows for version-controlled and repeatable deployment, enabling efficient management and scaling of EC2 instances, RDS databases, S3 buckets, and other resources. Through this comprehensive architecture, the local services marketplace can seamlessly match service providers with customers, ensuring a scalable and reliable platform to meet diverse user activity levels.


## Architecture: 
![image](https://github.com/Nikam-Atharv/City-Taskers-Connect-Empowering-Local-Services-with-AWS-Scalability-and-Reliability/assets/55711642/2c49f303-5742-43e8-b4cf-7eb450bb7979)


![image](https://github.com/Nikam-Atharv/City-Taskers-Connect-Empowering-Local-Services-with-AWS-Scalability-and-Reliability/assets/55711642/63939c1c-2d21-4a84-9e55-2bf0286613e6)
