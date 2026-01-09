## Environment
- Windows Server 2019 (Domain Controller)
- Windows 11 (Domain-joined client)
- VirtualBox internal network

## Objective
Design a realistic Active Directory OU structure to support
user lifecycle management, access control, and Group Policy enforcement.

### Phase 1 – OU Design
Created a structured OU hierarchy to support role-based access,
Group Policy application, and clean user lifecycle management.
This mirrors real-world environments where new structure is
introduced without disrupting existing objects.

![Active Directory OU Structure](OU-Structure.png)

## Phase 2 – Security Groups
Created role-based security groups to support least privilege access
and simplify user onboarding. Permissions are designed to be assigned
to groups rather than individual users.
