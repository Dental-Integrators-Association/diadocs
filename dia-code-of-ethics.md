# The DIA Code of Ethics

## Overview
The DIA “Code of Ethics” is a document defining the best ways DIA members do business with their client base. The “Code of Ethics” must be followed to the best of DIA members’ ability. DIA Members that follow the code of ethics must be recognized for doing so by 2024.

## Glossary
### Propose
To offer a solution and maintain a written record of all offers. Solutions packaged into an agreement are considered proposed.

### Consult
To guide an entity to a solution and maintain a written record of said guidance.

### Remote/Remotely
To access information (in this context work resources) over the public internet between trusted LAN and untrusted WAN networks. Zero Trust network access is excluded here as all "practical network traffic" is untrusted.

### Easy/Easily
The problem at hand can be solved without signifcant cost to time, currency, or general value.

## Application Licensing
DIA members must only distribute legal and licensed software applications. Refrain from assisting in the installation, support, or distribution of software applications obtained in an illegal manner. Consult the client on the risks of using illegally obtained software applications.

## Records & Documentation Management
DIA members must maintain a record management solution (including applications, workflows, policy, and best practices) to adhere to accountability. Examples of this include a help desk ticketing system, a task management system, a documentation system for technical configurations and policies. All of these solutions must be digital and backed up.

## HIPAA & PII Policies
DIA members must develop and maintain a HIPAA & PII policies for their team. This includes general written documentation and regular training on both subjects.

## Identity Solutions
DIA members must always propose an identity solution. Examples of identity solutions are Azure AD, Active Directory Domain Services, Jumpcloud, FreeIPA, MFDS, Workgroup by means of manual configuration (Same users across all endpoints), Configuration management deploying users across all systems, and PKI identifying end users.
## Infrastructure Solutions
DIA members must always propose infrastructure solutions that follow these best practices:

### Servers
-	Must be configured for performance in the best interest of the client & maximum availability based on budget.

### Networking
-	Must have ability to control ACL’s, Access Control Lists (Statelesss and Statefull), to set network boundaries.
-	Must provide secure tunneling across the public internet where a direct wire or Over the Air cannot be used.
-	Must have the ability to monitor the network solution for faults.
-	Must have the ability to monitor the network solution for security incidents.
-   All Over the Air (OTA) solutions must be encrypted using at least AES-128 encryption. User authentication indiviudally is optional. OTA solutions meant for the public or guests to access do not require encyrption or user authenication.

## Data Lifecycle & Backups
### Data Lifecycle
DIA members must communicate the urgency of data lifecycle. Data lifecycle is the start of a piece of information stored digitally, organizing, and archiving.

### Data Backups
DIA members must communicate the urgency of data backups. DIA members must also propose backup solutions and communicate the default configuration for each client. Communication can be done during the sales process or done via the global agreement. DIA members must at least keep more than 1 version of a backup of a file and retain that data for 7 days or longer.

## Modern Work
### Email
DIA members must propose an enterprise grade email solution that can integrate with an identity provider. Please see Identity Solutions for more information. DIA members must also propose security solutions to protect said email solutions such as spam filtering and policy driving (enforcintg) industry standard email best practices. The email best practices include but are not limited to Sender Policy Framework, DKIM, and DMARC.

## Cyber Security
### EDR
DIA members must propose EDR (Endpoint Detection and Response) solutions rather than traditional anti-virus solutions. Please note most traditional anti-virus solutions do offer EDR solutions. A step further would be to propose a MDR solution which is a service that helps manage an EDR solution.

### User Authentication
#### Passwords
DIA members must all have their own password policy. The passwords policy must meet the requirements set by NIST Guidelines or may DIA members must consult with their clients on their own password policy following at least Microsoft Guidelines. NIST Guidelines are preferred.

#### Passwordless
DIA Members should propose an Identity Solution that can support passwordless authentication in environments where it is 100% supported. The only current passwordlesss solution across all boards is the use of Asymmetrical Cryptography along with a PKI infrastructure.

#### Multi-Factor Authentication
DIA Members themselves must have a multi-factor solution in place for accessing everything in the workplace REMOTELY. DIA Members must propose and consult on implementing any form of Mult-Factor Authentication that exists today to secure end user authentication even further for everything in the clients' workspace that is practical.

#### Service Accounts & Application Keys/Secrets
DIA Members must have a system or workflow that can rotate private application keys for themselves at least yearly. DIA Members that require service accounts must make usernames that are identifiable but obfuscated in nature for their username, and have a password that is 32 characters or longer.

#### Shared Accounts or Non-SSO Authentication
Due to the lack of fully integrated Identity Solutions, shared accounts & non-sso authentication must be used. In these scenarios, DIA Members are required to have their own credential/password management solution.

DIA Members must also develop a solution for their clients by 01/01/2026 to propose to their clients for the same scenario.

## Loggin
DIA Members must not use any application/tool/system/solution/etc to support their client base if it does not adhere to the following:
-    Security logs cannot easily be retained for 7-30 days. This one is a grey area, but differenet security levels are noisy and others are not, and vendors choose what is critical to the common so the minimum is 7 days and the maximum is 30 days).
-    
## Data Encryption
DIA Members must encrypt with their own solution any portable media device using AES-256 bit encryption or stronger. Phones & Laptops that access work data are considered portable media devices. All data stored in any data center must also be encrypted by the service provider or by the DIA Member. When using Symmetrical Cryptography, Pre-shared keys, the encryption key must be 32 characters long. The encryption keys must also be rotated when a compromise of any key is detected.

## Continuing Education For Users
DIA Members must develop by 01/01/2026 a cyber security continuing education program for their clients’ end users that can achieve the following: Phishing Campaigns, Training Regularly, Training when Phishing test is failed.
DIA Members by 01/01/2025 must implement the solution above for themselves.

## Secure Remote Access
DIA Members must consult and propose on secure remote access solutions that follow a Zero Trust networking model including Multi-Factor authentication if practical. If not practical, the use of VPNs with at least AES-128 encyrption must be used for secure remote access, or a remote console/virtual desktop solution that supports Multi-Factor authentication. 

## Infrastructure Security
DIA Members must develop a DNS Filtering solution by 01/01/2025 to propose to their clients. Examples include Cisco Umbrella, DNSFilter, and Webtitan.
