![Shape1](RackMultipart20230809-1-6q5c5p_html_c06e835f4fc12726.gif)

# **Contents**

[**Introduction** 3](#_Toc139617759)

[**Scope** 3](#_Toc139617760)

[**Definitions** 3](#_Toc139617761)

[**Plan Summary** 3](#_Toc139617762)

[Preparation 3](#_Toc139617763)

[Detection and Analysis 4](#_Toc139617764)

[Containment and Investigation 4](#_Toc139617765)

[Eradication and Recovery 4](#_Toc139617766)

[Post-Incident Review 4](#_Toc139617767)

[**Plan Framework** 4](#_Toc139617768)

[Preparation 5](#_Toc139617769)

[Detection and Analysis 6](#_Toc139617770)

[Detection and Analysis Protocol 7](#_Toc139617771)

[Containment and Investigation Summary 10](#_Toc139617772)

[Post-Incident Review 13](#_Toc139617773)

[References 15](#_Toc139617774)

[Version Tracking 15](#_Toc139617775)

[**Appendix A: Notification and Communication** 16](#_Toc139617776)

[Interaction with Law Enforcement 16](#_Toc139617777)

[Regulatory Authorities 16](#_Toc139617778)

[Customers 16](#_Toc139617779)

[Public Media Handling 16](#_Toc139617780)

[**Appendix B: Evidence Chain of Custody Tracking Form** 17](#_Toc139617781)

[**Appendix C: Incident Response Scenarios** 18](#_Toc139617782)

[Scenario: Unauthorized access or breach 18](#_Toc139617783)

[Scenario: Ransomware 18](#_Toc139617784)

[Scenario: Insider threat 18](#_Toc139617785)

[Scenario: Phishing or social engineering attack 18](#_Toc139617786)

[Scenario: System or application vulnerability exploitation 19](#_Toc139617787)

[Scenario: Incident related to third-party vendors 19](#_Toc139617788)

[**Appendix D: Incident Response Guide and Report** 20](#_Toc139617789)

[Indicators of Compromise 20](#_Toc139617790)

[Containment Actions 20](#_Toc139617791)

[Investigatory Actions 21](#_Toc139617792)

[Eradication and Recovery Actions: 21](#_Toc139617793)

[Post-Incident Review 21](#_Toc139617794)

#

# **Introduction**

A critical principle of medicine applies equally well to cybersecurity incident responses – _Do No Harm_. Organizations face many pitfalls that can dramatically increase the negative impact of an incident. This

guide is designed to help you manage a cybersecurity incident while avoiding common errors, increasing

both the effectiveness and efficiency of your incident response efforts.

The DTC Incident Response Plan has been developed to provide direction and focus on the handling of security incidents that adversely affect DTC. This plan should be followed by any person or entity responding to a security incident.

# **Scope**

This plan applies to all DTC information resources and data.

# **Definitions**

- **Incident:** Violation of DTC policy, unauthorized access, use, or modification of information resources and data, denial of service to information resources and data, or loss of confidential or protected information.
- **Incident Response Commander (IRC):** Prioritizes and manages the IRT's actions during an incident. The IRC is also responsible for reporting back to the Leadership team. The IRC may or may not be a member of Leadership team.
- **Incident Response Team (IRT):** A team comprised of the commander and members that follow the Incident Response Plan to detect, contain, investigate, remediate, and recover from a security incident.
- **Incident Response Team Members:** Staff that execute actions from the Incident Response Plan at the direction from the IRC. An IRT member may direct their team to perform response actions instead of performing them directly.
- **Documentation Manager:** Team member responsible for documenting all activity related to the incident including when the incident was discovered, how it was reported, actions taken, etc. This team member is also responsible for ensuring chain of custody.

# **Plan Summary**

### **Preparation**

The preparation phase begins with the dedicating of resources for the IRT including team members, facilities, and equipment to perform the tasks. A contact list should be maintained to ensure all necessary parties are informed.

### **Detection and Analysis**

Incidents are discovered by investigations into reported indicators. An indicator is a sign that an incident may have occurred, such as unusual files found on a workstation or other anomalous activity. Reports of indicators come from a variety of sources including employees, SIEMs, or other monitoring platforms. When an indicator is reported, the Information Security team is responsible for further assessment to determine the legitimacy and continue with incident response procedures if necessary.

### **Containment and Investigation**

After an incident has been detected and scope determined, containment should take place to minimize impact, isolate affected resources, and prevent further damage to DTC information resources and data. Investigation involves collecting and preserving event logs and data to determine the order of events, confirm affected systems and data, and allow for root cause analysis.

### **Eradication and Recovery**

Once contained, eradication and recovery should be performed to restore operations to normal. Eradication involves performing a root cause analysis to identify what allowed an incident to occur. The finding should be documented and resolved to prevent the incident from recurring before continuing onto recovery.

The recovery phase facilitates the resumption of both systems and business operations to normal function. Prior to resuming operations, checks should be performed to ensure that all systems are properly cleaned of any remnants of the incident and secured from the possible repeat of the incident. Monitoring should be established to detect and prevent future incidents.

### Post-Incident Review

The final phase consists of a "lessons learned" meeting with all involved parties. This meeting should review the events of the incident, what went well, and opportunities for improvement. The legal team and Information Security team should work together during this phase to determine retention of evidence and any determine if any additional steps should be performed in regard to legislative or legal requirements.

# **Plan Framework**

All steps performed in each phase should be documented in a ticket to track events and time. Confidential information should be stored in the Security Incidents repository on SharePoint to limit access to confidential resources. Appendix D contains a report template that all IRT members should complete during an active incident. The report template should be used in conjunction with this framework to ensure no steps are missed. All reports will be retained as evidence of the incident. The IRC is responsible for summarizing the events in a single report (using the same template) to provide and review with the Security Committee.

### **Preparation**

The Leadership team should understand the responsibilities of an IRC and be prepared to select one in the event of an incident. The IRC, with the help of the Security Leadership team, will define the members of the IRT. Below is a list of potential primary members and alternates in the event the primary is unavailable or filling another role in the IRT. This table should be used as a starting place, during an incident the list may be partially implemented or modified depending on the response needed.

| Role | Primary | Alternate |
| --- | --- | --- |
| Incident Response Commander | Nate Smith | Scott Leister |
| Internal Systems Management | Scott Leister | Kathy Gilbert |
| IT Service Operations | Jennifer German | Chad Prindible |
| Finance | Steve McNamara | Christina Geiwitz |
| General Counsel/Legal | Christina Geiwitz | Outside Legal Counsel |
| Communications | Christina Geiwitz | Chloe Barnett |
| Human Resources | Christina Geiwitz | Bambee |
| Documentation Management | Chloe Barnett | Christina Geiwitz |

#### Roles and Responsibilities

| **Role** | **Responsibilities** |
| --- | --- |
| **Incident Response Commander (IRC)** | Leads, drives, and coordinates all Incident Response Team activity, keeps the team focused on minimizing damage, and recovering quickly. Informs and coordinates with Executive Management. |
| **Internal Systems Management** | Coordinates Internal Systems team(s) to support the IRT in detection, containment, and determining root cause and to resume business operations. Collects and analyzes all evidence, determines root cause, directs the other security analysts, and implements rapid system and service recovery. |
| **I**** T Service Operations** | Coordinates IT Field Services resources to support the IRT in detection, containment, and determining root cause and to resume business operations of IT Field Services operations and Client environments, if impacted. |
| **Finance** | Coordinates Finance resources to support the IRT in detection, containment, and determining root cause and to resume Finance operations, if impacted.Provides guidance for organizational financial operations and fiduciary impact analysis. May serve as a subject matter expert regarding financial crimes. |
| **General Counsel/Legal** | Provides guidance for legal matters. Legal ensures that any evidence collected maintains its forensic value if the company chooses to take legal action. They also provide advice regarding liability issues when an incident affects customers, vendors, and/or the general public. |
| **Communications** | Leads the effort on messaging and communications for all audiences, inside and outside of the company. |
| **Human Resources** | Provide guidance and act in matters that involve employees. Examples may include errors or malicious intent leading to disciplinary action up to criminal reporting. |
| **Documentation Management** | Documents all team activities, including investigation, discovery, and recovery tasks, and develops reliable timeline for each stage of the incident. |

### **Detection and Analysis**

Incidents are discovered by investigations into reported indicators. An indicator is a sign that an incident may have occurred, such as unusual files found on a workstation or other anomalous activity. Reports of indicators come from a variety of sources including employees, SIEMs, or other monitoring platforms. When an indicator is reported, the **Information Security** team is responsible for further assessment to determine the legitimacy and continue with incident response procedures if necessary.

- **Detection** involves collecting data from IT systems, security tools, publicly available information, and people inside and outside the organization and identifying precursors (signs that an incident may happen in the future) and indicators (data showing that an attack has happened or is happening now).
- **Analysis** involves identifying a baseline or normal activity for the affected systems, correlating related events, and seeing if and how they deviate from normal behavior.

### **Detection and Analysis Protocol**

When a DTC employee or external party notices a suspicious anomaly in data, a system, or the network, or a system alert generates an event, the **Information Security** team (or IRT if already initiated) must perform an assessment and verification of the event. The assessment will determine the category, scope, and potential impact of the incident. Once an incident has been identified and confirmed, part or all of the IRT will be activated to investigate and contain the situation. An incident response analyst is responsible for collecting and analysing data to find any clues to help identify the source of an attack. In this step, analysts identify the nature of the attack and its impact on systems. The IRT should work quickly to analyse and validate each incident, following the pre-defined process and documenting each step taken. During this phase, third party security providers, such as a managed SOC, should be contacted to inform them of an active incident. The security provider may continue to assist throughout each phase to help identify, scope, and remediate incidents.

#### Indicators of Compromise

Although there is no single symptom or indicator that an incident has occurred, below is a non-comprehensive list of indicators that require deeper investigation.

- Alert from an IDS/IDP sensor
- Suspicious entries or discrepancies in system or network logs
- Repetitive unsuccessful logon attempts within a short time interval.
- Unexplained new accounts, files, etc.
- Unexplained modification or deletion of data
- Disruption of service or inability of one or more users to login to an account
- Poor system performance of dedicated servers
- Loss or Theft of Equipment
- Unusual time of usage (e.g., user login during unusual times)
- Last logon (or usage) for a user account does not correspond to the actual last time the user used the account.
- Abnormal usage patterns

#### Incident Scope

The **Information Security Team** or IRT should first work to scope and define the incident. At a minimum, the following questions should be answered.

- What **Information Resource(s)** and data is impacted and what are the classification level?
- What indicators were discovered (signs and symptoms of an incident)?
- How were the indicators discovered?
- Has the source (point of entry) of the event been discovered?
- When were the indicators discovered?
- Who discovered the indicators?
- Any other pertinent history (user's most recent actions, any recent maintenance, etc.)

#### Incident Classification

With the scoped information, an incident categorization should be determined. Incident classification is not final but will help guide investigative and recovery processes. Below is a non-comprehensive list of possible classifications.

- Social engineering
- Business email compromise/corporate account takeover
- Financial fraud
- Denial of service
- Unauthorized network scanning/probing
- Ransomware
- Unauthorized access or intrusion
- Data loss or leakage
- Policy violation
- Espionage

#### Incident Impact

Once the scope and classification of an incident has been determined, the potential impact must be discussed and agreed upon. Impact will be based on severity of the incident and the data involved.

**Functional Impact**. Incident handlers should consider how the incident will impact the existing functionality of the affected systems. Incident handlers should consider not only the current

functional impact of the incident, but also the likely future functional impact of the incident if it is not immediately contained.

| **Functional Impact** | **Definition** | **IRT Response** |
| --- | --- | --- |
| **None** | No effect to DTC's ability to provide all services to all users | Create ticket and assign for remediation |
| **Low** | Minimal effect: DTC can still provide all critical services to all users but has lost efficiency | Create ticket and assign for remediation, notify IRT of incident |
| **Medium** | DTC has lost the ability to provide a critical service to a subset of system users | Initiate full IRT |
| **High** | DTC is no longer able to provide some critical services to any user | Initiate full IRT |

**Information Impact.** Incidents may affect the confidentiality, integrity, and availability of the organization's information. An incident that results in the exfiltration of sensitive information may also affect other organizations if any of the data pertained to a partner organization.

| **Information Impact** | **Definition** | **IRT Response** |
| --- | --- | --- |
| **None** | No information was exfiltrated, changed, deleted, or otherwise compromised | No action required |
| **Privacy Breach** | Sensitive personally identifiable information (PII) of taxpayers, employees, beneficiaries, etc. was accessed or exfiltrated | Notify IRC to work with legal/compliance to begin notification process according to state privacy laws |
| **Proprietary Breach** | Proprietary information, such as IP, business plans, etc. was accessed or exfiltrated | Notify IRC to communicate to executive management |
| **PHI Breach** | Protected health information (PHI) of customers or employees was accessed or exfiltrated | Notify IRC to work with legal/compliance to begin notification process according to HHS |
| **Integrity Loss** | Sensitive or proprietary information was changed or deleted | Notify IRC to communicate to data owners to determine appropriate course of action |

**Recoverability.** The size of the incident and the type of resources it affects will determine the amount of time and resources that must be spent on recovering from that incident. Incident handlers should consider the effort necessary to successfully recover from an incident and carefully weigh that against the value the recovery effort will create and any requirements related to incident handling.

| **Recoverability** | **Definition** | **IRT Response** |
| --- | --- | --- |
| **Regular** | Time to recovery is predictable with existing resources | Notify IRC of recovery scopte |
| **Supplemented** | Time to recovery is predictable with additional resources | Notify IRC of required additional resources plus recovery scope |
| **Extended** | Time to recovery is unpredictable; additional resources and outside help are needed | Notify IRC the recovery scope is unknown and external resources are required |
| **Not Recoverable** | Recovery from the incident is not possible (e.g., sensitive data exfiltrated and posted publicly); launch investigation | Notify IRC to communicate to stakeholders not-recoverable status and to determine appropriate course of action. |

#### Incident Notification

Part of containment involves notification to the appropriate parties, both internal and external. Parties should be notified on a need-to-know basis. Communication to external parties will typically come from legal, the IRC, or a designee. All communication to clients and media should be reviewed by Legal and Marketing before distributing. The communications plan is outlined in Appendix A: Notification and Communication.

| Internal parties | External parties |
| --- | --- |
| Human resources | Customers |
| Legal | Government |
| Finance | Media |
| Marketing | General public |
| Business owner | Law enforcement |
|
 | Incident response firm |
|
 | Insurance providerPublic Relations |
|
 | Security providers (managed SOC) |

### **Containment and Investigation Summary**

After an incident has been detected and scope determined, containment should take place to minimize impact, isolate affected resources, and prevent further damage to DTC information resources and data.Investigation involves collecting and preserving event logs and data to determine the order of events, confirm affected systems and data, and allow for root cause analysis.

#### Containment and Isolation

Common actions that can be performed during containment

- Isolate machines from network through Third Wall and Huntress
- Disable user accounts and disconnect any active connections
- Disable file shares
- Change user passwords
- Disconnect servers from the network
- Implement additional protection and/or monitoring solutions
- Scan systems with antimalware software and quarantine files
- Modify firewall rules

Actions that should not be performed during containment

- Powering off compromised systems
- Restore files from backup
- Restore servers from backup
- Restore workstations from backup or reimage if there are no backups

#### Evidence Collection and Investigation

The primary source of evidence is system logs. All relevant logs should be collected in a timely manner to ensure events are not lost. Logs should be collected as far back as possible if the incident timeline isn't well defined. In addition to log collection, affected systems should be snapshotted if possible and backups retained throughout the incident. The chain of evidence should be maintained throughout the evidence collection process. The following log files should be considered when determining what to collect.

- Firewall
- IDS/IDP
- Wireless access
- Proxy
- Antivirus/EDR/MDR
- VPN
- Identity Provider (e.g. Active Directory)
- Critical applications
- Known affected systems

Once the incident is contained and evidence is collected, an investigation will be performed to determine the root cause of the incident. DTC will perform all investigations for internal unless otherwise instructed by legal. Depending on the situation and information involved, the IRC or outside Legal Counsel may request a third-party IR and/or forensics firm may be engaged. Investigation techniques will vary depending on the type of incident. The investigation may rely on some (or all) of the following:

- Interviews with witnesses and/or affected persons
- Obtaining relevant documents
- Conducting observations
- Analysing the logs of the various devices involved (e.g. firewall, router, host).
- Taking photographs of physical locations

##### Root Cause Analysis

The root cause of an incident is determined by performing a root cause analysis (RCA). The RCA is performed by the Incident Response Team and is intended to identify system and process failures that contributed to the incident. The RCA will generate tasks to be reviewed during the lessons learned in the Post-Incident Review phase, however, it is important to identify the technical root causes early so eradication is successful. The following steps should be completed when performing an RCA:

1. Meet with the IRT
  - It is important that all members are present as individual teams bring their expertise to the group
2. Review the event at a high level and the information that has been collected
  - Chart and review timeline of events based on the investigation
3. Identify contributing factors
  - Situations, circumstances, or conditions that increased the likelihood of the event
  - E.g. Poor communication, no tools geo-blocking, ineffective alerts, etc.
4. Identify and categorize the root cause(s)
  - Can usually determine by repeatedly asking "Why is that?" For example:
    - Why did you not get an alert? – Disk space alerts were not configured.
    - Why is that? – The baseline does not require this.
    - Why is that? – The baseline hasn't been updated for several years.
    - Why is that? – No one was assigned responsibility.
  - The root cause should be assigned to one of the following categories
    - Administrative control non-existent
    - Administrative control change
    - Technical control non-existent
    - Technical control change
    - Newly discovered vulnerability
  - Categorization includes identifying the team responsible
5. Design remediation plan to eliminate or mitigate the contributing factors and root cause(s)
  - Should include long- and short-term actions
  - Should address root cause and contributing factors
  - May include modifications to technical, administrative, and physical controls

**Eradication and Recovery**

Once the investigation is complete and root cause(s) are determined, the applicable findings of the RCA should be executed to remove or mitigate vulnerabilities and threats which may cause the issue to recur. Once the new controls are in place, actions should be taken to clean affected systems. This may include a clean installation of operating systems and/or applications if necessary. The reinstalled operating system and applications must be installed according to DTC system standards. Any additional actions to prevent a recurrence of the incident should also be implemented.

It should be noted that administrative tools on a compromised host could be altered versions of the originals. A separate set of administrative tools (e.g. boot disk) than those on a compromised host for investigation should be used whenever possible.

Prior to restoring systems or data from a clean backup, the IRT must validate the system to confirm eradication was successful and the system is secure. If feasible, the system should be installed in a test environment to determine functionality prior to re-introduction into a production environment.

Additional endpoint and network monitoring should be implemented for as long as necessary to detect any unauthorized access or modification attempts.

If a disaster is declared as a result of the incident affecting the DTC network or facilities, the Disaster Recovery Policy should be invoked.

### Post-Incident Review

#### Lessons Learned

The objective of completing a Lessons Learned review is to improve the incident response process by evaluating the incident and actions performed. This meeting should involve all members of the IRT and any involved stakeholders. The IRC will be responsible for generating takeaways during this meeting and assigning tasks appropriately. During this meeting, the following questions be answered:

- What happened and when?
- What actions were performed by the staff and were procedures followed?
- Were the documented procedures accurate and sufficient?
- What information and/or resources were needed sooner?
- What actions hindered recovery?
- What actions expedited recovery?
- What could staff and management do differently in a similar situation?
- Are there any additional controls, tools, or monitoring identified by the RCA that are needed to mitigate future incidents?

#### Documentation

All documentation created during the response should be reviewed to ensure completeness and retained. This includes the following:

- All system events (audit records, logs)
- All actions taken (including the date and time that an action is performed), and
- All external conversations
- RCA results

Additionally, an Incident Report should be created for easy tracking and reference. The report should be created by following the guide in Appendix D: Incident Response Guide and Report, shared with the Security Committee, and saved with their documents. The report identifies areas of potential improvement and should be provided to management for review. The following items should be included:

- A description of the exact sequence of events
- The method of discovery
- Preventative measures implemented post-incident
- Lessons Learned takeaways
- Assessment to determine if the recovery is sufficient and what other recommendations should be considered.

#### Lessons Learned Tasks

Any takeaways generated during Lessons Learned will be reviewed with the involved parties. The IRT will meet with each party (technical staff, management, vendors, security team, etc.) and work to incorporate lessons learned from the incident to mitigate the risk of future incidents. Mitigations can include system configurations, policies, procedures, training, and many other safeguards.

Additionally, the results of the RCA performed during the Containment and Investigation phase should be reviewed by the IRC. Any implementation plan tasks that have not been completed or should be assigned to the appropriate teams.

Information about the incident should be shared when possible with appropriate organizations. The Security Leadership team and Legal can decide which agencies to share information with. Agencies may include the FBI, InfraGard, ISACs, etc.

## References

- NIST CSF: RS.RP, RS.CO, RS.AN, RS.MI, RS.IM, RC.RP, RC.IM, RC.CO
- NIST 800-61 Rev. 2: Computer Security Incident Handling Guide

## Version Tracking

| Reviewed/Approved By: | Reviewed/Approval Date: | Revision Comments |
| --- | --- | --- |
|
 |
 |
 |
|
 |
 |
 |
|
 |
 |
 |

# **Appendix A: Notification and Communication**

Required notification and communication both internally and with third parties (customers, vendors, law enforcement, etc.) based on legal, regulatory, and contractual requirements must take place in a timely manner.

- DTC's Chief Information Security Officer or designee must report the incident to the DTC Executive Management
- The CISO, Legal, and/or executive management must report any breaches and/or incidents involving customer data to:
  - Any affected customers and/or partners (within X hours or based on SLA)
  - Local, state or federal law officials as required by applicable statutes and/or regulations

### Interaction with Law Enforcement

Interaction between law enforcement and emergency services personnel should be coordinated by members of the IRT only at the direction of the IRC.

In cases of personal safety, all personnel are permitted to contact law enforcement and emergency services personnel; however, ongoing communication with these authorities should be turned over to members of the IRT when appropriate.

### Regulatory Authorities

- DTC is subject to various regulatory oversight depending on the data impacted. If there is the potential that regulated data was breached, it may be necessary to notify the Secretary of the U.S. Department of Health & Human Services or Payment Card Industry Security Standards Council (PCI SSC). (See Appendix for specific details for various regulation.) Depending upon the nature of the breach, other governmental regulators may contact DTC
- Only members of the IRT are permitted to discuss the nature and/or details of an incident with any regulatory agencies.
- The IRT should contact regulators as soon as practical.

### Customers

- All customers who are affected by the incident must be notified according to applicable contract language and/or service level agreements (SLAs).
- Communications with customers must be consistent, with the same or similar message delivered to each. The message sent to customers will be created by members of the appropriate support team and reviewed by Legal and Marketing.
- Customer service and/or customer account managers will communicate with customers according to the message developed by the Marketing Team.

### Public Media Handling

All information concerning an incident is to be considered Confidential and should not be discussed with anyone outside of DTC without approval of the executive management and legal counsel.

Public or media statements must be carefully managed to ensure that any investigation and/or legal proceedings are not jeopardized. Decisions concerning the disclosure of incident information will only be made by executive management and legal counsel. The Business Continuity plan should be referenced for a communication plan for internal and external users. Only employees designated by the executive team and legal counsel are permitted to interact with members of the media.

#

# **Appendix B: Evidence Chain of Custody Tracking Form**

Ticket Number: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ Incident Classification: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

Company: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

Resource: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ Date/Time Collected: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

|
 | **Description of Evidence** |
| --- | --- |
| **Item #** | **Description of Item** (model, serial, condition, marks, scratches, etc.) |
| _00_ | _Image of file share server from vSphere | log files from system A_ |
| 01 |
 |
| 02 |
 |
| 03 |
 |
| 04 |
 |
| 05 |
 |
| 06 |
 |
| 07 |
 |
| 08 |
 |
| 09 |
 |
| 10 |
 |
| 11 |
 |
| 12 |
 |
| 13 |
 |
| 14 |
 |
| 15 |
 |
| 16 |
 |
| 17 |
 |
| 18 |
 |
| 19 |
 |
| 20 |
 |

| **Chain of Custody** |
| --- |
| **Item #** | **Date/Time** | **Released by** | **Received by** | **Comments** |
|
 |
 |
 |
 |
 |
|
 |
 |
 |
 |
 |
|
 |
 |
 |
 |
 |
|
 |
 |
 |
 |
 |
|
 |
 |
 |
 |
 |
|
 |
 |
 |
 |
 |
|
 |
 |
 |
 |
 |
|
 |
 |
 |
 |
 |
|
 |
 |
 |
 |
 |
|
 |
 |
 |
 |
 |

##

# **Appendix C: Incident Response Scenarios**

This appendix is designed to provide examples of responses to common incidents. These scenarios do not cover the detection, analysis, or post-incident phases as these are standard and performed similarly regardless of the incident.

### Scenario: Unauthorized access or breach

#### Assumptions: The breach has already occurred, access to sensitive data/systems, attacker may still have access to systems/data. Scope and impact are not fully known.

#### Containment:Isolate affected systems, change passwords, patch vulnerabilities, monitor network traffic, preserve evidence.

#### Investigation: Thorough examination of compromised systems, determine entry point, identify malicious files/code, understand attacker's actions. Speak with individuals involved in incident. External collaboration.

#### Eradication: Remove malware, patch vulnerabilities, remove backdoors, system hardening, update passwords.

#### Recovery: Restore affected systems, validate system integrity, user awareness/training, continuous monitoring.

### Scenario: Ransomware

#### Assumptions: Nature of malware/ransomware, potential impact, affected systems, resources available to respond.

#### Containment: Isolation of infected systems, network segmentation, disable compromised accounts, blocking communication channels for malware.

#### Investigation: Gather evidence to identify entry point plus other compromised systems/data.

#### Eradication: Thoroughly clean infected computers, patches, or updates to resolve vulnerabilities.

#### Recovery: Install/restore affected systems and data.

### Scenario: Insider threat

#### Assumptions: Nature of the threat, potential impact, resources required to address.

#### Containment: Limit authorized access, safeguard critical systems/data. Disable compromised accounts, isolation of affected systems, restrict network access.

#### Investigation: Collaboration with internal and external resources.

#### Eradication: Remove malware/tools. Implement security enhancement to prevent similar incidents in the future, ensure all traces of the threat are eliminated.

#### Recovery: Restore affected systems, review and update security controls, policies.

### Scenario: Phishing or social engineering attack

#### Assumptions: Affected systems, users, departments, potential impact on data confidentiality, integrity, availability, assess the level of urgency and available resources.

#### Containment: Isolate affected systems, disable compromised accounts, change passwords.

#### Investigation: Preserve evidence, analyze attack vectors, techniques used, identify compromised systems, user accounts, credentials.

#### Eradication: Remove or neutralize attacker's presence from compromised systems, patch vulnerabilities or security gaps, remove malware, update security controls, policies.

#### Recovery: Restore affected systems/data, user awareness training.

### Scenario: System or application vulnerability exploitation

#### Assumptions: Vulnerability has been successfully exploited, attacker has gained unauthorized access to systems or application, sensitive data may have been compromised, incident poses potential risk to DTC's operations, reputation, or compliance.

#### Containment: Isolate affected systems/applications, disable compromised accounts/credentials, restrict access privileges.

#### Investigation: Collect logs, snapshots, available artifacts related to incident, analyze network traffic, forensic analysis to understand scope and impact, identify compromised data/systems and extent.

#### Eradication: Apply patches, updates, or configuration changes to fix vulnerability, reset compromised user accounts/passwords, conduct thorough security review to identify and address other potential vulnerabilities.

#### Recovery: Restore systems/data, verify integrity of restored systems/applications, implement additional security monitoring tools, educate users about incident and any necessary precautions.

### Scenario: Incident related to third-party vendors

#### Assumptions: Define scope and potential impact, identify affected systems/application, establish communication with third-party vendor.

#### Containment: Isolate and disconnect affected systems/applications, assess extent of incident and potential spread, coordinate with third party vendor to temporarily suspend their access or connections, implement and temporary workarounds or mitigations to minimize impact.

#### Investigation: Gather relevant logs, snapshots, data related to third-party vendors activities, analyze incident to understand cause, origin, actions taken by vendor or threat actors, determine vulnerabilities or security gaps that allowed incident to occur, collaborate with third party vendor to gain insight into their security practices.

#### Eradication: Develop remediation plan based on finding of investigation, implement necessary changes or patches to fix vulnerabilities, work closely with third-party vendor to ensure they address any security issues on their side, conduct system review to verify all malicious activity has been removed.

#### Recovery: Restore systems, services, or applications that were impacted, monitor restored systems for recurring issues or further compromise.

# **Appendix D: Incident Response Guide and Report**

**Ticket** : **Classification** : **Written by:**

**Incident summary** :

**Date/time of discovery** : **Date/time of recovery** :

**Incident Commander** :

**Incident Response Team** :

**Scope** :

**Functional impact** : ☐None ☐Low ☐Medium ☐High

**Information impact** : ☐None ☐Proprietary ☐Integrity ☐PII ☐PCI ☐PHI

**Notification required** : ☐None ☐Internal ☐Customers ☐Legal

### Indicators of Compromise

| **Indicator of Compromise (IoC)** | **Detected by** | **Date/Time** | **Responder** |
| --- | --- | --- | --- |
|
 |
 |
 |
 |
|
 |
 |
 |
 |
|
 |
 |
 |
 |
|
 |
 |
 |
 |
|
 |
 |
 |
 |
|
 |
 |
 |
 |
|
 |
 |
 |
 |

### Containment Actions

| **Action** | **Purpose** | **Date/Time** | **Performed by** |
| --- | --- | --- | --- |
|
 |
 |
 |
 |
|
 |
 |
 |
 |
|
 |
 |
 |
 |
|
 |
 |
 |
 |
|
 |
 |
 |
 |
|
 |
 |
 |
 |
|
 |
 |
 |
 |

###

### Investigatory Actions

**Third-party Incident Response firm engaged?** ☐Yes☐No

**Summary of Events** (include timeline, interviews, resources collected, RCA results, etc.):

**Root Cause Analysis:**

### Eradication and Recovery Actions:

### Post-Incident Review

**Lessons Learned Date/Time:**

**Lessons Learned Attendees:**

**Lessons Learned:**

**Remediation tasks** :

| **Task** | **Ticket** | **Assignee** |
| --- | --- | --- |
|
 |
 |
 |
|
 |
 |
 |
|
 |
 |
 |
|
 |
 |
 |
|
 |
 |
 |
|
 |
 |
 |

**Details reported to third parties?** ☐No ☐Yes: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

**Incident Commander** : \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ **Date** : \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

**Security Committee Review Date/Time** :\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_