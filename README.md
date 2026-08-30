  # Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
* The core problem stems from a fictional company, Northstar Medical Group (NMG). Early on, when NMG was smaller, they outsourced their IT infrastructure to a managed service provider (MSP) because they didn't yet have the internal resources to manage it themselves. As the company grew,this arrangement became a liability. The Active Directory environment was left disorganized, with no formal RBAC (role-based access control) policies in place resulting in inconsistent, unmanaged access across the organization.
Because NMG operates in healthcare, HIPAA compliance is critical. Without a properly structured identity and access management system, NMG is exposed to serious compliance risk, including the potential for significant fines tied to failing to meet regulatory standards.

## Solution Overview
* I took ownership of Northstar's identity infrastructure, starting by building a strong foundation through a properly structured Active Directory environment. This was the most critical piece of the project, since everything built afterward depends on that foundation being solid. I created the OUs and security groups, then built out user accounts and placed them in their correct departments. To validate the setup, I also simulated a mock support ticket in which a user had been provisioned with the wrong access allowing me to walk through the troubleshooting and remediation process end to end.

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
* I solved a mock ticket where user was given incorrect access
* I was able to document and show detailed work end-to-end
