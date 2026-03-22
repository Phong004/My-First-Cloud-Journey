---
title: "Week 1 Worklog"
date: 2026-01-11
weight: 1
chapter: false
pre: " <b> 1.1. </b> "
---

### Week 1 Objectives:
* Get familiar with the First Cloud Journey (FCJ) project workflow.
* Build a foundational understanding of the Cloud environment; master AWS administration via both the web interface (Console) and command line (AWS CLI).
* Apply basic security principles right from account creation (IAM management, setting up Billing/Budgets for cost control).

### Tasks Implemented During the Week:

| Day | Task | Start Date | Completion Date | Resource / Material |
| :--- | :--- | :--- | :--- | :--- |
| Mon | - Familiarized with FCJ members and the working environment.<br> - Reviewed internship rules, regulations, and project deployment guidelines. | 05/01/2026 | 05/01/2026 | [FCJ Rules & Instructions](https://rules.fcjuni.com/) |
| Tue | - Researched AWS Whitepapers at the library.<br> - Learned foundational Cloud Computing concepts and deployment models (IaaS, PaaS, SaaS).<br> - Self-studied essential Cloud infrastructure components (Compute, Network, Storage, Database). | 06/01/2026 | 06/01/2026 | [Explore AWS Services](https://cloudjourney.awsstudygroup.com/1-explore/) |
| Wed | - Created a secure AWS Free Tier account.<br> - Installed and configured AWS CLI locally.<br> - **Practice:** Set up secure Access/Secret Keys, configured default Region, and tested basic CLI commands. | 07/01/2026 | 07/01/2026 | [Explore AWS Services](https://cloudjourney.awsstudygroup.com/1-explore/) |
| Thu | - Deep dive into Amazon EC2: Differentiated between Instance types and AMIs, explored EBS storage mechanisms, and configured basic Security Groups.<br> - Learned about secure remote protocols (SSH) into EC2. | 08/01/2026 | 09/01/2026 | [Explore AWS Services](https://cloudjourney.awsstudygroup.com/1-explore/) |
| Fri | - **Practice:** Launched a Linux EC2 instance via the Console.<br> - Created a Key Pair and successfully established an SSH connection from the local terminal.<br> - Attached and formatted an additional EBS volume to the instance. | 09/01/2026 | 09/01/2026 | [Explore AWS Services](https://cloudjourney.awsstudygroup.com/1-explore/) |

### Week 1 Achievements:

* Gained an overview of the AWS ecosystem and understood the roles of core services through self-study.
* Successfully created an AWS Free Tier account and understood basic cost control principles.
* Successfully configured AWS CLI with security standards (Region, Access/Secret Key) for automation tasks.
* Proficiently used AWS CLI to execute core administrative tasks:
  * Checked configuration and account identity (`aws sts get-caller-identity`).
  * Queried regions and active services.
  * Managed Key Pair lifecycles.
* Completed hands-on lab: Launched a Linux EC2, configured secure SSH rules in Security Groups, connected via terminal, and mounted an EBS volume.