# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
* The MSP faced significant compliance risks due to the absence of a structured access management process. As a result, employees were frequently granted inappropriate levels of access, increasing the likelihood of unauthorized exposure to sensitive data. This lack of governance created potential HIPAA compliance violations and exposed the organization to substantial regulatory fines and penalties. To mitigate these risks, the company required a formal, streamlined, and scalable access control process to ensure compliance and strengthen security oversight.

## Solution Overview
* I created a new Active Directory domain and organized the environment using Organizational Units (OUs) for each department. Employees were placed into the appropriate OU based on their role within the company, making user management more organized and efficient. I then created security groups and assigned users according to their job responsibilities to ensure they received the correct level of access. Using a flat Role-Based Access Control (RBAC) model, permissions were managed through group membership rather than individual user assignments. This approach improved security, simplified user provisioning, and helped ensure employees had access only to the resources needed to perform their jobs.

## Video Walkthrough
[Add your video walkthrough link placeholder here. You will record this tomorrow and update this link so visitors can see a live demonstration of your lab environment.]

## Tools Used
* Windows Server
* Active Directory Domain Services
* VirtualBox
* UTM
* RBAC
* GitHub

## Project Timeline
* Day 1: Domain creation and domain controller promotion
* Day 2: Organizational unit and security group design
* Day 3: User provisioning and RBAC implementation
* Day 4: Incident response and resolution (NMG-0047)
* Day 5: Documentation and case study packaging

## Key Accomplishments
* Built NMG.com domain from scratch
* Helped the MSP be HIPPA compliant
* Implemented a more structured Access Control System
