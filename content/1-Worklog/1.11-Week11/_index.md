---
title: "Week 11 Worklog"
date: 2024-01-01
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

### Week 11 Objectives

* Design the AWS architecture for the graduation project: AWS + Minecraft + Cyber Security.
* Deploy the foundational infrastructure: VPC, EC2, GuardDuty, Lambda, Backup, NLB, and Global Accelerator.
* Deliver a runnable Minecraft server with basic security monitoring.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | ---------- | --------------- | ----------------------------------------- |
| 2 | - Review project goals and cost estimate<br>- Draw the architecture diagram<br>- Define required AWS services | 08/11/2025 | 08/11/2025 | Architecture design notes |
| 3 | - Create VPC `Minecraft-Security-Lab`<br>- Create subnets and route tables<br>- Create security groups that allow only port 25565 | 08/12/2025 | 08/12/2025 | AWS VPC documentation |
| 4 | - Launch an Ubuntu EC2 instance<br>- Install Minecraft server via Session Manager<br>- Run Minecraft as the `minecraft` user | 08/13/2025 | 08/13/2025 | AWS Systems Manager docs |
| 5 | - Enable GuardDuty<br>- Review findings, settings, and alert concepts<br>- Document threat detection logic | 08/14/2025 | 08/15/2025 | AWS GuardDuty guides |
| 6 | - Create Lambda `Minecraft-Automated-Block-IP`<br>- Grant EC2 permissions<br>- Create an EventBridge rule from GuardDuty to Lambda | 08/15/2025 | 08/15/2025 | AWS Lambda and EventBridge docs |

### Week 11 Achievements

* Designed a clear AWS architecture for the graduation project.
* Deployed VPC, EC2, and Minecraft server with security-first settings.
* Enabled GuardDuty and connected it to an automation Lambda function.
* Created an hourly backup plan for EC2.
* Made the Minecraft server reachable via Global Accelerator.
* ...