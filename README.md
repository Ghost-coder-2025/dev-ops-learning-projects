# DevOps Learning Projects

A collection of hands-on DevOps projects to build practical cloud and infrastructure skills. Each project focuses on real-world scenarios and industry-standard tools.

## About

This repository documents my journey learning DevOps engineering through practical projects from [roadmap.sh](https://roadmap.sh/devops). Each project is deployed on AWS and follows infrastructure-as-code principles.

## Projects

| # | Project | Description | Tech Stack | Status |
|---|---------|-------------|------------|--------|
| 01 | [Server Stats Monitor](./01-server-stats-monitor) | Real-time server monitoring with CloudWatch alerting | Python, AWS (EC2, CloudWatch, SNS), Terraform | 🚧 In Progress |
| 02 | [Log Archive Tool](./02-log-archive-tool) | Automated log compression and archival system | Bash, Cron, S3 | ⏳ Planned |
| 03 | [Nginx Log Analyzer](./03-nginx-log-analyzer) | Parse and analyze web server logs | Python, Bash | ⏳ Planned |
| 04 | [Configuration Backup](./04-server-configuration-backup) | Automated system configuration backups | Bash, Git, S3 | ⏳ Planned |
| 05 | [Backup Solution](./05-automated-backup-solution) | Multi-server backup automation | Python, Terraform, S3 | ⏳ Planned |
| 06 | [CI/CD Pipeline](./06-ci-cd-pipeline) | Automated build, test, and deployment pipeline | GitHub Actions, Docker, AWS | ⏳ Planned |
| 07 | [Infrastructure Monitoring](./07-infrastructure-monitoring) | Full-stack monitoring with Prometheus and Grafana | Prometheus, Grafana, Docker | ⏳ Planned |
| 08 | [Container Deployment](./08-container-deployment) | Kubernetes cluster setup and application deployment | Docker, Kubernetes, Helm | ⏳ Planned |

## Tech Stack

**Cloud Platform:** AWS (EC2, VPC, S3, CloudWatch, SNS, IAM)

**Infrastructure as Code:** Terraform

**Containerization:** Docker, Kubernetes

**CI/CD:** GitHub Actions, Jenkins

**Monitoring:** CloudWatch, Prometheus, Grafana

**Scripting:** Python, Bash

**Version Control:** Git, GitHub

## Getting Started

Each project folder contains:
- Detailed README with setup instructions
- Source code (scripts, configurations)
- Infrastructure as Code (Terraform)
- Documentation

### Prerequisites
- AWS account (Free Tier)
- AWS CLI configured
- Terraform installed
- Docker installed (for container projects)
- Basic knowledge of Linux, networking, and cloud concepts

## Learning Goals

- Design and deploy cloud infrastructure on AWS
- Write Infrastructure as Code with Terraform
- Build CI/CD pipelines for automated deployments
- Implement monitoring and alerting solutions
- Work with containers and orchestration
- Practice DevOps security best practices
- Develop automation scripts for common tasks

## Project Approach

For each project, I:
1. Build the basic solution following roadmap.sh
2. Deploy it on AWS infrastructure (not just locally)
3. Add Infrastructure as Code with Terraform
4. Implement monitoring and alerting
5. Document everything clearly
6. Apply security best practices

## Resources

- [roadmap.sh DevOps Path](https://roadmap.sh/devops)
- [AWS Documentation](https://docs.aws.amazon.com/)
- [Terraform Documentation](https://www.terraform.io/docs)
- [Docker Documentation](https://docs.docker.com/)

## License

MIT License - This is a learning project, feel free to use it for your own learning.

---

⭐ If you find this helpful for your own DevOps learning journey, feel free to star the repo!
