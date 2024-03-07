# Advanced Architecting on AWS course material links

_Please not that this is not a prep course for the "AWS Certified Solutions Architect - Professional" certification!_

This document contains links mentioned in the "Advanced Architecting on AWS" course. 

## Module 0: Course Introduction

Full name: Developing on AWS

Product code: 300-ADVARC-37

These links are based on the course version 3.7.3.

The official course material: [eVantage Bookshelf (VitalSource)](https://evantage.gilmoreglobal.com)

[Online Course Supplement (OCS) material](https://explore.skillbuilder.aws/learn/course/1283/advanced-architecting-on-aws-online-course-supplement)

Additional material: [AWS Skill Builder](https://explore.skillbuilder.aws/)

## Module 1: Review Architecting Concepts

### Websites

- Amazon Virtual Private Cloud (VPC) [User Guide](https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Subnets.html)
- EC2 Auto Scaling [User Guide](https://docs.aws.amazon.com/autoscaling/ec2/userguide/what-is-amazon-ec2-auto-scaling.html)
- Amazon Aurora [User Guide](https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/CHAP_AuroraOverview.html)
- S3 [User Guide](https://docs.aws.amazon.com/AmazonS3/latest/userguide/Welcome.html)
- EC2 [User Guide](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/concepts.html)
- EFS [overview](https://aws.amazon.com/efs/faq) & [User Guide](https://docs.aws.amazon.com/efs/latest/ug/whatisefs.html)
- Route 53 [overview](https://aws.amazon.com/route53/faqs) & [Developer Guide](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/Welcome.html)
- [NAT gateways](https://docs.aws.amazon.com/vpc/latest/userguide/vpc-nat-gateway.html)
- [Target groups](https://docs.aws.amazon.com/elasticloadbalancing/latest/application/load-balancer-target-groups.html) for your Application Load Balancers
- [Launch Templates](https://docs.aws.amazon.com/autoscaling/ec2/userguide/create-launch-template.html)
- Caching [Overview](https://aws.amazon.com/caching)
- [High availability](https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/Concepts.AuroraHighAvailability.html) for Amazon Aurora
- [S3 lifecycle configuration](https://docs.aws.amazon.com/AmazonS3/latest/userguide/how-to-set-lifecycle-configuration-intro.html)
- Connect to the internet using an [internet gateway](https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Internet_Gateway.html)
- [Connect to your Linux instance](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AccessingInstances.html)
- [CloudFront distribution origins](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/DownloadDistS3AndCustomOrigins.html)
- [AWS PrivateLink for S3](https://aws.amazon.com/blogs/aws/aws-privatelink-for-amazon-s3-now-available/)

## Module 2: Single to Multiple Accounts 

### Websites

- IAM [User Guide](https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html)
- AWS Organizations [User Guide](https://docs.aws.amazon.com/organizations/latest/userguide/orgs_introduction.html)
- IAM Identity Center [User Guide](https://docs.aws.amazon.com/singlesignon/latest/userguide/what-is.html)
- AWS CLI [User Guide](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-welcome.html)
- AWS Control Tower [User Guide](https://docs.aws.amazon.com/controltower/latest/userguide/what-is-control-tower.html)
- [Providing access to an IAM user in another AWS account](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_roles_common-scenarios_aws-accounts.html)
- [Cross-account access](https://aws.amazon.com/blogs/security/enable-a-new-feature-in-the-aws-management-console-cross-account-access/)
- [Switching to an IAM role](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_roles_use_switch-role-api.html)
- [Test access by switching roles](https://docs.aws.amazon.com/IAM/latest/UserGuide/tutorial_cross-account-with-roles.html#tutorial_cross-account-with-roles-3)
- AWS Organizations [terminology and concepts](https://docs.aws.amazon.com/organizations/latest/userguide/orgs_getting-started_concepts.html)
- [Managing organizational units](https://docs.aws.amazon.com/organizations/latest/userguide/orgs_manage_ous.html)
- Service control policy [examples](https://docs.aws.amazon.com/organizations/latest/userguide/orgs_manage_policies_scps_examples.html)
- SCP [syntax](https://docs.aws.amazon.com/organizations/latest/userguide/orgs_manage_policies_scps_syntax.html)
- [manage users within](https://aws.amazon.com/blogs/security/how-to-create-and-manage-users-within-aws-sso/) AWS IAM Identity Center
- AWS CLI [new features](https://aws.amazon.com/blogs/developer/aws-cli-v2-is-now-generally-available/)
- AWS CLI [update instructions](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)
- [AWS Services by Region](https://aws.amazon.com/about-aws/global-infrastructure/regional-product-services/)
- [About controls in AWS Control Tower](https://docs.aws.amazon.com/controltower/latest/userguide/controls.html)
- [manage accounts](https://docs.aws.amazon.com/controltower/latest/userguide/account-factory.html) with Account Factory
- [How AWS Control Tower Works](https://docs.aws.amazon.com/controltower/latest/userguide/how-control-tower-works.html)
- Field Notes: [Enroll Existing AWS Accounts](https://aws.amazon.com/blogs/architecture/field-notes-enroll-existing-aws-accounts-into-aws-control-tower/) into AWS Control Tower 
- [Enroll an existing AWS account](https://docs.aws.amazon.com/controltower/latest/userguide/enroll-account.html)
- [Best practices](https://docs.aws.amazon.com/controltower/latest/userguide/best-practices.html) for AWS Control Tower administrators
- [Best Practices](https://aws.amazon.com/blogs/mt/best-practices-for-organizational-units-with-aws-organizations/?org_product_gs_bp_OUBlog) for Organizational Units with AWS Organizations

## Module 3: Hybrid Connectivity

### Websites

- AWS Global Accelerator [Developer Guide](https://docs.aws.amazon.com/global-accelerator/latest/dg/what-is-global-accelerator.html)
- AWS Direct Connect [User Guide](https://docs.aws.amazon.com/directconnect/latest/UserGuide/Welcome.html)
- [VPCs and subnets](https://docs.aws.amazon.com/vpc/latest/userguide/how-it-works.html#how-it-works-subnet)
- What is [AWS Client VPN](https://docs.aws.amazon.com/vpn/latest/clientvpn-admin/what-is.html#what-is-limitations)?
- [Scenarios and examples](https://docs.aws.amazon.com/vpn/latest/clientvpn-admin/scenario.html) for AWS Client VPN
- [Authenticate](https://aws.amazon.com/blogs/security/authenticate-aws-client-vpn-users-with-aws-single-sign-on/) AWS Client VPN users with AWS IAM Identity Center
- [Modify Client VPN Endpoint](https://docs.aws.amazon.com/AWSEC2/latest/APIReference/API_ModifyClientVpnEndpoint.html)
- [customer gateway device](https://docs.aws.amazon.com/vpn/latest/s2svpn/your-cgw.html)
- [Tunnel options](https://docs.aws.amazon.com/vpn/latest/s2svpn/VPNTunnels.html) for your Site-to-Site VPN connection
- [Customer gateway options](https://docs.aws.amazon.com/vpn/latest/s2svpn/cgw-options.html) for your Site-to-Site VPN connection
- [Scaling VPN throughput](https://aws.amazon.com/blogs/networking-and-content-delivery/scaling-vpn-throughput-using-aws-transit-gateway/) using AWS Transit Gateway
- [Improve VPN Network Performance](https://aws.amazon.com/blogs/architecture/improve-vpn-network-performance-of-aws-hybrid-cloud-with-global-accelerator/)
- [Encryption](https://docs.aws.amazon.com/directconnect/latest/UserGuide/encryption-in-transit.html) in AWS Direct Connect
- AWS Direct Connect [features](https://aws.amazon.com/directconnect/features/)
- AWS Direct Connect [Delivery Partners](https://aws.amazon.com/directconnect/partners/)
- [Bidirectional Forwarding Detection (BFD)](https://aws.amazon.com/premiumsupport/knowledge-center/enable-bfd-direct-connect/) for Direct Connect
- [Network MTU](https://docs.aws.amazon.com/directconnect/latest/UserGuide/set-jumbo-frames-vif.html) for private virtual interfaces
- [EFS and Direct Connect](https://aws.amazon.com/blogs/aws/amazon-efs-update-on-premises-access-via-direct-connect-vpc/)
- [Private IP VPN](https://docs.aws.amazon.com/vpn/latest/s2svpn/private-ip-dx.html) with AWS Direct Connect
- Site-to-Site VPN [routing options](https://docs.aws.amazon.com/vpn/latest/s2svpn/VPNRoutingTypes.html)

## Module 4: Specialized Infrastructure

### Websites

- AWS Storage Gateway [User Guides](https://docs.aws.amazon.com/storagegateway/latest/userguide/WhatIsStorageGateway.html)
- AWS Wavelength [Developer Guide](https://docs.aws.amazon.com/wavelength/latest/developerguide/what-is-wavelength.html)
- [AWS Outposts Family](https://docs.aws.amazon.com/outposts/latest/userguide/what-is-outposts.html#services)
- [Site requirements](https://docs.aws.amazon.com/outposts/latest/userguide/outposts-requirements.html) for Outposts rack
- AWS Outposts Servers [Features](https://aws.amazon.com/outposts/servers/features/)
- AWS Local Zones [locations](https://aws.amazon.com/about-aws/global-infrastructure/localzones/locations/)
- AWS Local Zones [overview](https://aws.amazon.com/about-aws/global-infrastructure/localzones/)
- AWS Storage Gateway [FAQs](https://aws.amazon.com/storagegateway/faqs/)
- AWS Outposts Rack [FAQs](https://aws.amazon.com/outposts/faqs/)
- AWS Local Zones [FAQs](https://aws.amazon.com/about-aws/global-infrastructure/localzones/faqs/)

## Module 5: Connecting Networks

### Websites

- Transit gateway [use cases](https://docs.aws.amazon.com/vpc/latest/tgw/TGW_Scenarios.html)
- Transit gateway [associations](https://docs.aws.amazon.com/directconnect/latest/UserGuide/direct-connect-transit-gateways.html)
- [How Reachability Analyzer works](https://docs.aws.amazon.com/vpc/latest/reachability/how-reachability-analyzer-works.html)
- [AWS PrivateLink](https://docs.aws.amazon.com/vpc/latest/userguide/endpoint-service.html)
- [AWS Marketplace](https://aws.amazon.com/marketplace)
- [AWS Compliance Programs](https://aws.amazon.com/compliance/programs/)
- AWS PrivateLink [Guide](https://docs.aws.amazon.com/vpc/latest/privatelink/what-is-privatelink.html)

### Videos

- AWS on Air 2020: [VPC Reachability Analyzer](https://www.youtube.com/watch?v=KuwPQL2zYNQ)

## Module 6: Containers

### Websites

- [Containers on AWS](https://aws.amazon.com/containers/services/)
- [Docker Engine overview](https://docs.docker.com/engine/)
- [Understanding Docker Container Architecture](https://collabnix.com/understanding-docker-container-image/)
- [Docker overview](https://docs.docker.com/get-started/overview/)
- Amazon ECR Public [User Guide](https://docs.aws.amazon.com/AmazonECR/latest/public/what-is-ecr.html)
- [ECR Public and ECR Public Gallery](https://aws.amazon.com/about-aws/whats-new/2020/12/announcing-amazon-ecr-public-and-amazon-ecr-public-gallery/)
- [Docker image tag](https://docs.docker.com/engine/reference/commandline/tag/)
- [Amazon EKS Anywhere](https://aws.amazon.com/blogs/aws/amazon-eks-anywhere-now-generally-available-to-create-and-manage-kubernetes-clusters-on-premises/)
- [ECS task definition](http://docs.aws.amazon.com/AmazonECS/latest/developerguide/create-task-definition.html)
- [Example ECS task definitions](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/example_task_definitions.html)
- ECS [Developer Guide](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/Welcome.html)
- [ECS task placement strategies](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/task-placement-strategies.html)
- [Amazon ECS task placement constraints](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/task-placement-constraints.html)
- [Cluster management](https://docs.aws.amazon.com/AmazonECS/latest/userguide/clusters-concepts.html)
- [Amazon EKS ended support for Dockershim](https://docs.aws.amazon.com/eks/latest/userguide/dockershim-deprecation.html)
- [Creating a task definition using the console](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/create-task-definition.html)
- [Task definition parameters](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/task_definition_parameters.html)
- [ECS clusters and capacity](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/clusters.html)
- Migrating Your Amazon ECS Containers to [AWS Fargate](https://aws.amazon.com/blogs/compute/migrating-your-amazon-ecs-containers-to-aws-fargate)
- [Using data volumes in tasks](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/using_data_volumes.html)

## Module 7: Continuous Integration/Continuous Delivery (CI/CD)

### Websites

- CodePipeline [User Guide](https://docs.aws.amazon.com/codepipeline/latest/userguide/welcome.html)
- Code Commit [User Guide](https://docs.aws.amazon.com/codecommit/latest/userguide/welcome.html)
- CodeDeploy [User Guide](https://docs.aws.amazon.com/codedeploy/latest/userguide/welcome.html)
- [Developer Tools on AWS (overview)](https://aws.amazon.com/products/developer-tools)
- [Developer tools](https://docs.aws.amazon.com/whitepapers/latest/aws-overview/developer-tools.html)
- Getting started with [Amazon CodeWhisperer](https://docs.aws.amazon.com/codewhisperer/latest/userguide/getting-started.html)
- CodeWhisperer [Resources](https://aws.amazon.com/codewhisperer/resources)
- CodeWhisperer course in [Skill Builder](https://explore.skillbuilder.aws/learn/course/external/view/elearning/16405/amazon-codewhisperer-getting-started)
- A small tutorial to [create a simple pipeline](https://docs.aws.amazon.com/codepipeline/latest/userguide/tutorials-simple-s3.html)
- CodePipeline [product integrations](https://aws.amazon.com/codepipeline/product-integrations)
- [integrations](https://docs.aws.amazon.com/codedeploy/latest/userguide/integrations.html) with CodeDeploy
- CodeDeploy [policy examples](https://docs.aws.amazon.com/codedeploy/latest/userguide/security_iam_id-based-policy-examples.html)
- [Continuous Deployment](https://aws.amazon.com/blogs/compute/continuous-deployment-to-amazon-ecs-using-aws-codepipeline-aws-codebuild-amazon-ecr-and-aws-cloudformation/) using AWS CodePipeline
- [What is DevOps?](https://aws.amazon.com/devops/what-is-devops/)
- [Practicing Continuous Integration and Continuous Delivery on AWS](https://d0.awsstatic.com/whitepapers/DevOps/practicing-continuous-integration-continuous-delivery-on-AWS.pdf)
- [What can I do with CodePipeline?](https://docs.aws.amazon.com/codepipeline/latest/userguide/welcome-what-can-I-do.html)
- [Infrastructure as code (IaC)](https://docs.aws.amazon.com/whitepapers/latest/introduction-devops-aws/infrastructure-as-code.html)
- [Blue/Green Deployments on AWS](https://d0.awsstatic.com/whitepapers/AWS_Blue_Green_Deployments.pdf)

## Module 8: High Availability and DDos

### Websites

- AWS WAF [User Guide](https://docs.aws.amazon.com/waf/latest/developerguide/what-is-aws-waf.html)
- [How AWS Shield works](https://docs.aws.amazon.com/waf/latest/developerguide/ddos-overview.html)
- [WAF Rule statement basics](https://docs.aws.amazon.com/waf/latest/developerguide/waf-rule-statements.html)
- [Analyze AWS WAF logs](https://aws.amazon.com/blogs/security/analyze-aws-waf-logs-using-amazon-opensearch-service-anomaly-detection-built-on-random-cut-forests/)
- [Security Automations](https://aws.amazon.com/solutions/implementations/aws-waf-security-automations/) for AWS WAF
- Use GuardDuty and WAF to [automatically block suspicious hosts](https://aws.amazon.com/blogs/security/how-to-use-amazon-guardduty-and-aws-web-application-firewall-to-automatically-block-suspicious-hosts/)
- AWS Shield [Features](https://aws.amazon.com/shield/features/)
- [Control traffic to subnets using network ACLs](https://docs.aws.amazon.com/vpc/latest/userguide/vpc-network-acls.html)
- AWS Shield [Engagement Lambda](https://s3.amazonaws.com/aws-shield-lambda/ShieldEngagementLambda.pdf)
- AWS WAF [pricing](https://aws.amazon.com/waf/pricing/)
- AWS Config [pricing](https://aws.amazon.com/config/pricing/)
- AWS Firewall Manager [prerequisites](https://docs.aws.amazon.com/waf/latest/developerguide/fms-prereq.html)

## Module 9: Securing Data

### Websites

- AWS Key Management Service (KMS) [Developer Guide](https://docs.aws.amazon.com/kms/latest/developerguide/overview.html)
- AWS Secrets Manager [User Guide](https://docs.aws.amazon.com/secretsmanager/latest/userguide/intro.html)
- AWS CloudHSM [User Guide](https://docs.aws.amazon.com/cloudhsm/latest/userguide/introduction.html)
- KMS [features](https://aws.amazon.com/kms/features/)
- [KMS concepts](https://docs.aws.amazon.com/kms/latest/developerguide/concepts.html)
- [Asymmetric keys](https://docs.aws.amazon.com/kms/latest/developerguide/symmetric-asymmetric.html)
- [HSM users in CloudHSM](https://docs.aws.amazon.com/cloudhsm/latest/userguide/manage-hsm-users.html#crypto-officer)
- [Using quorum authentication for crypto officers](https://docs.aws.amazon.com/cloudhsm/latest/userguide/quorum-authentication-crypto-officers.html)
- [Oracle Transparent Data Encryption](https://aws.amazon.com/about-aws/whats-new/2015/01/08/amazon-rds-integrates-oracle-tde-with-cloudhsm/)
- Oracle Transparent Data Encryption [configuration](https://docs.aws.amazon.com/cloudhsm/latest/userguide/oracle-tde.html)
- [Database credentials and AWS Secrets Manager](https://aws.amazon.com/blogs/security/how-to-securely-provide-database-credentials-to-lambda-functions-by-using-aws-secrets-manager/)
- [AWS Secrets Manager concepts](https://docs.aws.amazon.com/secretsmanager/latest/userguide/terms-concepts.html)
- [Rotate](https://docs.aws.amazon.com/secretsmanager/latest/userguide/rotating-secrets.html) AWS Secrets Manager secrets
- [Configuring S3 default encryption](https://docs.aws.amazon.com/AmazonS3/latest/userguide/default-bucket-encryption.html)
- [Using server-side encryption with customer-provided keys (SSE-C)](https://docs.aws.amazon.com/AmazonS3/latest/userguide/ServerSideEncryptionCustomerKeys.html)

## Module 10: Large Scale Data Stores

### Websites

- S3 [pricing](https://aws.amazon.com/s3/pricing)
- [Amazon S3 Inventory](https://docs.aws.amazon.com/AmazonS3/latest/userguide/storage-inventory.html)
- Lake Formation [permissions](https://docs.aws.amazon.com/lake-formation/latest/dg/implicit-permissions.html)
- [S3 access with VPC endpoints and S3 Access Points](https://aws.amazon.com/blogs/storage/managing-amazon-s3-access-with-vpc-endpoints-and-s3-access-points/)
- [S3 Batch Operations](https://docs.aws.amazon.com/AmazonS3/latest/userguide/batch-ops.html)
- [S3 Intelligent-Tiering](https://docs.aws.amazon.com/AmazonS3/latest/userguide/storage-class-intro.html#sc-dynamic-data-access)
- [Blueprints and workflows](https://docs.aws.amazon.com/lake-formation/latest/dg/workflows-about.html) in Lake Formation

## Module 11: Migrating Workloads

### Websites

### Courses

### Videos

## Module 12: Optimizing Cost

### Websites

### Courses

### Videos

## Module 13: Architecting for the Edge

### Websites

### Courses

### Videos

## Module 14: Review

### Websites

### Courses

### Videos
