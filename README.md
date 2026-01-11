# Cloud Computing Lab 1

**Course:** Cloud Computing  
**Lab Title:** Introduction to Cloud Computing and Platform Setup  
**Student:** Arshia Jadoon  
**Registration:** BSE-2023-014  
**Semester:** VA

## Overview

This introductory lab provides hands-on experience with cloud computing fundamentals and platform setup. Students explore cloud service models, deployment models, and set up their development environment for cloud-based application development and deployment.

## Table of Contents

1. [Introduction to Cloud Computing](#introduction-to-cloud-computing)
2. [Lab Environment Setup](#lab-environment-setup)
3. [Cloud Platform Exploration](#cloud-platform-exploration)
4. [Basic Cloud Operations](#basic-cloud-operations)
5. [Key Takeaways](#key-takeaways)

---

## Introduction to Cloud Computing

### What is Cloud Computing?

Cloud computing is the delivery of computing services—including servers, storage, databases, networking, software, analytics, and intelligence—over the Internet ("the cloud") to offer faster innovation, flexible resources, and economies of scale.

### Key Characteristics

**On-Demand Self-Service:**
- Users can provision computing resources automatically
- No human interaction with service provider needed
- Available 24/7 through web interfaces or APIs

**Broad Network Access:**
- Available over the network
- Accessible through standard mechanisms
- Works on phones, tablets, laptops, workstations

**Resource Pooling:**
- Multi-tenant model
- Resources dynamically assigned based on demand
- Location independence (with some geographic control)

**Rapid Elasticity:**
- Scale up or down quickly
- Automatic scaling based on demand
- Appears unlimited to consumers

**Measured Service:**
- Pay-per-use or subscription model
- Resource usage monitored and controlled
- Transparent pricing and reporting

---

## Cloud Service Models

### 1. Infrastructure as a Service (IaaS)

**Description:** Provides virtualized computing resources over the internet

**Components:**
- Virtual machines
- Storage
- Networks
- Operating systems

**Examples:**
- Amazon EC2 (Elastic Compute Cloud)
- Microsoft Azure Virtual Machines
- Google Compute Engine
- DigitalOcean Droplets

**Use Cases:**
- Website hosting
- Development and testing environments
- Data storage and backup
- High-performance computing

**Advantages:**
✅ Complete control over infrastructure  
✅ Highly scalable  
✅ Pay only for what you use  
✅ No hardware maintenance  

**Responsibilities:**
- User manages: Applications, data, runtime, middleware, OS
- Provider manages: Virtualization, servers, storage, networking

---

### 2. Platform as a Service (PaaS)

**Description:** Provides platform allowing customers to develop, run, and manage applications

**Components:**
- Development tools
- Database management
- Business analytics
- Operating systems
- Runtime environments

**Examples:**
- AWS Elastic Beanstalk
- Google App Engine
- Microsoft Azure App Service
- Heroku
- Railway

**Use Cases:**
- Web application development
- API development and management
- Microservices architecture
- Business process management

**Advantages:**
✅ Focus on application development  
✅ Faster time to market  
✅ Built-in scalability  
✅ Reduced complexity  

**Responsibilities:**
- User manages: Applications, data
- Provider manages: Runtime, middleware, OS, virtualization, servers, storage, networking

---

### 3. Software as a Service (SaaS)

**Description:** Software delivered over the internet on a subscription basis

**Components:**
- Complete applications
- Web-based interfaces
- Automatic updates
- Data storage

**Examples:**
- Google Workspace (Gmail, Docs, Drive)
- Microsoft 365
- Salesforce
- Dropbox
- Slack
- Zoom

**Use Cases:**
- Email and collaboration
- Customer relationship management (CRM)
- Enterprise resource planning (ERP)
- Project management
- Communication tools

**Advantages:**
✅ No installation or maintenance  
✅ Accessible from anywhere  
✅ Automatic updates  
✅ Lower upfront costs  

**Responsibilities:**
- User manages: Data and access policies
- Provider manages: Everything else (applications, runtime, middleware, OS, infrastructure)

---

## Cloud Deployment Models

### 1. Public Cloud

**Description:** Services offered over the public internet and available to anyone

**Characteristics:**
- Owned and operated by third-party providers
- Shared infrastructure across multiple tenants
- Accessible via internet
- Pay-as-you-go pricing

**Providers:**
- Amazon Web Services (AWS)
- Microsoft Azure
- Google Cloud Platform (GCP)
- IBM Cloud
- Oracle Cloud

**Advantages:**
✅ No capital expenditure  
✅ High scalability  
✅ Reduced maintenance  
✅ Global reach  

**Disadvantages:**
❌ Less control over infrastructure  
❌ Potential security concerns for sensitive data  
❌ Internet dependency  

---

### 2. Private Cloud

**Description:** Cloud infrastructure used exclusively by a single organization

**Characteristics:**
- Dedicated resources
- Hosted on-premises or by third party
- Greater control and customization
- Enhanced security

**Use Cases:**
- Government agencies
- Financial institutions
- Healthcare organizations
- Companies with strict compliance requirements

**Advantages:**
✅ Complete control  
✅ Enhanced security  
✅ Customizable  
✅ Regulatory compliance  

**Disadvantages:**
❌ Higher costs  
❌ Requires IT expertise  
❌ Limited scalability compared to public  

---

### 3. Hybrid Cloud

**Description:** Combination of public and private clouds

**Characteristics:**
- Data and applications shared between clouds
- Flexibility to choose optimal environment
- Orchestration between platforms
- Best of both worlds

**Use Cases:**
- Bursting workloads to public cloud
- Sensitive data in private, non-sensitive in public
- Disaster recovery
- Development/testing in public, production in private

**Advantages:**
✅ Flexibility  
✅ Cost optimization  
✅ Scalability when needed  
✅ Security for sensitive data  

**Disadvantages:**
❌ Complex management  
❌ Integration challenges  
❌ Potential security vulnerabilities at connection points  

---

### 4. Community Cloud

**Description:** Infrastructure shared by several organizations with common concerns

**Characteristics:**
- Shared by specific community
- Common security, compliance, or policy requirements
- Managed internally or by third party
- Cost shared among members

**Examples:**
- Healthcare community clouds (HIPAA compliance)
- Government community clouds (FedRAMP)
- Financial services clouds
- Research community clouds

**Advantages:**
✅ Shared costs  
✅ Common compliance needs  
✅ Collaborative capabilities  
✅ Community-specific features  

---

## Lab Environment Setup

### Prerequisites

**Hardware Requirements:**
- Computer with minimum 4GB RAM (8GB recommended)
- 20GB free disk space
- Stable internet connection
- Modern web browser

**Software Requirements:**
- Operating System: Windows 10/11, macOS, or Linux
- Web browser: Chrome, Firefox, or Edge (latest version)
- Terminal/Command Prompt access
- (Optional) SSH client

**Accounts Needed:**
- AWS Account (free tier)
- GitHub Account (for version control)
- Email account for notifications

---

## Cloud Platform Exploration

### Understanding Cloud Consoles

**AWS Management Console:**
- Web-based interface for AWS services
- Dashboard for resource management
- Service catalog and navigation
- Billing and cost management
- IAM for access control

**Key Sections:**
1. **Services Menu:** Access to all AWS services
2. **Resource Groups:** Organize and manage resources
3. **CloudShell:** Browser-based shell
4. **Account Settings:** User preferences and billing
5. **Support Center:** Documentation and help

### Common Cloud Services Overview

**Compute Services:**
- EC2 (Virtual Servers)
- Lambda (Serverless Functions)
- ECS/EKS (Container Services)
- Lightsail (Simplified VPS)

**Storage Services:**
- S3 (Object Storage)
- EBS (Block Storage)
- EFS (File Storage)
- Glacier (Archive Storage)

**Database Services:**
- RDS (Relational Databases)
- DynamoDB (NoSQL)
- ElastiCache (Caching)
- Aurora (High-performance DB)

**Networking Services:**
- VPC (Virtual Private Cloud)
- Route 53 (DNS)
- CloudFront (CDN)
- Direct Connect (Dedicated Network)

---

## Basic Cloud Operations

### 1. Account Creation and Setup

**Steps:**
1. Navigate to cloud provider website
2. Click "Create Account" or "Sign Up"
3. Provide email and create password
4. Enter payment information (for verification)
5. Complete identity verification
6. Select support plan (Basic/Free)
7. Access management console

**Security Best Practices:**
✅ Use strong, unique password  
✅ Enable Multi-Factor Authentication (MFA)  
✅ Don't share root/admin credentials  
✅ Create IAM users for daily operations  
✅ Set up billing alerts  

---

### 2. Console Navigation

**Learning the Interface:**
- Service search and favorites
- Recent services accessed
- Resource creation workflows
- Documentation integration
- Cost and usage dashboards

**Common Tasks:**
- Launching resources
- Configuring settings
- Monitoring performance
- Managing costs
- Setting up alerts

---

### 3. Understanding Regions and Availability Zones

**Regions:**
- Geographic locations with data centers
- Independent from each other
- Compliance and latency considerations
- Some services are region-specific

**Popular Regions:**
- us-east-1 (N. Virginia)
- eu-west-1 (Ireland)
- ap-southeast-1 (Singapore)
- me-central-1 (UAE)

**Availability Zones:**
- Multiple isolated locations within a region
- Physically separate data centers
- Connected with low-latency networks
- Fault isolation and high availability

---

### 4. Free Tier Understanding

**AWS Free Tier Types:**

**Always Free:**
- Services that remain free beyond 12 months
- Example: Lambda (1M requests/month)
- Example: DynamoDB (25GB storage)

**12 Months Free:**
- Free for first 12 months after signup
- Example: EC2 t2.micro (750 hours/month)
- Example: S3 (5GB standard storage)
- Example: RDS (750 hours/month)

**Trial Periods:**
- Short-term free trials for specific services
- Example: SageMaker (2 months)
- Example: Inspector (90 days)

**Monitoring Free Tier:**
- Set up billing alerts
- Check Free Tier usage dashboard
- Enable detailed billing reports
- Monitor service usage regularly

---

## Cloud Computing Benefits

### Technical Benefits

**Scalability:**
- Vertical scaling (more powerful resources)
- Horizontal scaling (more instances)
- Automatic scaling based on demand
- Handle traffic spikes effortlessly

**Reliability:**
- Multiple data centers and regions
- Automatic failover
- Backup and disaster recovery
- Service Level Agreements (SLAs)

**Performance:**
- Global network of data centers
- Content Delivery Networks (CDN)
- Low-latency access
- High-speed connections

**Security:**
- Professional security teams
- Compliance certifications
- Encryption at rest and in transit
- Regular security updates

---

### Business Benefits

**Cost Savings:**
- No upfront hardware costs
- Pay only for what you use
- Reduce operational expenses
- Predictable monthly costs

**Speed and Agility:**
- Rapid resource provisioning
- Faster time to market
- Quick experimentation
- Easy scaling

**Global Reach:**
- Deploy in multiple regions instantly
- Serve global customers
- Reduce latency worldwide
- Comply with regional regulations

**Focus on Business:**
- No infrastructure management
- Reduced IT staff needs
- Focus on core business
- Innovation over maintenance

---

## Key Concepts and Terminology

### Essential Cloud Terms

**Virtualization:**
- Running multiple virtual systems on single physical hardware
- Foundation of cloud computing
- Efficient resource utilization

**Instance:**
- Virtual server in the cloud
- Can be started, stopped, terminated
- Various sizes and configurations

**Snapshot:**
- Point-in-time copy of data
- Used for backups
- Quick recovery option

**Load Balancer:**
- Distributes traffic across multiple instances
- Improves availability
- Handles health checks

**Auto Scaling:**
- Automatically adjusts resource capacity
- Based on defined metrics
- Maintains performance and minimizes costs

**VPC (Virtual Private Cloud):**
- Isolated virtual network
- Control over IP addresses
- Security and routing configuration

**IAM (Identity and Access Management):**
- User and permission management
- Role-based access control
- Principle of least privilege

**API (Application Programming Interface):**
- Programmatic access to services
- Automation and scripting
- Integration with tools

---

## Cloud Security Fundamentals

### Shared Responsibility Model

**Cloud Provider Responsibilities:**
- Physical infrastructure security
- Hardware maintenance
- Network infrastructure
- Virtualization platform
- Managed service operations

**Customer Responsibilities:**
- Data encryption
- Access management (IAM)
- Network configuration
- Application security
- Compliance adherence

### Security Best Practices

**Identity and Access:**
✅ Enable MFA on all accounts  
✅ Use IAM roles instead of access keys  
✅ Follow principle of least privilege  
✅ Regularly rotate credentials  
✅ Monitor access logs  

**Network Security:**
✅ Use security groups as virtual firewalls  
✅ Implement network ACLs  
✅ Use VPCs for isolation  
✅ Enable VPC flow logs  
✅ Use VPN or Direct Connect for sensitive data  

**Data Protection:**
✅ Encrypt data at rest  
✅ Encrypt data in transit (SSL/TLS)  
✅ Regular backups  
✅ Implement versioning  
✅ Use secure key management  

---

## Cost Management

### Understanding Cloud Pricing

**Pricing Models:**
- **On-Demand:** Pay per hour/second
- **Reserved:** Commit for 1-3 years (discounts)
- **Spot:** Bid on spare capacity (up to 90% savings)
- **Savings Plans:** Flexible pricing for committed usage

**Cost Optimization Strategies:**
✅ Right-size instances  
✅ Use auto-scaling  
✅ Delete unused resources  
✅ Use reserved instances for steady workloads  
✅ Leverage spot instances for flexible workloads  
✅ Set up cost allocation tags  
✅ Use cost explorer and budgets  

### Billing Alerts

**Setting Up Alerts:**
1. Navigate to Billing Dashboard
2. Enable billing alerts
3. Create CloudWatch alarm
4. Set threshold (e.g., $10)
5. Add email notification
6. Save configuration

---

## Lab Activities Summary

### Activities Completed

Based on the screenshots provided, this lab covered:

1. ✅ **Cloud Platform Introduction**
   - Understanding cloud computing concepts
   - Exploring service and deployment models

2. ✅ **Account Setup**
   - Creating cloud provider account
   - Configuring initial settings

3. ✅ **Console Navigation**
   - Familiarizing with management console
   - Exploring service dashboard

4. ✅ **Basic Configuration**
   - Understanding regions and zones
   - Exploring available services

5. ✅ **Security Awareness**
   - Learning about IAM
   - Understanding security best practices

6. ✅ **Cost Management**
   - Reviewing free tier offerings
   - Setting up billing alerts

---

## Learning Outcomes

After completing this lab, students should be able to:

✅ Define cloud computing and its characteristics  
✅ Differentiate between IaaS, PaaS, and SaaS  
✅ Explain public, private, hybrid, and community clouds  
✅ Navigate cloud management consoles  
✅ Understand regions and availability zones  
✅ Set up and secure cloud accounts  
✅ Recognize cloud security responsibilities  
✅ Monitor costs and free tier usage  
✅ Identify common cloud services  
✅ Apply basic cloud security practices  

---

## Common Use Cases

### Development and Testing
- Quickly spin up environments
- Test different configurations
- Parallel testing
- Destroy when done

### Web Application Hosting
- Scalable web servers
- Content delivery
- Database services
- Load balancing

### Data Storage and Backup
- Object storage for files
- Automated backups
- Disaster recovery
- Archive storage

### Big Data and Analytics
- Process large datasets
- Machine learning
- Business intelligence
- Real-time analytics

### Mobile Backend
- APIs for mobile apps
- Push notifications
- User authentication
- Data synchronization

---

## Comparison: Traditional vs Cloud

| Aspect | Traditional IT | Cloud Computing |
|--------|---------------|-----------------|
| **Capital Cost** | High upfront | Pay-as-you-go |
| **Scalability** | Limited, slow | Unlimited, instant |
| **Maintenance** | Your responsibility | Provider handles it |
| **Setup Time** | Weeks/months | Minutes/hours |
| **Global Reach** | Complex, expensive | Built-in capability |
| **Disaster Recovery** | Costly to implement | Easier, more affordable |
| **Innovation Speed** | Slower | Faster |
| **Resource Utilization** | Often underutilized | Optimized usage |

---

## Next Steps

### Continue Learning

**Upcoming Labs:**
- Lab 2-7: Linux administration and scripting
- Lab 8: AWS infrastructure deployment
- Lab 11: Infrastructure as Code with Terraform
- Advanced cloud architectures

**Skills to Develop:**
- Command line proficiency
- Scripting (Bash, Python)
- Networking fundamentals
- Security best practices
- Cost optimization

**Certifications to Consider:**
- AWS Certified Cloud Practitioner
- AWS Certified Solutions Architect - Associate
- Microsoft Azure Fundamentals
- Google Cloud Associate Cloud Engineer

---

## Additional Resources

### Official Documentation
- [AWS Documentation](https://docs.aws.amazon.com/)
- [AWS Free Tier](https://aws.amazon.com/free/)
- [AWS Getting Started](https://aws.amazon.com/getting-started/)

### Learning Platforms
- [AWS Skill Builder](https://skillbuilder.aws/)
- [AWS Training](https://aws.amazon.com/training/)
- [A Cloud Guru](https://acloudguru.com/)
- [Coursera Cloud Courses](https://www.coursera.org/)

### Community Resources
- [AWS Forums](https://forums.aws.amazon.com/)
- [Stack Overflow - AWS](https://stackoverflow.com/questions/tagged/amazon-web-services)
- [Reddit r/aws](https://www.reddit.com/r/aws/)

### Tools and Utilities
- [AWS CLI](https://aws.amazon.com/cli/) - Command line interface
- [AWS CloudShell](https://aws.amazon.com/cloudshell/) - Browser-based shell
- [AWS Mobile App](https://aws.amazon.com/console/mobile/) - Manage on the go

---

## Glossary

**AMI (Amazon Machine Image):** Pre-configured template for instances  
**API Gateway:** Managed service for creating and managing APIs  
**Availability Zone:** Isolated location within a region  
**CIDR:** Classless Inter-Domain Routing (IP addressing)  
**CloudFormation:** Infrastructure as Code service  
**CloudWatch:** Monitoring and observability service  
**EC2:** Elastic Compute Cloud (virtual servers)  
**EBS:** Elastic Block Store (persistent storage)  
**ELB:** Elastic Load Balancing  
**IAM:** Identity and Access Management  
**IGW:** Internet Gateway  
**Lambda:** Serverless compute service  
**NAT Gateway:** Network Address Translation for private subnets  
**RDS:** Relational Database Service  
**Region:** Geographic area with multiple availability zones  
**S3:** Simple Storage Service (object storage)  
**Security Group:** Virtual firewall for instances  
**Subnet:** Range of IP addresses in VPC  
**VPC:** Virtual Private Cloud (isolated network)  

---

## Author

**Arshia Jadoon**  
BSE-2023-014  
Semester VA

---

## Acknowledgments

- AWS Free Tier Program
- Cloud Computing Course Instructors
- Open Source Community
- Documentation Contributors

---

*This lab manual is part of the Cloud Computing course curriculum introducing fundamental cloud concepts and hands-on platform experience.*

## 📚 Study Tips

**For Exams:**
- Understand service models (IaaS, PaaS, SaaS)
- Know deployment models and use cases
- Memorize key cloud characteristics
- Practice console navigation
- Review security best practices
- Understand pricing models

**For Practical Work:**
- Always check free tier limits
- Set up billing alerts immediately
- Clean up resources after practice
- Document your configurations
- Use tags for resource organization
- Practice in sandbox environments first

**Remember:** Cloud computing is best learned by doing. Don't just read—practice!
