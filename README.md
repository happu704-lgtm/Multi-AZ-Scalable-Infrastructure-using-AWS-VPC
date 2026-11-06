# Multi-AZ-Scalable-Infrastructure-using-AWS-VPC

### Implementation of Multi-AZ Scalable Infrastructure using AWS VPC

**Technologies:** AWS VPC, EC2, Application Load Balancer (ALB), Auto Scaling Group (ASG), NAT Gateway, Internet Gateway (IGW), Route Tables, Security Groups, Availability Zones.

- Designed and implemented a highly available AWS infrastructure using a custom VPC with public and private subnets distributed across multiple Availability Zones.
- Configured an Internet Gateway and NAT Gateway to manage internet connectivity for public and private subnet resources.
- Deployed an Application Load Balancer across public subnets to distribute incoming application traffic across EC2 instances in private subnets.
- Configured Target Groups and health checks to route traffic only to healthy application instances.
- Implemented an EC2 Auto Scaling Group across multiple Availability Zones to maintain application availability and automatically adjust compute capacity based on demand.
- Configured public and private route tables and security groups to control network traffic and improve infrastructure security.
- Designed the architecture to support fault tolerance, horizontal scalability, and reduced exposure of application instances to the public internet.




aws-multi-az-scalable-infrastructure/
│
├── README.md
│
├── architecture/
│   └── architecture.png
│
├── documentation/
│   ├── vpc-configuration.md
│   ├── subnet-configuration.md
│   ├── routing-configuration.md
│   ├── load-balancer.md
│   └── auto-scaling.md
│
└── screenshots/
    ├── vpc.png
    ├── subnets.png
    ├── nat-gateway.png
    ├── load-balancer.png
    ├── target-group.png
    └── auto-scaling.png
