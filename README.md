# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
* The MSP faced significant compliance risks due to the absence of a structured access management process. As a result, employees were frequently granted inappropriate levels of access, increasing the likelihood of unauthorized exposure to sensitive data. This lack of governance introduced HIPAA compliance risks and increased the organization's exposure to significant regulatory fines and penalties. To address these risks, the company required a formal, streamlined, and scalable access control process to ensure compliance and strengthen security oversight.
  
## Solution Overview
* I designed and implemented a new Active Directory domain, organizing users and resources through Organizational Units (OUs) aligned to each department. Employees were placed into the appropriate OU based on their role, improving administrative efficiency and simplifying user management. Security groups were then created and assigned according to job responsibilities, ensuring employees received the appropriate level of access. A flat Role-Based Access Control (RBAC) model was implemented, with permissions managed through group membership rather than individual user assignments. This approach streamlined user provisioning, strengthened security, and helped ensure users had access only to the resources necessary to perform their job functions.

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
