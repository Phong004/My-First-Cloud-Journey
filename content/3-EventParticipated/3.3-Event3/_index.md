---
title: "Cloud Mastery 2026: #2 IaC, K8s & DevOps"
date: 2026-04-04
weight: 3
chapter: false
pre: " <b> 3.3. </b> "
---

### Event Objectives

- Shift the infrastructure management mindset from manual configuration (ClickOps) to full automation using Infrastructure as Code (IaC).
- Provide a comprehensive overview of Cloud Native architecture through the leading container orchestration platform, Kubernetes (K8s).
- Introduce the Elixir programming language and the BEAM virtual machine, optimal solutions for DevOps systems requiring high concurrency and fault tolerance.

### Speakers

- **Thinh Nguyen** - FCAJ Cloud Engineer Trainee.
- **Bao Huynh** - Junior Cloud Native Developer at Endava Vietnam / Founder of ITea Lab.
- **Minh Triet Nguyen Ta** - R&D Member at ITea Lab / SAP Developer Intern.

### Key Highlights

#### Infrastructure as Code (IaC) with Terraform
- **From ClickOps to Code:** Analyzed manual configuration drawbacks such as slow speed, human error, and collaboration difficulties.
- **Terraform Workflow:** Introduction to basic commands (`init`, `plan`, `apply`, `destroy`) and resource state management via the `terraform.tfstate` file.
- **Practical Simulation:** Utilized LocalStack to emulate AWS environments locally and demonstrated advanced Terraform directory structures divided by modules and environments (dev/prod).

#### Cloud Native Architecture with Kubernetes (K8s)
- **K8s Architecture:** Delved into the Control Plane and Worker Nodes, explaining the operations of kube-apiserver, etcd, and kubelet.
- **Managing Kubernetes Objects:** Clarified the functions of Pods, Deployments, Services, ConfigMaps, and specifically how K8s handles Secrets.
- **Tooling Ecosystem:** Introduced Helm for application packaging (Charts) and K9s for direct cluster monitoring via the terminal.

#### Elixir and the "Let It Crash" Philosophy in DevOps
- **The Power of BEAM VM:** Explained how Elixir runs on the BEAM virtual machine, allowing systems to handle millions of lightweight processes efficiently without consuming excess resources.
- **Fault-Tolerance:** Explored the Supervisor mechanism for monitoring and automatically restarting failed processes, ensuring high availability.

### Key Takeaways

#### Technical Mindset
- Mastered automated infrastructure deployment workflows, eliminating configuration drift risks across environments.
- Gained a clear understanding of container orchestration for managing large-scale microservice systems.

#### Security Awareness
- **Risk of Sensitive Data Exposure:** Identified risks from `terraform.tfstate` files which, if not properly secured, may contain secrets in plaintext.
- **K8s Configuration Vulnerabilities:** Realized that K8s Secrets are only Base64 encoded by default rather than securely encrypted, requiring specialized secret management solutions like HashiCorp Vault.

### Applying to Work

- **Optimizing Pentest Workflow:** Applied IaC principles to build rapid and consistent attack/defense lab scenarios for the *FPT Event Management System* project.
- **Container Environment Testing:** Knowledge of K8s allows for building new test cases targeting RBAC (Role-Based Access Control) configurations and container escape possibilities in Cloud Native environments.
- **Advancing Red Team Mindset:** Understanding Elixir's "Let It Crash" philosophy revealed new attack surfaces within fault-tolerant logic, enabling the design of simulated attacks that target application-layer logic more deeply than traditional network-layer attacks.

### Event Experience

The event took place at the 26th floor of the Bitexco tower, providing a dynamic and highly technical space for technology discussions.

#### Bridging Theory and Practice
- Live demos of LocalStack and Terraform helped transform theory into practical lessons, making it easy to visualize how AWS services interact under the hood.

#### Lessons Learned
- To become an elite Pentester on the Cloud, understanding how Builders construct infrastructure through code (IaC) and orchestrate systems (K8s) is mandatory. Understanding the "infrastructure's source code" is the fastest way to find a system's weaknesses.

#### Proof of Participation

![Cloud Mastery 2026 #2](/images/3-EventParticipated/event-image-3.3.jpg)

> In conclusion, the "Cloud Mastery #2" event not only provided a solid knowledge foundation in Cloud Native architecture but also helped me recognize new security risks in infrastructure management, directly supporting my career trajectory in Information Assurance.