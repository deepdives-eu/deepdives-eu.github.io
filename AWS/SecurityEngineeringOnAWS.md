# Security Engineering on AWS course material links

_Please not that this is not a prep course for the "AWS Certified Security - Specialty" certification!_

This document contains links mentioned in the "Security Engineering on AWS" course.

## Module 0: Course Overview

Full name: Security Engineering on AWS

Product code: 200-SISECO-33

These links are based on the course version 3.3.11.

Online and classroom course options: [Security Engineering on AWS](https://www.aws.training/SessionSearch?pageNumber=1&courseId=10021&languageId=1)

The official course material: [eVantage Bookshelf (VitalSource)](https://evantage.gilmoreglobal.com)

Additional material: [AWS Skill Builder](https://explore.skillbuilder.aws/)

## Module 1: Security Overview

### Websites

- [Applying the AWS Shared Responsibility Model to your GxP Solution](https://aws.amazon.com/blogs/industries/applying-the-aws-shared-responsibility-model-to-your-gxp-solution)
- [AWS Managed Service Provider Program](https://aws.amazon.com/partners/managed-service)
- [AWS Well-Architected Framework Design Principles](https://docs.aws.amazon.com/wellarchitected/latest/framework/sec-design.html)
- [How to approach threat modeling
](https://aws.amazon.com/blogs/security/how-to-approach-threat-modeling)

## Module 2: Access and Authorizations on AWS

### Websites

- [AWS service endpoints](https://docs.aws.amazon.com/general/latest/gr/rande.html#ct_region)
- [AWS Signature Version 4 for API requests](https://docs.aws.amazon.com/general/latest/gr/signing_aws_api_requests.html)
- [AWS services that work with IAM
](https://docs.aws.amazon.com/IAM/latest/UserGuide/reference_aws-services-that-work-with-iam.html)
- [Tasks that require root user credentials](https://docs.aws.amazon.com/accounts/latest/reference/root-user-tasks.html)
- [AWS account root user](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_root-user.html)
- [Secure API access with MFA](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_mfa_configure-api-require.html)
- [IAM Roles Anywhere concepts](https://docs.aws.amazon.com/rolesanywhere/latest/userguide/introduction.html#first-time-user)
- [AWS services that work with IAM](https://docs.aws.amazon.com/IAM/latest/UserGuide/reference_aws-services-that-work-with-iam.html)
- [AWS Policy Generator](https://awspolicygen.s3.amazonaws.com/policygen.html)
- [AWS Policy Simulator](https://policysim.aws.amazon.com)
- [Policy summary (list of services)](https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies_understand-policy-summary.html)
- [Policy evaluation logic](https://docs.aws.amazon.com/IAM/latest/UserGuide/reference_policies_evaluation-logic.html)
- [IAM JSON policy element reference](https://docs.aws.amazon.com/IAM/latest/UserGuide/reference_policies_elements.html)
- [Session policies](https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies.html#policies_session)
- [Working with resource-based IAM policies in Lambda](https://docs.aws.amazon.com/lambda/latest/dg/access-control-resource-based.html)
- [Create fine-grained session permissions using IAM managed policies](https://aws.amazon.com/blogs/security/create-fine-grained-session-permissions-using-iam-managed-policies/)
- [Working with CloudTrail Event history](http://docs.aws.amazon.com/awscloudtrail/latest/userguide/view-cloudtrail-events.html)
- [CloudTrail supported services and integrations](https://docs.aws.amazon.com/awscloudtrail/latest/userguide/cloudtrail-aws-service-specific-topics.html)
- [Validating CloudTrail log file integrity](https://docs.aws.amazon.com/awscloudtrail/latest/userguide/cloudtrail-log-file-validation-intro.html)
- [How AWS uses automated reasoning to help you achieve security at scale](https://aws.amazon.com/blogs/security/protect-sensitive-data-in-the-cloud-with-automated-reasoning-zelkova)

## Module 3: Account Management and Provisioning on AWS

### Websites

- [Benefits of using multiple AWS accounts](https://docs.aws.amazon.com/accounts/latest/reference/welcome-multiple-accounts.html)
- [SCPs and guardrails in your AWS Organization](https://aws.amazon.com/blogs/security/how-to-use-service-control-policies-to-set-permission-guardrails-across-accounts-in-your-aws-organization/)
- [Organizing your AWS Control Tower landing zone with nested OUs](https://aws.amazon.com/blogs/mt/organizing-your-aws-control-tower-landing-zone-with-nested-ous)
- [AWS Control Tower](https://aws.amazon.com/controltower)
- [How AWS Control Tower Works](https://docs.aws.amazon.com/controltower/latest/userguide/how-control-tower-works.html)
- [Strategies for consolidating AWS environments](https://aws.amazon.com/blogs/mt/strategies-for-consolidating-aws-environments)
- [Enabling self-service provisioning of AWS resources with AWS Control Tower](https://aws.amazon.com/blogs/mt/enabling-self-service-provisioning-of-aws-resources-with-aws-control-tower)
- [Enabling SAML for your AWS resources](https://aws.amazon.com/identity/saml)
- [Roles, terms and concepts](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_roles_terms-and-concepts.html#iam-term-service-linked-role)
- [Introducing AWS IAM Identity Center](https://aws.amazon.com/blogs/security/introducing-aws-single-sign-on)
- [Common Amazon Cognito scenarios](https://docs.aws.amazon.com/cognito/latest/developerguide/cognito-scenarios.html)
- [Working with adaptive authentication](https://docs.aws.amazon.com/cognito/latest/developerguide/cognito-user-pool-settings-adaptive-authentication.html)

## Module 4: Managing Keys and Secrets on AWS

### Websites

- [Protecting data with encryption](https://docs.aws.amazon.com/AmazonS3/latest/dev/UsingEncryption.html)
- [What is the AWS Encryption SDK?](https://docs.aws.amazon.com/encryption-sdk/latest/developer-guide/introduction.html)
- [AWS Key Management Service introduces new HMAC API
](https://aws.amazon.com/about-aws/whats-new/2022/04/aws-key-management-service-hmac-api)
- [Using AWS KMS encryption with AWS services](https://docs.aws.amazon.com/kms/latest/developerguide/service-integration.html)
- [Grants in AWS KMS](https://docs.aws.amazon.com/kms/latest/developerguide/grants.html)
- [External key stores](https://docs.aws.amazon.com/kms/latest/developerguide/keystore-external.html)
- [Multi-Region keys in AWS KMS](https://docs.aws.amazon.com/kms/latest/developerguide/multi-region-keys-overview.html)
- [AWS CloudHSM clusters](https://docs.aws.amazon.com/cloudhsm/latest/userguide/clusters.html)
- [AWS Key Management Service](https://docs.aws.amazon.com/kms/latest/developerguide/custom-key-store-overview.html)
- [Are KMS custom key stores right for you?](https://aws.amazon.com/blogs/security/are-kms-custom-key-stores-right-for-you)
- [Database Credentials, Lambda Functions and AWS Secrets Manager](https://aws.amazon.com/blogs/security/how-to-securely-provide-database-credentials-to-lambda-functions-by-using-aws-secrets-manager)
- [What is AWS Secrets Manager?](https://docs.aws.amazon.com/secretsmanager/latest/userguide/terms-concepts.html)
- [Identity-based policies](https://docs.aws.amazon.com/secretsmanager/latest/userguide/auth-and-access_examples.html#auth-and-access_examples_read)
- [Managing Parameter Store parameter tiers
](https://docs.aws.amazon.com/systems-manager/latest/userguide/parameter-store-advanced-parameters.html)

## Module 5: Data Security

### Websites

- [Using access points](https://docs.aws.amazon.com/AmazonS3/latest/dev/using-access-points.html#access-points-service-api-support)
- [Correlate IAM Access Analyzer findings with Amazon Macie](https://aws.amazon.com/blogs/security/correlate-iam-access-analyzer-findings-with-amazon-macie)
- [Client-side and server-side encryption](https://docs.aws.amazon.com/dynamodb-encryption-client/latest/devguide/client-server-side.html)
- [Creating security groups](https://docs.aws.amazon.com/efs/latest/ug/accessing-fs-create-security-groups.html)
- [Amazon VPC Security Groups](https://docs.aws.amazon.com/fsx/latest/WindowsGuide/limit-access-security-groups.html#fsx-vpc-security-groups)
- [Securing your data in Amazon EFS](https://docs.aws.amazon.com/efs/latest/ug/security-considerations.html)
- [Encryption at Rest](https://docs.aws.amazon.com/fsx/latest/WindowsGuide/encryption-at-rest.html)
- [S3 Glacier Vault Lock](https://docs.aws.amazon.com/amazonglacier/latest/dev/vault-lock.html)

## Module 6: Infrastructure and Edge Protection

### Websites

- [Amazon VPC now supports an AWS-managed prefix list for Amazon CloudFront](https://aws.amazon.com/about-aws/whats-new/2022/02/amazon-cloudfront-managed-prefix-list/)
- [AWS Best Practices for DDoS Resiliency](https://d1.awsstatic.com/whitepapers/DDoS_White_Paper_June2015.pdf)
- [Combinations Calculator (nCr)](https://www.calculatorsoup.com/calculators/discretemathematics/combinations.php)

## Module 7: Monitoring and Collecting Logs on AWS

### Websites

- [Multi-Account Multi-Region Data Aggregation](https://docs.aws.amazon.com/config/latest/developerguide/aggregate-data.html)
- [Supported Resource Types](http://docs.aws.amazon.com/config/latest/developerguide/resource-config-reference.html)
- [AWS Config Managed Rules](http://docs.aws.amazon.com/config/latest/developerguide/evaluate-config_use-managed-rules.html)
- [AWS Config Custom Rules](https://docs.aws.amazon.com/config/latest/developerguide/evaluate-config_develop-rules.html)
- [Logging IP traffic using VPC Flow Logs](https://docs.aws.amazon.com/AmazonVPC/latest/UserGuide/flow-logs.html#flow-log-records)
- [CloudWatch Logs Insights query syntax](https://docs.aws.amazon.com/AmazonCloudWatch/latest/logs/CWL_QuerySyntax.html)
- [Access logs for your Application Load Balancer](https://docs.aws.amazon.com/elasticloadbalancing/latest/application/load-balancer-access-logs.html)
- [Amazon S3 server access log format](https://docs.aws.amazon.com/AmazonS3/latest/dev/LogFormat.html)
- [EventBridge is the evolution of Amazon CloudWatch Events](https://docs.aws.amazon.com/AmazonCloudWatch/latest/events/WhatIsCloudWatchEvents.html)
- [How to Receive Notifications When Your AWS Account’s Root Access Keys Are Used](https://aws.amazon.com/blogs/security/how-to-receive-notifications-when-your-aws-accounts-root-access-keys-are-used/)
- [Instance metrics](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/viewing_metrics_with_cloudwatch.html#ec2-cloudwatch-metrics)
- [Amazon Data Firehose / CreateDeliveryStream](https://docs.aws.amazon.com/firehose/latest/APIReference/API_CreateDeliveryStream.html)
- [Analyzing Data in S3 using Amazon Athena](https://aws.amazon.com/blogs/big-data/analyzing-data-in-s3-using-amazon-athena)
- [What is Amazon Athena?](https://docs.aws.amazon.com/athena/latest/ug/supported-format.html)
- [Amazon Athena / Encryption at rest](https://docs.aws.amazon.com/athena/latest/ug/encryption.html)
- [Query flow logs using Amazon Athena](https://docs.aws.amazon.com/vpc/latest/userguide/flow-logs-athena.html)
- [OpenSearch Documentation](https://opensearch.org/docs/latest)
- [Build a Log Analytics Solution on
AWS](https://d1.awsstatic.com/Projects/P4113850/aws-projects_build-log-analytics-solution-on-aws.pdf)
- [Centralized Logging with OpenSearch](https://docs.aws.amazon.com/pdfs/solutions/latest/centralized-logging-with-opensearch/centralized-logging-with-opensearch.pdf)
- [Centralized Logging with OpenSearch (implementation guide)](https://aws.amazon.com/solutions/implementations/centralized-logging-with-opensearch)

## Module 8: Responding to Threats

### Websites

- [AWS Security Incident Response Guide](https://docs.aws.amazon.com/whitepapers/latest/aws-security-incident-response-guide/welcome.html)
- [Penetration Testing](https://aws.amazon.com/security/penetration-testing)
- [Amazon SNS message data protection](https://aws.amazon.com/about-aws/whats-new/2022/11/amazon-sns-message-data-protection-available-real-time-data-redaction-masking)
- [Automated Security Response on AWS](https://aws.amazon.com/solutions/implementations/automated-security-response-on-aws)
- [What is Amazon GuardDuty?](https://docs.aws.amazon.com/guardduty/latest/ug/guarduty_upload-lists.html)
- [Cyber Threat Intelligence (CTI)](https://oasis-open.github.io/cti-documentation)
- [Overview of the behavior graph data structure](https://docs.aws.amazon.com/detective/latest/userguide/graph-data-structure-overview.html)
- [What is Amazon Detective?](https://docs.aws.amazon.com/detective/latest/adminguide/detective-source-data-about.html)
- [AWS Security Blog](https://aws.amazon.com/blogs/security/)
- [Automated Forensics Orchestrator for Amazon EC2](https://aws.amazon.com/solutions/implementations/automated-forensics-orchestrator-for-amazon-ec2)

## Module 9: Course Wrap-Up

### Websites

- Serverless Architectures with [AWS Lambda](https://d1.awsstatic.com/whitepapers/serverless-architectures-with-aws-lambda.pdf)
- How AWS [Pricing](https://docs.aws.amazon.com/whitepapers/latest/how-aws-pricing-works/welcome.html) Works
- Back to [Basics](https://aws.amazon.com/architecture/back-to-basics/?tma.sort-by=item.additionalFields.airDate&tma.sort-order=desc&awsf.categories=*all&awsm.page-tma=2)
- [AWS Support](https://aws.amazon.com/premiumsupport/)
- AWS Certification [exam preparation](https://aws.amazon.com/certification/certification-prep/)
- [AWS Certification](https://aws.amazon.com/certification/)
- AWS Certification [exams](https://aws.amazon.com/certification/exams/)
- [AWS Recertification](https://aws.amazon.com/certification/recertification/)
- Schedule an [Exam](https://aws.amazon.com/certification/certification-prep/testing/)
- [AWS Ramp-Up Guides](https://aws.amazon.com/training/ramp-up-guides/)

### Courses

- [Advanced Developing on AWS](https://www.aws.training/SessionSearch?pageNumber=1&courseId=36896&languageId=1)
- [Developing Serverless Solutions on AWS](https://www.aws.training/SessionSearch?pageNumber=1&courseId=53785&languageId=1)
- [Build Modern Applications with AWS NoSQL Databases](https://aws.amazon.com/training/classroom/build-modern-applications-with-aws-nosql-databases/)
- [Getting Started with DevOps on AWS](https://www.aws.training/Details/eLearning?id=66768) 
- [AWS Cloud Development Kit Primer](https://www.aws.training/Details/Curriculum?id=64511)
- [AWS Skill Builder](https://aws.amazon.com/training/digital)
- AWS Skill Builder [courses](https://explore.skillbuilder.aws/learn)
- [AWS Builder Labs](https://aws.amazon.com/training/digital/aws-builder-labs/)
- [AWS Workshops](https://workshops.aws/)
- [Classroom training](https://aws.amazon.com/training) 

### Videos

- [Tech Talks](https://aws.amazon.com/events/online-tech-talks/on-demand/)
