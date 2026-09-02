# Windows Server and Active Directory Administration Lab

## Overview

This project documents a hands-on Windows Server lab built in VMware. I installed Windows Server, configured Active Directory, administered users and access groups, organized directory objects, applied Group Policy, and configured DNS and DHCP services. I then tested the environment and recorded validation and troubleshooting observations so the build could be repeated.

## Skills demonstrated

- Windows Server installation and initial configuration
- Active Directory Domain Services administration
- User, security-group, and organizational-unit management
- Group Policy creation, application, and validation
- DNS and DHCP configuration and testing
- Virtual-machine networking
- Access validation and structured troubleshooting
- Technical documentation

## Lab environment

Complete this table with the versions and settings used in your actual lab.

| Component | Lab value |
| --- | --- |
| Hypervisor | VMware [PRODUCT AND VERSION] |
| Host operating system | [HOST OS] |
| Server virtual machine | Windows Server [VERSION] |
| Server role | Domain controller, DNS, DHCP |
| Domain | `[FICTIONAL_LAB_DOMAIN]` |
| Client system, if used | [CLIENT OS OR NOT USED] |
| Virtual network mode | [NAT / HOST-ONLY / BRIDGED / CUSTOM] |
| IP plan | [SANITIZED LAB SUBNET] |

## Implementation summary

1. Created a VMware virtual machine and installed Windows Server.
2. Completed initial server, network, and hostname configuration.
3. Installed and configured Active Directory Domain Services.
4. Created organizational units matching the lab's administrative structure.
5. Created test users and security groups and assigned group membership.
6. Created and linked Group Policy settings, then tested the resulting access behaviour.
7. Configured DNS and verified name resolution.
8. Configured a DHCP scope and tested address assignment.
9. Recorded configuration details, validation results, and troubleshooting observations.

## Directory design

Replace the example names with your actual fictional lab design.

| Object type | Purpose | Example |
| --- | --- | --- |
| Organizational unit | Separate objects for administration and policy targeting | `[Workstations]`, `[Users]`, `[Departments]` |
| User | Represent a fictional lab employee | `[Lab User 01]` |
| Security group | Assign access or policy by role | `[IT Support]` |
| Group Policy Object | Apply a defined user or computer setting | `[Policy name and purpose]` |

## Validation

Record what you actually tested. Helpful tools may include `ipconfig /all`, `nslookup`, `gpresult /r`, Event Viewer, Active Directory Users and Computers, DNS Manager, and DHCP Manager.

| Test | Expected result | Actual result | Evidence |
| --- | --- | --- | --- |
| Domain and directory service availability | [EXPECTED] | [ACTUAL] | [SCREENSHOT OR LOG LINK] |
| Test-user authentication | [EXPECTED] | [ACTUAL] | [SCREENSHOT OR LOG LINK] |
| Security-group-based access | [EXPECTED] | [ACTUAL] | [SCREENSHOT OR LOG LINK] |
| Group Policy application | [EXPECTED] | [ACTUAL] | [SCREENSHOT OR LOG LINK] |
| DNS name resolution | [EXPECTED] | [ACTUAL] | [SCREENSHOT OR LOG LINK] |
| DHCP address assignment | [EXPECTED] | [ACTUAL] | [SCREENSHOT OR LOG LINK] |

## Screenshots to add

- Server Manager showing installed roles
- Redacted Active Directory organizational-unit structure
- Fictional test users and security groups
- Group Policy Management showing the policy and link location
- Redacted `gpresult` evidence
- DNS zone and a successful name-resolution test
- DHCP scope, lease, and sanitized client address configuration

Store screenshots in `images/` and use descriptive names such as `03-ou-and-group-structure.png`.

## Troubleshooting

Document at least one real issue using `docs/troubleshooting-log-template.md`. Strong examples include DNS misconfiguration, a policy not applying, a user receiving an unexpected access result, or a client not receiving a DHCP lease.

## Lessons learned

- [EXPLAIN HOW OU DESIGN AFFECTED ADMINISTRATION OR POLICY TARGETING]
- [EXPLAIN WHAT YOU LEARNED ABOUT DNS DEPENDENCIES]
- [EXPLAIN HOW YOU VALIDATED CHANGES INSTEAD OF ASSUMING THEY WORKED]

## Planned improvements

- [OPTIONAL NEXT STEP THAT YOU INTEND TO COMPLETE]

## Security note

All identities and network details shown in this repository must be fictional or sanitized. Never publish passwords, production domains, client data, private keys, or unredacted infrastructure details.
