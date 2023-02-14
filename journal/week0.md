# Week 0 — Billing and Architecture


## Creating an AWS account
Week 0 I began by creating a new AWS account. The great thing about creating a new AWS account was that I had AWS Free Tier which enables customers the opportunity to explore and trial out AWS services free of charge to specified limits for each service. When an account goes over the free tier limit, the standard AWS service rates will be billed to your credit card.

## Budget and CloudWatch Alarm

I created an alarm using Amazon CloudWatch billing Alarm to monitor my estimated charges. I set the budget to 5 USD so if I use any services that are more expensive than 5 USD I will recieve an alert via email.

## MFA for my Root Account

I enabled MFA (Multi-factor authentication) for my root account. This provides my account with extra layer of authentication. As a best practice, it is important to protect your root user credentials and only use it for a few tasks rather than everyday tasks. 




# Architectural design (Conceptual and logical).


Below i have posted the link for the architectual design of my microbloggin app. I used the lucidCharts app which helped me recreate a logical design.

 The requirements of this app will include 
 
 - frontend in JS (Javascript) and backend in Python. 

 - API BASED

 - Low cost solution

 - Utilise free tier 

 Please click the link below to view the diagram.


https://lucid.app/lucidchart/e0b945e9-673f-4602-b79e-486d54d2ba91/edit?viewport_loc=-153%2C49%2C1544%2C911%2C0_0&invitationId=inv_4fb47ab1-40a6-44a5-a2bb-abd4f0c97a3b

