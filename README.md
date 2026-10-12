# Hi, I'm Eranda Welgama 👋

**Cloud & Infrastructure Engineer**  
AWS · Microsoft Azure · Microsoft 365 · Infrastructure as Code · Automation

I build, secure, and troubleshoot cloud and hybrid infrastructure, working across cloud platforms, Linux, networking, and identity. My focus is reliable operations, practical automation, and clear documentation.

This profile brings together my **independent personal labs**, with code, architecture decisions, and validation evidence.

## Featured projects

### [AWS Serverless Page CI/CD](https://github.com/reranda/aws-serverless-page-cicd)

**AWS Lambda · API Gateway · Terraform · GitHub Actions · OIDC · CloudWatch · SNS**

An end-to-end serverless delivery lab that publishes a version-controlled HTML page through API Gateway and Lambda, with infrastructure provisioned in Terraform and deployments orchestrated through GitHub Actions.

- **Architecture:** API Gateway HTTP API, packaged Python Lambda and HTML, separate bootstrap/application Terraform state, and CloudWatch observability.
- **Secure delivery:** GitHub OIDC credentials, scoped plan and deploy IAM roles, CI validation, and saved-plan application with release commit verification.
- **Lifecycle evidence:** Verified HTML updates, rollback, recovery after resource deletion, CloudWatch/SNS email alerts, and guarded application teardown.
- **Cleanup:** Full project-specific infrastructure and versioned Terraform state bucket removed after testing. The demo endpoint is intentionally **offline**; the code and validation history remain available.

[Explore the code](https://github.com/reranda/aws-serverless-page-cicd) · [Validation record](https://github.com/reranda/aws-serverless-page-cicd/blob/main/docs/validation.md) · [Successful release](https://github.com/reranda/aws-serverless-page-cicd/actions/runs/38148490686)


### [Terraform AWS CI/CD Lab](https://github.com/reranda/terraform-aws-cicd-lab)

**Terraform · AWS · GitHub Actions · OIDC · TFLint · Checkov**

An AWS lab demonstrating repeatable infrastructure delivery with temporary credentials, automated checks, and explicit deployment controls.

- **Infrastructure:** A VPC spanning two Availability Zones, public and private subnets, and an encrypted, versioned S3 data bucket.
- **Authentication and state:** GitHub OIDC with short-lived AWS credentials, plus a separate S3 backend with versioning and native state locking.
- **Delivery controls:** Terraform validation, TFLint, and Checkov in CI; manual deployment from a saved plan; and a separate destroy workflow requiring confirmation.
- **Validation:** Documented deployment, zero-change plans, teardown, backend preservation, clean redeployment, and recovery from a partial apply failure.

[Explore the code](https://github.com/reranda/terraform-aws-cicd-lab) · [Architecture](https://github.com/reranda/terraform-aws-cicd-lab/blob/main/docs/architecture.md) · [Validation record](https://github.com/reranda/terraform-aws-cicd-lab/blob/main/docs/validation.md)

## ☁️ Core Technologies

| Area | Technologies |
| --- | --- |
| Cloud platforms | AWS, Microsoft Azure, Google Cloud |
| AWS services | VPC, EC2, S3, IAM, Lambda, CloudWatch |
| Infrastructure as Code | Terraform, OpenTofu, AWS CDK |
| Automation and CI/CD | Bash, PowerShell, GitHub Actions |
| Microsoft cloud and security | Microsoft 365, Entra ID, Intune, Microsoft Defender, Conditional Access |
| Systems and networking | Linux, Windows, TCP/IP, DNS, VPNs, firewalls, identity and access management |

## 🛠️ What I Work On

- Cloud and hybrid infrastructure architecture and implementation
- Infrastructure as Code and deployment automation
- Secure cloud networking and remote access
- Microsoft 365 administration and endpoint management
- Cloud security, hardening, and access control
- Linux operations and scripting
- Infrastructure troubleshooting and root-cause analysis

## Engineering approach

I aim for infrastructure that is secure by design, repeatable through code, and practical to operate. I document decisions and trade-offs, verify changes, and investigate failures to address their root causes.

## Current focus

Expanding my independent labs in AWS architecture, Terraform and OpenTofu, infrastructure automation, and cloud security, alongside building my personal cloud engineering portfolio website.
