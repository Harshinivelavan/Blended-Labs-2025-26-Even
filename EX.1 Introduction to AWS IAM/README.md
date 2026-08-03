# Lab 1 - Introduction to AWS Identity and Access Management (IAM)

## Title
Introduction to AWS Identity and Access Management (IAM)


## Objective
The objective of this lab is to understand how AWS Identity and Access Management (IAM) controls authentication and authorization in AWS. The lab focuses on exploring IAM users and groups, analyzing attached policies, assigning users to appropriate groups based on organizational roles, and validating permissions by testing service access.


## Prerequisites
- Basic understanding of cloud computing concepts  
- AWS Academy Lab access  
- Web browser with internet connectivity  


## Tools Used
- AWS Management Console  
- AWS Identity and Access Management (IAM)  
- Amazon EC2  
- Amazon S3  


## Tasks Performed

### Task 1: Explore IAM Users and Groups
- Reviewed pre-created IAM users: user-1, user-2, user-3  
- Explored IAM groups: EC2-Admin, EC2-Support, S3-Support  
- Inspected managed and inline policies attached to groups  

<img width="1913" height="931" alt="Screenshot 2026-08-03 160914" src="https://github.com/user-attachments/assets/5bc24b58-d319-422f-8e70-d97f56093acf" />

<img width="1917" height="928" alt="Screenshot 2026-08-03 161033" src="https://github.com/user-attachments/assets/04fbc5e5-ad52-4739-b30b-d8c8a94a35c4" />

<img width="1917" height="872" alt="Screenshot 2026-08-03 161107" src="https://github.com/user-attachments/assets/5baf2b5f-5f86-4e16-81f2-7f7d8cc4cfbd" />




### Task 2: Add Users to Groups
- Added user-1 to the S3-Support group  
- Added user-2 to the EC2-Support group  
- Added user-3 to the EC2-Admin group  

<img width="1903" height="943" alt="Screenshot 2026-08-03 162840" src="https://github.com/user-attachments/assets/4d190f9f-9937-4a55-a82a-4928e40d9588" />


### Task 3: Test IAM User Permissions
- Logged in using IAM sign-in URL  
- Verified S3 access for user-1  
- Verified EC2 read-only access for user-2  
- Verified EC2 administrative access for user-3  


<img width="1907" height="1000" alt="Screenshot 2026-08-03 165706" src="https://github.com/user-attachments/assets/e61619dc-c73b-4ae1-8305-1aa682a67b7a" />


## Workflow
1. Accessed IAM console and reviewed users and groups.  
2. Inspected policy permissions attached to groups.  
3. Assigned users to groups based on their roles.  
4. Logged in as each IAM user using the sign-in URL.  
5. Validated permissions by accessing AWS services.  


## Learning Outcomes
- Understood the role of IAM in AWS security.  
- Learned how IAM users, groups, and policies interact.  
- Gained practical experience implementing role-based access control.  
- Verified permission enforcement through real-time service testing.  


## Conclusion
This lab provided hands-on experience with AWS IAM by demonstrating how organizations manage secure access to cloud resources. Assigning users to groups with predefined policies simplified permission management and ensured role-based access control across AWS services.


## Author
**Name:** Harshini V Reg No: 212224040109
**Course:** Introduction to Cloud Computing  

