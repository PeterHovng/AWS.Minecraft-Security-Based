---
title: "Week 7 Worklog"
date: 2024-01-01
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---

### Week 7 Objectives

* Understand IAM roles for EC2 and why they are safer than access keys.
* Practice instance profile assignment and temporary credentials.
* Access AWS resources from EC2 without hardcoded credentials.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | ---------- | --------------- | ----------------------------------------- |
| 2 | - Review risks of long-term access keys<br>- Compare IAM user access keys vs instance roles | 08/11/2025 | 08/11/2025 | AWS IAM documentation |
| 3 | - Create an IAM role for EC2<br>- Attach S3 access permissions<br>- Review trust policy | 08/12/2025 | 08/12/2025 | AWS IAM console |
| 4 | - Attach the role to an EC2 instance<br>- Verify temporary credentials metadata | 08/13/2025 | 08/13/2025 | EC2 instance metadata docs |
| 5 | - Access S3 from EC2 using the role<br>- Test read/write operations<br>- Verify no static keys exist in code | 08/14/2025 | 08/15/2025 | AWS SDK examples |
| 6 | - Review cleanup steps for roles and instance profiles<br>- Document role best practices | 08/15/2025 | 08/15/2025 | AWS IAM best practices |

### Week 7 Achievements

* Learned why IAM roles are preferred over long-term access keys for EC2.
* Created an IAM role and attached it to an EC2 instance.
* Successfully accessed AWS resources from EC2 without hardcoded credentials.
* Verified temporary credential behavior using instance metadata.
* Documented role-based access best practices.
* ...