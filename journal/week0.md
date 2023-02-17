# Week 0 — Billing and Architecture

## Required Work:

- Completed all the required work.

### Create IAM user

Following best practice and using IAM user with admin and billing policies attached instead of root account. MFA enabled for user account.

![IAM-user](assets/week0-user.png)
![admin-billing](assets/week0-adminbilling.png)

### Conceptual Design

![conceptual-diagram](assets/week0-conceptual-diagram.png)

High level Architecture design for all stakeholders.

### Logical Architecture Design

![main-diagram](assets/week0-logical-diagram-main.png)

Detailed design of the architecture for the technical team.

### Create Budget And Billing Alarm

![budget](assets/budget-aws.png)
Created budget.

![billing-alert](assets/week0-billing-alert.png)
Created billing alert.

## Challenges:

- Reviewed all the questions of each pillars in the Well Architected Tool

### Pipeline Logical Design

![pipeline-diagram](assets/week0-logical-diagram-pipeline.png)

## Obstacles:

I played with cloudtrail and used alot of the S3 free tier resources but I was notified because of the budget and billing alarm.
