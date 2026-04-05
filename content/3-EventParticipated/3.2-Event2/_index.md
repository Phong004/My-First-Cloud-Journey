---
title: "Cloud Mastery 2026: #1 AI From Scratch"
date: 2026-03-14
weight: 2
chapter: false
pre: " <b> 3.2. </b> "
---

### Event Objectives

- Equip attendees with foundational and advanced knowledge of Prompt Engineering to optimize token costs and mitigate hallucination phenomena when working with AI.
- Understand the methodology of building AI Agents, specifically Strands Agents, with capabilities for autonomous planning and interaction with external tools.
- Explore Artificial Intelligence of Things (AIoT) application models through real-world projects deployed on the AWS Cloud platform.

### Speakers

- **Le Hoang Dinh** - AI Engineer.
- **Banh Cam Vinh** - Data Engineer.
- **Nguyen Tuan Thinh** - DevOps Engineer.

### Key Highlights

#### Automated Prompt Engineering
- **Token Economics:** Analyzed the actual costs of utilizing LLMs. For instance, Claude Opus's output cost is five times higher than its input ($25.00 vs. $5.00 per 1 million tokens). Writing generic prompts leads to massive resource waste.
- **7 Core Principles:** Emphasized using Delimiters, focusing on DOs rather than DON'Ts, and allowing the model to respond with "I don't know" to prevent Hallucination.

#### Building AI Agents (Strands Agent)
- Introduced the concept of AI Agents with multi-step reasoning capabilities and the Agent-as-tools protocol, which facilitates collaboration among Agents.
- Explored the Agentic Loop for executing tool calls (APIs, Databases) and Knowledge Base integration.

#### AIoT Ecosystem on AWS Cloud
- **Locker Management Project:** Demonstrated an automated locker management system utilizing edge devices (Arduino, Raspberry Pi) communicating via an MQTT Broker.
- Showcased the architecture integrating AWS IoT Core with AWS Rekognition for facial recognition and AWS Lambda for automated logic processing.

### Key Takeaways

#### Technical Mindset
- Mastered the structure of a standard prompt, comprising 7 components: Role, Instruction, Context, Input Data, Output Format, Examples, and Constraints.
- Understood the paradigm shift from purely interactive AI to autonomous AI (Agents) capable of manipulating the physical world via APIs.

#### Security Awareness
- The process of AI Agents calling system APIs and fetching real-time data introduces a massive security risk (Attack Surface). Without strict Identity and Access Management (IAM) controls, hackers can utilize Prompt Injection to deceive Agents into executing malicious code.

### Applying to Work

- **Optimizing Pentest Workflow:** Applying advanced techniques like Chain-of-Thought (CoT) to leverage LLMs in writing vulnerability exploitation scripts and automatically synthesizing the "Penetration Test Report" for the FPT Event Management System project.
- **IoT & Cloud Security:** Insights from the Locker Management project clarified the communication flow between IoT devices and the AWS Cloud, enabling me to construct test cases evaluating internal network configurations and the API Gateway.
- **Expanding Red Teaming:** Further researching Strands Agents to program autonomous agents that assist in target information gathering (Reconnaissance) during future simulated attack campaigns.

### Event Experience

The event, held at the 26th Floor of the Bitexco tower, provided an incredibly inspiring space for learning and working in an office environment.

#### Delving into Coding Discipline
- Understanding output/input costs (Token Economics) served as a stern reminder: In a Cloud environment, a loosely written command doesn't just cause logic errors but also results in direct financial damage.

#### Proof of Participation

![Cloud Mastery 2026](/My-First-Cloud-Journey/images/3-EventParticipated/0S0A0016.jpg)

> Overall, the "Cloud Mastery 2026" event not only provided a solid knowledge foundation in GenAI but also helped me recognize new security risks in the era of autonomous AI, directly supporting my career trajectory in Information Assurance.