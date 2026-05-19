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
**Screenshot:**  
<img width="1915" height="964" alt="Screenshot 2026-05-06 133305" src="https://github.com/user-attachments/assets/2651bce5-ba1d-4e0e-a3af-a3335ca5132a" />

<img width="1919" height="979" alt="Screenshot 2026-05-06 133607" src="https://github.com/user-attachments/assets/b539c9df-646c-48ef-be9b-32d46cfcbb3f" />


### Task 2: Add Users to Groups
- Added user-1 to the S3-Support group  
- Added user-2 to the EC2-Support group  
- Added user-3 to the EC2-Admin group  
**Screenshot:**  

<img width="1917" height="967" alt="Screenshot 2026-05-06 133715" src="https://github.com/user-attachments/assets/fee7aa91-bdbf-4681-8947-0683087413b3" />

<img width="1912" height="963" alt="Screenshot 2026-05-06 133734" src="https://github.com/user-attachments/assets/db8e6ccd-499c-4e04-9197-2414c4a7bc52" />

<img width="1916" height="965" alt="Screenshot 2026-05-06 133754" src="https://github.com/user-attachments/assets/ba1fe090-9862-4473-8f16-24f31cf3a6a7" />

<img width="1915" height="964" alt="Screenshot 2026-05-06 133825" src="https://github.com/user-attachments/assets/81909727-a481-4dbf-a655-f2d2628099d7" />


### Task 3: Test IAM User Permissions
- Logged in using IAM sign-in URL  
- Verified S3 access for user-1  
- Verified EC2 read-only access for user-2  
- Verified EC2 administrative access for user-3  
**Screenshot:**  
User-1

<img width="1918" height="966" alt="Screenshot 2026-05-06 135650" src="https://github.com/user-attachments/assets/44bd1029-ce66-4bd3-b990-36cb06f41f51" />

<img width="1918" height="974" alt="Screenshot 2026-05-06 135751" src="https://github.com/user-attachments/assets/d2adad49-df9c-43d4-8bba-454227685f06" />


User-2

<img width="1914" height="953" alt="Screenshot 2026-05-06 140027" src="https://github.com/user-attachments/assets/4fc8cc05-9e34-45c4-ada3-3679444d8519" />


<img width="1919" height="960" alt="Screenshot 2026-05-06 140104" src="https://github.com/user-attachments/assets/74bae7a9-b8e0-4768-af23-288af55204ce" />

User-3


<img width="1912" height="965" alt="Screenshot 2026-05-06 140305" src="https://github.com/user-attachments/assets/adec07b2-e165-4a1b-a85b-88d2f865fa82" />


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
**Name:** Sam Chris M (212224040285)
**Course:** Introduction to Cloud Computing  

