\# TechNova IT Help Desk Lab



\### Windows Server 2025 | Active Directory | Windows 11 | DNS | IIS | Jira Service Management



\## Project Overview



TechNova IT Help Desk Lab is a simulated enterprise IT environment designed to demonstrate practical IT support, system administration, and troubleshooting skills.



The project recreates common responsibilities of an entry-level IT Support or Desktop Support technician, including managing employee accounts, configuring Windows workstations, resolving network and DNS issues, supporting internal resources, and documenting incidents through a ticketing system.



All employees, departments, and support incidents in this project are fictional and used for educational purposes.



\## Technologies Used



\- Windows Server 2025

\- Windows 11

\- Oracle VirtualBox

\- Active Directory Domain Services (AD DS)

\- Group Policy Management

\- Windows DNS Server

\- Internet Information Services (IIS)

\- Jira Service Management

\- Command Prompt and Windows administration tools



\## Lab Environment



| Component | Configuration |

|---|---|

| Organization | TechNova (Simulated) |

| Active Directory Domain | `corp.technova.test` |

| Domain Controller | Windows Server 2025 |

| Domain Controller IP | `192.168.56.10` |

| Windows 11 Workstation | `TN-WIN11-01` |

| Internal DNS | Windows Server DNS |

| Internal Website | `intranet.corp.technova.test` |

| Ticketing System | Jira Service Management |



\## Active Directory Administration



Configured a Windows Server 2025 domain controller and created an organizational structure representing a fictional company.



Tasks performed:



\- Installed and configured Active Directory Domain Services.

\- Created the `corp.technova.test` domain.

\- Organized departments using Organizational Units (OUs).

\- Created simulated employee accounts.

\- Created departmental security groups.

\- Managed user group memberships.

\- Practiced account password resets and account enable/disable procedures.

\- Explored Group Policy administration.



Departments configured:



\- IT

\- Human Resources

\- Finance

\- Sales

\- Workstations



\## Windows 11 Workstation Support



Configured and tested a Windows 11 workstation in the simulated corporate environment.



Tasks included:



\- Configuring TCP/IP networking.

\- Verifying network adapter settings.

\- Testing connectivity to the domain controller.

\- Troubleshooting DNS name resolution.

\- Verifying domain user authentication.

\- Using Windows command-line diagnostic tools.



Commands used:



`ipconfig /all`



`ping 192.168.56.10`



`nslookup corp.technova.test`



`whoami`



\## DNS and Internal Website Troubleshooting



Configured Windows DNS and IIS to support an internal TechNova employee website.



Tasks performed:



\- Investigated failed internal DNS lookups.

\- Created a DNS Host (A) record.

\- Mapped `intranet.corp.technova.test` to `192.168.56.10`.

\- Installed the IIS Web Server role.

\- Verified IIS operation through localhost.

\- Created a basic HTML employee intranet page.

\- Configured `index.html` as the default website document.

\- Verified website access from a Windows 11 workstation.



\## IT Support Ticket Simulation



Created and documented three simulated employee support incidents using Jira Service Management.



| Ticket | Issue | Status |

|---|---|---|

| SUP-1 | Employee unable to log in | Resolved |

| SUP-2 | HR employee unable to access shared folder | Resolved |

| SUP-3 | Employee unable to access internal website | Resolved |



Each incident includes troubleshooting documentation describing the reported problem, investigation, corrective actions, and resolution.



\## Troubleshooting Methodology



Followed a structured troubleshooting process:



1\. Identify and document the reported issue.

2\. Gather relevant system and network information.

3\. Investigate possible causes.

4\. Implement an appropriate corrective action.

5\. Verify the issue is resolved.

6\. Document the findings in Jira Service Management.

7\. Update the ticket status.



\## Project Evidence



Screenshots are organized into the following folders:



\- `Screenshots/Active-Directory/`

\- `Screenshots/Windows-11/`

\- `Screenshots/DNS-and-IIS/`

\- `Screenshots/Jira-Tickets/`



These screenshots provide evidence of the lab configuration, diagnostic testing, and simulated support-ticket documentation.



\## Skills Demonstrated



\- Windows 11 desktop support

\- Windows Server administration fundamentals

\- Active Directory user and group management

\- TCP/IP troubleshooting

\- DNS troubleshooting

\- IIS web server configuration

\- Domain authentication verification

\- IT incident documentation

\- Jira ticket management

\- Technical problem-solving



\## Project Purpose



This project was created to develop practical experience with technologies and workflows commonly encountered in entry-level Help Desk, IT Support, and Desktop Support positions.



It demonstrates the ability to configure a small Windows domain environment, investigate simulated employee issues, verify technical solutions, and document support activities professionally.

