# IAM-Portfolio-Project

<h3>This is my first portfolio project as a cloud engineer. </h3>
<p> In this portfolio projects, my attempt is to demonstrate my knowledge of IAM in AWS, and how to fully utilize it's features and security measures. Any and all scenarios in this text are fictional, and any resemeblence to any scenario is unintentional 
For this project we are going to be examining the issues in the workplace when it comes to incorrectly using the IAM service in AWS. This features covers all aspects of roles, groups, and users in the AWS cloud service. Improperly using it can be detrimental to your business, it's reputation, it's revenue,and much more. To ensure I maximized the full potential of securing this company's IAM resources, I will be referencing the AWS Services and policies many times, as well as their best practices. Thank you for looking. </p>

<h2>Scenario:</h2>
<p>You are a Cloud Engineer Consultant, working with StartupCo, a fast-growing tech startup that recently launched their first product - a fitness tracking application.

They've been using AWS for three months, initially setting up their infrastructure quickly to meet launch deadlines.

Now that their product is live, they need to address their cloud security fundamentals.  The company has 10 employees who all currently share the AWS root account credentials to access and manage their cloud resources.

This practice started when they were moving quickly to launch, but now their CTO recognizes the security risks this poses.

<h2>Current Setup</h2>

Everyone uses the root account

No separate permissions for different teams

No MFA or password policies

AWS credentials shared via team chat

<h3>Current Infrastructure</h3>:

EC2 instances running their application

S3 buckets storing user data and application assets

RDS database for user information

CloudWatch for monitoring

Several development and production environments

<h3>Team Structure & Access Needs</h3> 

  4 Developers (need EC2 and S3 access)

 2 Operations (need full infrastructure access)

 1 Finance Manager (needs cost management access)

 3 Data Analysts (need read-only access to data resources)


</p>
