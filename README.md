# 💰 Cloud Custodian Example Policies

This repository contains a curated set of Cloud Custodian policies focused on identifying cost saving opportunities across major areas of cloud infrastructure. These policies are designed to be **plug-and-play**—ready to deploy in your environment with minimal customization.

## 🎯 Objectives

- Make Cloud Custodian quicker to implement without of the box policies
- Reduce unnecessary cloud spend across services like Compute, Storage, Database, Logging, Networking, AI/ML, and more
- Provide guardrails to enforce cost-conscious resource provisioning and lifecycle management
- Enable automated scheduling and cleanup actions
- Establish consistent governance for cloud savings

## 📦 Structure

The repository is organized into directories based on functional domains of cloud cost optimization:

- Compute: Policies targeting virtual machines, auto-scaling groups, etc.
- Storage: Identify waste in volumes, buckets, snapshots, and more
- Database: Optimize database engines, clusters, and backups
- Logging / Data / Backup: Detect excessive log retention, stale backups, and redundant copies
- Networking: Address unused IPs, over-provisioned load balancers, and excessive traffic flows
- Data Transfer: Highlight costly cross-region or cross-zone data movement
- Scheduling: Automate start/stop cycles for non-critical resources
- AI / ML: Detect idle or oversized AI and ML workloads
- Guardrails: Prevent expensive misconfigurations and enforce cost-related policies
```
├── compute/
├── storage/
├── database/
├── logging-data-backup/
├── networking/
├── data-transfer/
├── scheduling/
├── ai-ml/
└── guardrails/
```
## 🛡️ Governance Benefits

These policies serve not only to optimize cost but also to enforce good practices around:
- Tag compliance
- Lifecycle management
- Resource right-sizing
- Decommissioning unused assets
- 
## 🔧 Requirements

- [Cloud Custodian](https://cloudcustodian.io/) installed
- Cloud credentials with read and write permissions to target services
- Optional: AWS CLI, Azure CLI, or GCP SDK (depending on your cloud provider)

Install Cloud Custodian:

```bash
pip install c7n
```
## 🙌 Contributions

Contributions are welcome! Please feel free to submit:
- New policies in any of the supported domains
- Enhancements to existing rules
- Suggestions for new areas of coverage
- Documentation improvements
