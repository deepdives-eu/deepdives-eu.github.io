# Running Containers on Amazon Elastic Kubernetes Service course material links

_Please not that this is not a prep course for any AWS certification!_

This document contains links mentioned in the "Running Containers on Amazon Elastic Kubernetes Service" course. 

## Module 0: Course Introduction

Full name: Running Containers on Amazon Elastic Kubernetes Service

Product code: 200-COREKS-21

These links are based on the course version 2.1.1.

The official course material: [eVantage Bookshelf (VitalSource)](https://evantage.gilmoreglobal.com)

[AWS Documentation](https://docs.aws.amazon.com/)

Additional material: [AWS Skill Builder](https://explore.skillbuilder.aws/)

## Module 1: Kubernetes Fundamentals

### Websites

- [The Twelve-Factor App](https://12factor.net/)
- [Containers on AWS](https://aws.amazon.com/containers/)
- [CNCF Projects](https://www.cncf.io/projects/)
- [Kubernetes Documentation: Overview](https://kubernetes.io/docs/concepts/overview/)
- [Nodes](https://kubernetes.io/docs/concepts/architecture/nodes/)
- [Building Large Clusters](https://kubernetes.io/docs/setup/best-practices/cluster-large/)
- [Managing Resources for Containers](https://kubernetes.io/docs/concepts/configuration/manage-resources-containers/#requests-and-limits)
- [Affinity and anti-affinity](https://kubernetes.io/docs/concepts/scheduling-eviction/assign-pod-node/#affinity-and-anti-affinity)
- [Labels, Annotations, and Taints](https://kubernetes.io/docs/reference/labels-annotations-taints/)
- [Multi-tenancy](https://kubernetes.io/docs/concepts/security/multi-tenancy/)
- [Workloads](https://kubernetes.io/docs/concepts/workloads/)
- [Bare Pods](https://kubernetes.io/docs/concepts/workloads/controllers/job/#bare-pods)


### AWS Services

- Amazon EKS [Overview](https://aws.amazon.com/documentation-overview/eks/) - [Documentation](https://docs.aws.amazon.com/eks/)
- Amazon ECS [Overview](https://aws.amazon.com/documentation-overview/ecs/) - [Documentation](https://docs.aws.amazon.com/ecs/)
- AWS Fargate [Overview](https://aws.amazon.com/documentation-overview/fargate/) - [Documentation](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/AWS_Fargate.html)

## Module 2: Amazon Elastic Kubernetes Service (Amazon EKS) Fundamentals

### Websites

- [AWS Fargate – Amazon EKS](https://docs.aws.amazon.com/eks/latest/userguide/fargate.html)
- [Services in Scope by Compliance Program](https://aws.amazon.com/compliance/services-in-scope/)
- [AWS Fargate Considerations – Amazon EKS](https://docs.aws.amazon.com/eks/latest/userguide/fargate.html#fargate-considerations)
- [eksctl - The Official CLI for Amazon EKS](https://eksctl.io/#)

### AWS Services

- AWS Fargate [Overview](https://aws.amazon.com/documentation-overview/fargate/) - [Documentation](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/AWS_Fargate.html)
- AWS Compliance [Overview](https://aws.amazon.com/compliance/) - [Documentation](https://aws.amazon.com/compliance/resources/)

## Module 3: Building and Maintaining an Amazon EKS Cluster

### Websites

- [Getting Started with Amazon EKS – eksctl](https://docs.aws.amazon.com/eks/latest/userguide/getting-started-eksctl.html)
- [Installing the AWS CLI Version 2](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-install.html)
- [Installing `aws-iam-authenticator`](https://docs.aws.amazon.com/eks/latest/userguide/install-aws-iam-authenticator.html)
- [Installing `kubectl`](https://docs.aws.amazon.com/eks/latest/userguide/install-kubectl.html)
- [eksctl GitHub Repository](https://github.com/eksctl-io/eksctl)
- [eksctl - The Official CLI for Amazon EKS](https://eksctl.io/)
- [Amazon EKS AMI Build Scripts](https://github.com/awslabs/amazon-eks-ami)
- [AWS CDK EKS Blueprints Quick Start](https://aws-quickstart.github.io/cdk-eks-blueprints/)
- [Updating an Amazon EKS Cluster Kubernetes Version](https://docs.aws.amazon.com/eks/latest/userguide/update-cluster.html)
- [Kubernetes Changelog](https://github.com/kubernetes/kubernetes/tree/master/CHANGELOG)
- [Version Skew Policy](https://kubernetes.io/docs/setup/release/version-skew-policy/)
- [Kubernetes API Deprecation Policy](https://kubernetes.io/docs/reference/using-api/deprecation-policy/)
- [Kubernetes API Deprecation Guide](https://kubernetes.io/docs/reference/using-api/deprecation-guide/)
- [Amazon EKS Extended Support for Kubernetes Versions Pricing](https://aws.amazon.com/blogs/containers/amazon-eks-extended-support-for-kubernetes-versions-pricing/)
- [Backup and Restore Your Amazon EKS Cluster Resources Using Velero](https://aws.amazon.com/blogs/containers/backup-and-restore-your-amazon-eks-cluster-resources-using-velero/)
- [Upgrades / AWS EKS Best Practices Guides](https://aws.github.io/aws-eks-best-practices/upgrades/)
- [Updating a Managed Node Group](https://docs.aws.amazon.com/eks/latest/userguide/update-managed-node-group.html)
- [Amazon EKS-Optimized AMIs](https://docs.aws.amazon.com/eks/latest/userguide/eks-optimized-ami.html)

### AWS Services

- Amazon EKS [Overview](https://aws.amazon.com/documentation-overview/eks/) - [Documentation](https://docs.aws.amazon.com/eks/)
- AWS IAM [Overview](https://aws.amazon.com/iam/) - [Documentation](https://docs.aws.amazon.com/iam/)
- AWS CloudFormation [Overview](https://aws.amazon.com/documentation-overview/cloudformation/) - [Documentation](https://docs.aws.amazon.com/cloudformation/)

## Module 4: Deploying Applications to Your Amazon Elastic Kubernetes Service (Amazon EKS) Cluster

### Websites

- [Amazon Elastic Container Registry (ECR)](https://aws.amazon.com/ecr/)
- [Clair](https://github.com/quay/clair)
- [Scan images for OS and programming language package vulnerabilities in Amazon ECR](https://docs.aws.amazon.com/AmazonECR/latest/userguide/image-scanning-enhanced.html)
- [Creating an Amazon ECR private repository to store images](https://docs.aws.amazon.com/AmazonECR/latest/userguide/repository-create.html)
- [Helm - The package manager for Kubernetes](https://docs.helm.sh/)
- [Helm - Built-in Objects](https://helm.sh/docs/chart_template_guide/builtin_objects/)
- [Helm - The Chart Template Developer's Guide](https://helm.sh/docs/chart_template_guide/)
- [ArtifactHUB - Find, install and publish Cloud Native packages](https://artifacthub.io)
- [Using Amazon ECR Images with Amazon EKS](https://docs.aws.amazon.com/AmazonECR/latest/userguide/ECR_on_EKS.html#using-helm-charts-eks)
- [Set up a Helm v3 chart repository in Amazon S3](https://docs.aws.amazon.com/prescriptive-guidance/latest/patterns/set-up-a-helm-v3-chart-repository-in-amazon-s3.html)

### Services

- Amazon ECR [Overview](https://docs.aws.amazon.com/AmazonECR/latest/userguide/what-is-ecr.html)
- Amazon S3 - [Overview](https://aws.amazon.com/documentation-overview/s3/)

## Module 5: Managing Applications at Scale in Amazon EKS

### Websites

- [Scaling Kubernetes Deployments with Amazon CloudWatch Metrics](https://aws.amazon.com/blogs/compute/scaling-kubernetes-deployments-with-amazon-cloudwatch-metrics/)
- [Horizontal Pod Autoscaler - Amazon EKS](https://docs.aws.amazon.com/eks/latest/userguide/horizontal-pod-autoscaler.html)
- [Meaning of CPU](https://kubernetes.io/docs/concepts/configuration/manage-resources-containers/#meaning-of-cpu)
- [Prometheus Monitoring](https://docs.aws.amazon.com/eks/latest/userguide/prometheus.html)
- [Vertical Pod Autoscaler](https://github.com/kubernetes/autoscaler/tree/master/vertical-pod-autoscaler)
- [Cluster Autoscaler on AWS](https://github.com/kubernetes/autoscaler/blob/master/cluster-autoscaler/cloudprovider/aws/README.md)
- [Cluster Autoscaler FAQ](https://github.com/kubernetes/autoscaler/blob/master/cluster-autoscaler/FAQ.md#what-are-expanders)
- [Cluster Autoscaling](https://aws.github.io/aws-eks-best-practices/cluster-autoscaling/)
- [Karpenter Documentation](https://karpenter.sh/docs)
- [Topology Spread Constraints](https://kubernetes.io/docs/concepts/scheduling-eviction/topology-spread-constraints/)
- [Scheduling Concepts / Karpenter](https://karpenter.sh/docs/concepts/scheduling/)
- [Karpenter](https://aws.github.io/aws-eks-best-practices/karpenter/)
- [Amazon EKS Partners](https://aws.amazon.com/eks/partners/)

### AWS Services

- Amazon CloudWatch [Overview](https://aws.amazon.com/documentation-overview/cloudwatch/)
- Amazon EKS [Overview](https://aws.amazon.com/documentation-overview/eks/)
- AWS Partner Network [Overview](https://aws.amazon.com/partners/)

## Module 6: Managing networking in Amazon EKS

### Websites

- [Network ACLs / Amazon VPC](https://docs.aws.amazon.com/vpc/latest/userguide/vpc-network-acls.html)
- [amazon-vpc-cni-k8s GitHub Repository](https://github.com/aws/amazon-vpc-cni-k8s)
- [Enable Integration with AWS IPAM](https://docs.aws.amazon.com/vpc/latest/ipam/enable-integ-ipam-outside-org.html)
- [Amazon VPC CNI Now Supports Kubernetes Network Policies](https://aws.amazon.com/blogs/containers/amazon-vpc-cni-now-supports-kubernetes-network-policies/)
- [Security Groups for Pods](https://docs.aws.amazon.com/eks/latest/userguide/security-groups-for-pods.html)
- [amazon-vpc-resource-controller-k8s GitHub Repository](https://github.com/aws/amazon-vpc-resource-controller-k8s)
- [Networking and Network Policy Add-ons](https://kubernetes.io/docs/concepts/cluster-administration/addons/#networking-and-network-policy)
- [Security Group Requirements](https://docs.aws.amazon.com/eks/latest/userguide/sec-group-reqs.html)
- [AWS Load Balancer Controller](https://docs.aws.amazon.com/eks/latest/userguide/aws-load-balancer-controller.html)
- [Managing CoreDNS](https://docs.aws.amazon.com/eks/latest/userguide/managing-coredns.html)

### AWS Services

- Amazon VPC [Overview](https://aws.amazon.com/documentation-overview/vpc/) - [Documentation](https://docs.aws.amazon.com/vpc/)
- Amazon EKS [Overview](https://aws.amazon.com/documentation-overview/eks/) - [Documentation](https://docs.aws.amazon.com/eks/)
- Elastic Load Balancing [Overview](https://aws.amazon.com/documentation-overview/elasticloadbalancing/) - [Documentation](https://docs.aws.amazon.com/elasticloadbalancing/)

## Module 7: Configuring observability in an Amazon EKS cluster

### Websites

- [OpenMetrics Specification](https://github.com/OpenObservability/OpenMetrics/blob/main/specification/OpenMetrics.md)
- [Prometheus Monitoring System](https://prometheus.io/)
- [Prometheus Exposition Formats](https://github.com/prometheus/docs/blob/master/content/docs/instrumenting/exposition_formats.md)
- [Grafana Analytics & Monitoring](https://grafana.com/)
- [AWS Distro for OpenTelemetry](https://aws.amazon.com/otel)
- [AWS Distro for OpenTelemetry Is Now Generally Available for Metrics](https://aws.amazon.com/blogs/opensource/aws-distro-for-opentelemetry-is-now-generally-available-for-metrics/)
- [Amazon Managed Service for Prometheus Collector Provides Agentless Metric Collection for Amazon EKS](https://aws.amazon.com/blogs/aws/amazon-managed-service-for-prometheus-collector-provides-agentless-metric-collection-for-amazon-eks/)
- [Container Insights Metrics / Amazon CloudWatch](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/Container-Insights-metrics-EKS.html)
- [Amazon EKS Control Plane Logging](https://docs.aws.amazon.com/eks/latest/userguide/control-plane-logs.html)
- [Amazon OpenSearch Service](https://aws.amazon.com/opensearch-service/)
- [Centralized Container Logging with Fluent Bit](https://aws.amazon.com/blogs/opensource/centralized-container-logging-fluent-bit/)
- [Setting Up Fluent Bit on Amazon EKS](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/Container-Insights-setup-logs-FluentBit.html)
- [Fluent Bit for Amazon EKS on AWS Fargate Is Here](https://aws.amazon.com/blogs/containers/fluent-bit-for-amazon-eks-on-aws-fargate-is-here/)
- [Logging Using Fluent Bit on AWS Fargate](https://docs.aws.amazon.com/eks/latest/userguide/fargate-logging.html)
- [Sidecar vs. Service / AWS Distro for OpenTelemetry](https://aws-otel.github.io/docs/getting-started/collector/sidecar-vs-service)

### AWS Services

- Amazon CloudWatch [Overview](https://aws.amazon.com/documentation-overview/cloudwatch/) - [Documentation](https://docs.aws.amazon.com/cloudwatch/)
- Amazon OpenSearch Service [Overview](https://aws.amazon.com/documentation-overview/opensearch-service/) - [Documentation](https://docs.aws.amazon.com/opensearch-service/)
- AWS Distro for OpenTelemetry [Overview](https://aws.amazon.com/otel/)

## Module 8: Managing Storage in Amazon EKS

### Websites

- [StatefulSet](https://kubernetes.io/docs/concepts/workloads/controllers/statefulset/)
- [Amazon Elastic Block Store (EBS)](https://aws.amazon.com/ebs/)
- [Amazon Elastic File System (EFS)](https://aws.amazon.com/efs/)
- [Amazon FSx File Systems](https://aws.amazon.com/fsx/)
- [What Is Amazon FSx for Lustre?](https://docs.aws.amazon.com/fsx/latest/LustreGuide/what-is.html)
- [What Is Amazon FSx for NetApp ONTAP?](https://docs.aws.amazon.com/fsx/latest/ONTAPGuide/what-is-fsx-ontap.html)
- [Volumes](https://kubernetes.io/docs/concepts/storage/volumes/)
- [Storage on Amazon EKS](https://docs.aws.amazon.com/eks/latest/userguide/storage.html)
- [Amazon EBS](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AmazonEBS.html)
- [Amazon EBS Volume Types](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ebs-volume-types.html)
- [AWS EBS CSI Driver Parameters](https://github.com/kubernetes-sigs/aws-ebs-csi-driver/blob/master/docs/parameters.md)
- [What is Amazon Elastic File System?
](https://docs.aws.amazon.com/efs/latest/ug/index.html)
- [aws-efs-csi-driver GitHub Repository](https://github.com/kubernetes-sigs/aws-efs-csi-driver)
- [JMESPath](https://jmespath.org/)
- [AWS Secrets Manager VPC Endpoint](https://docs.aws.amazon.com/secretsmanager/latest/userguide/vpc-endpoint-overview.html)
- [Secret Auto Rotation with Secrets Store CSI Driver](https://secrets-store-csi-driver.sigs.k8s.io/topics/secret-auto-rotation.html)
- [AWS Documentation](https://docs.aws.amazon.com/)
- [How to Use AWS Secrets Configuration Provider with Kubernetes Secrets Store CSI Driver](https://aws.amazon.com/blogs/security/how-to-use-aws-secrets-configuration-provider-with-kubernetes-secrets-store-csi-driver/)
- [SecretProviderClass](https://docs.aws.amazon.com/secretsmanager/latest/userguide/integrating_csi_driver_SecretProviderClass.html)

### AWS Services

- Amazon EBS [Overview](https://aws.amazon.com/documentation-overview/ebs/) - [Documentation](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AmazonEBS.html)
- Amazon EFS [Overview](https://aws.amazon.com/documentation-overview/efs/) - [Documentation](https://docs.aws.amazon.com/efs/)
- Amazon FSx [Documentation](https://docs.aws.amazon.com/fsx/)
- AWS Secrets Manager [Overview](https://aws.amazon.com/documentation-overview/secrets-manager/) - [Documentation](https://docs.aws.amazon.com/secretsmanager/)

## Module 9: Managing Security in Amazon EKS

### Websites

- [Kubernetes Protection / Amazon GuardDuty](https://docs.aws.amazon.com/guardduty/latest/ug/kubernetes-protection.html)
- [Adding Users and Roles to Your Amazon EKS Cluster](https://docs.aws.amazon.com/eks/latest/userguide/add-user-role.html)
- [Managing Users or IAM Roles for Your Cluster](https://docs.aws.amazon.com/eks/latest/userguide/managing-auth.html)
- [IAM Best Practices](https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html#grant-least-privilege)
- [Authorization Overview](https://kubernetes.io/docs/reference/access-authn-authz/authorization/)
- [Using RBAC Authorization](https://kubernetes.io/docs/reference/access-authn-authz/rbac/)
- [Default Roles and Role Bindings](https://kubernetes.io/docs/reference/access-authn-authz/rbac/#default-roles-and-role-bindings)
- [rbac-lookup GitHub Repository](https://github.com/FairwindsOps/rbac-lookup)
- [Changes in Kubernetes 1.24 About ServiceAccounts and Their Secrets](https://itnext.io/big-change-in-k8s-1-24-about-serviceaccounts-and-their-secrets-4b909a4af4e0)
- [Service Account Tokens](https://kubernetes.io/docs/reference/access-authn-authz/authentication/#service-account-tokens)
- [kube-ops-view GitHub Repository](https://github.com/hjacobs/kube-ops-view)
- [amazon-eks-pod-identity-webhook GitHub Repository](https://github.com/aws/amazon-eks-pod-identity-webhook)
- [IAM Roles for Service Accounts](https://docs.aws.amazon.com/eks/latest/userguide/iam-roles-for-service-accounts.html)
- [Restrict Access to IMDS](https://docs.aws.amazon.com/eks/latest/userguide/restrict-ec2-credential-access.html)

### AWS Services

- Amazon GuardDuty [Overview](https://aws.amazon.com/documentation-overview/guardduty/) - [Documentation](https://docs.aws.amazon.com/guardduty/)
- AWS IAM [Overview](https://aws.amazon.com/iam/) - [Documentation](https://docs.aws.amazon.com/iam/)
- Amazon EKS [Overview](https://aws.amazon.com/documentation-overview/eks/) - [Documentation](https://docs.aws.amazon.com/eks/)

## Module 10: Course Wrap-Up

### Websites

- [AWS Certification exam preparation](https://aws.amazon.com/certification/certification-prep/)
- [AWS Certification](https://aws.amazon.com/certification/)
- [AWS Recertification](https://aws.amazon.com/certification/recertification/)
- [All AWS Certification exams](https://aws.amazon.com/certification/exams/)
- [Schedule an Exam](https://aws.amazon.com/certification/certification-prep/testing/)
- AWS Skill Builder [subscription](https://aws.amazon.com/training/digital)
- [AWS Training and Certification](https://aws.amazon.com/training)
- [AWS Online Tech Talks](https://aws.amazon.com/events/online-tech-talks/on-demand/)
- [AWS Ramp-Up Guides](https://aws.amazon.com/training/ramp-up-guides/)

### Courses

- [AWS Skill Builder](https://explore.skillbuilder.aws/learn)
- [AWS Builder Labs](https://aws.amazon.com/training/digital/aws-builder-labs/)
- [AWS Workshops](https://workshops.aws/)
