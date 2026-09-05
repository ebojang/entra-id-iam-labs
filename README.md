# Week 1 IAM Lab - Joiner, Mover, Leaver (JML) Process

## Project Overview

This lab simulates a real-world Identity and Access Management (IAM) Joiner, Mover, and Leaver (JML) process using Microsoft Entra ID.

The objective was to demonstrate how user identities and access permissions are managed throughout an employee's lifecycle while ensuring security, compliance, and proper access governance.

## Scenario
Organisation: **Ebrima.com**

Departments:
- Human Resources (HR)
- Finance
- IT
- Sales
  
This lab follows the lifecycle of an employee named **Abdi Qani** from onboarding through departmental transfer and eventual offboarding.

Lab Objectives

✅ Create and manage security groups
✅ Manage user accounts
✅ Assign group memberships
✅ Assign and remove Microsoft 365 licenses
✅ Perform Joiner processes
✅ Perform Mover processes
✅ Perform Leaver processes
✅ Verify access changes
✅ Document audit evidence

Environment Configuration
## Security Groups Created

| Group Name | Purpose |

| HR-Team | Human Resources Access |
| Finance-Team | Finance Department Access |
| IT-Admins | Administrative Access |
| Contractors | Temporary Worker Access |

Step 1: Create Security Groups
 
Created departmental security groups to support role-based access management.
 
## Actions Performed
- Created HR-Team
- Created Finance-Team
- Created IT-Admins
- Created Contractors

  ##Evidence
  ### Group Overview
<img width="1874" height="914" alt="Screenshot 2026-09-05 145651" src="https://github.com/user-attachments/assets/82d01c90-58f6-4ea8-911d-32b86ec1fc51" />
<img width="1837" height="744" alt="image" src="https://github.com/user-attachments/assets/786d1c69-b8d8-442b-be3b-7cc48ad68c80" />


# Step 2: Create Existing Employees

Created users representing employees across multiple business functions and assigned them to the relevant security groups.
 
## Actions Performed
- Created employee accounts
- Assigned departments
- Added users to appropriate groups
## Evidence
### Employee Accounts
<img width="1260" height="884" alt="image" src="https://github.com/user-attachments/assets/36e75726-3e42-4caf-8246-da2bee950705" />

### Group Membership Assignments
### Evidence
<img width="1420" height="570" alt="image" src="https://github.com/user-attachments/assets/74b4bbc0-95f8-42a7-a9b8-f8d7b5d90e0f" />


# JOINER PROCESS
A new employee, **Abdi Qani**, joins the Finance department.
### Actions Performed

1. Created user account
2. Assigned department = Finance
3. Added user to Finance-Team
4. Assigned Microsoft 365 License
5. Verified successful sign-in

### Finance Group Assignment
<img width="1844" height="331" alt="Screenshot 2026-09-05 151852" src="https://github.com/user-attachments/assets/e15102fb-a06a-4d42-b4f3-e45f8db7bd6b" />

### License Assignment and Signed-in verification
<img width="1900" height="491" alt="Screenshot 2026-09-05 151551" src="https://github.com/user-attachments/assets/2660b272-3d91-47a0-87b9-0753376a2f42" />

# MOVER PROCESS
Abdi Qani transfers from Finance to HR.
### Actions Performed
1. Removed Finance-Team membership
2. Added HR-Team membership
3. Updated department information
4. Verified access changes

## Evidence
<img width="952" height="245" alt="image" src="https://github.com/user-attachments/assets/e2f7435f-b56e-4a30-a50f-bbe7a4e165c5" />

# LEAVER PROCESS 
Abdi Qani leaves the organisation.

### Actions Performed
1. Blocked account sign-in
2. Revoked active sessions
3. Removed group memberships
4. Removed assigned licenses
5. Verified account deprovisioning

## Evidence 
<img width="973" height="634" alt="Screenshot 2026-09-05 152146" src="https://github.com/user-attachments/assets/1630c828-52fd-45c5-bdf2-e8761045eb0f" />

## Account Deprovisioned 
<img width="395" height="569" alt="image" src="https://github.com/user-attachments/assets/0430ddd8-6d28-4359-a2b4-0c1703d621cc" />

# Evidence Checklist

| Requirement | Completed 
| Security Groups Created | ✅ |
| Users Created | ✅ |
| Group Membership Assigned | ✅ |
| License Assigned | ✅ |
| Joiner Process Completed | ✅ |
| Mover Process Completed | ✅ |
| Leaver Process Completed | 
| Before and After Screenshots | ✅ |
| Access Removed | ✅ |
| Account Disabled/deleted | ✅ |
| License Reclaimed | ✅ |


# Lessons Learned
This project provided hands-on experience with managing user identities throughout their lifecycle. It reinforced the importance of timely access provisioning, role changes, and secure offboarding processes to reduce security risks and maintain compliance.





