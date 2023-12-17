---
layout: single
title: ISO27001 - Phases Sample by Fernando
excerpt: "Distribuciones Mariano is a company dedicated to the sale and installation of electrical equipment to individuals and electrical material to individuals and professionals nationwide. In order to optimize the processes, Distribuciones Mariano has acquired a platform for Internet. The purpose of this report is to show my way of developing audit reports based in Phases and Process."
date: 2023-12-06
classes: wide
header:
  teaser: /assets/images/iso-sample/ISO-logo.png
  teaser_home_page: true
  icon: /assets/images/hackthebox.webp
categories:
  - ISO
  - "27001"
  - eMarisma
  - Auditing
  - Inform
tags:
  - Phases
  - ISO27001
  - Audit
  - Inform
  - Samples
  - Report
  - Portfolio
---

![](/assets/images/iso-sample/ISO-logo.png)


## Background

Distribuciones Mariano is a company dedicated to the sale and installation of electrical equipment to individuals and
electrical material to individuals and professionals nationwide.

In order to optimize the processes, Distribuciones Mariano has acquired a platform for platform so that from the Internet:
  - Its customers can place their orders, both for individuals and professionals.
professionals.
  - Professionals can opt for installations and works.

On this platform you will find the inventory of products, accounting, as well as all the data of the all the data of the customers or professionals (both groups; among these data are their demographics and demographic and financial data).
In order to access the platform, from the Distribuciones Mariano's website you select whether you are a private individual or a professional, and then you can access your personal personal zone. Similarly, there is an administration area that is managed exclusively by Distribuciones Mariano's staff. exclusively by Distribuciones Mariano staff.
Distribuciones Mariano, conscious of the importance of this platform, wants to to carry out a security review of this, so we request commercial offers from different suppliers.
to different suppliers.
In addition to the information provided above, Distribuciones Mariano comments to the suppliers that the platform is hosted by the company.
suppliers that the platform is hosted in its Data Processing Center (CPD), which contains a database that it contains an Oracle database and that all the development and maintenance services are outsourced to a third party and maintenance is outsourced to another company.

Once these casuistries are understood, it is requested to perform a complete report of security audit of the distribuciones Mariano platform. This audit should be focused under the audit practice on access, DB or security in the DPC.
in the DPC.


## Goals

The objective of IT Security is to protect against threats, in order to ensure the continuity of information systems, minimize ensure the continuity of information systems, minimize damage, maximize the return on investments and opportunities. In the case of Distribuciones Mariano, the information of product inventory, accounting, transactions and customer data represent one of the most important transactions and customer data represent one of the most important assets of the business. business. For this reason, an audit must be carried out in order to implement an adequate set of controls and measures that an adequate set of controls and measures comprising policies, procedures, practices, organizational structures, procedures, practices, organizational structures, policies and measures, procedures, practices, organizational structures, software or hardware functions.
The objectives of an IT audit are to control the IT function, analyze the efficiency and effectiveness of the the analysis of the efficiency of the IT systems involved, the verification of compliance with the the verification of compliance with the company's general regulations in this field and the review of the and the review of the effective management of resources. In the acquisition and design of information systems, in some cases, good practices are not taken into consideration or security regulations are overlooked, which ensure that, redundantly, a system is secure. For The level of security that can be achieved by technical means is therefore limited and must be supported by adequate management and procedures, involving the organization's employees of the organization, and even in some cases, suppliers and/or customers.

In the current report the process and phases of the audit will be carried out focused under the audit practice on access, DB or security in the DPC (Data Processing Center).
(Data Processing Center). 

## Methodology

There are currently three types of audit methodologies: ROA (risk oriented approach), simplified EDR Checklist or questionnaires and advanced EDR product audit.
The generic EDR methodology presented in this report is the most widely used and general one. The whole process is divided into three parts: develop, implement and monitor.

![image-20200519201954045](/assets/images/iso-sample/iso-sample-1.PNG)

The develop of the audit of a company's information system consists of identifying the origin of the audit, i.e. where the audit will start, then a preliminary visit to the area must be made. Then we proceed to establish the objectives that we want to achieve, determine the points that will be evaluated in the audit and develop plans, schedules and budgets for their realization. Then the methods, tools, instruments and procedures necessary for the audit must be identified and selected and the resources and systems that will be useful for the audit must be allocated (Kimat, 2018). Being a little more detailed with the process of a generic EDR audit, as we can divide the 3 parts mentioned in 6 phases, as in the illustration of the course slides. 

![image-20200519201954045](/assets/images/iso-sample/iso-sample-2.png)

As it could be seen in the illustration, the scope is a very important stage that defines the future processes for the realization of this type of projects, being essential to achieve the quantification of assets, threats, vulnerability, risks and future treatment plan.

Additionally, there is a compliance chart in the RGPD, which allows to verify from a checklist if the regulation is being complied with for the development of the application and the security of the information. Since it is a bit long, I will attach some small tables in the annexes section on the document in question.


## Executive Summary
The management of Distribuciones Mariano is aware of the importance of protecting the Information and consequently the Systems and Technologies that support and manage it, in order to safeguard the correct performance of the Company's business processes.
For this reason, Distribuciones Mariano has set as an objective the elaboration of an Information Security audit, but above all in the topics of Accesses, BBDD and CPD; this because it handles orders for professionals as well as individuals, and professionals can opt for installations and works; for this reason payments can be generated within their platforms and reservations. As a result of the work carried out, it is concluded that Distribuciones Mariano's information security situation is at a level (1) Initial / (2) Developing (on a scale of 0 to 4).
This company has implemented controls to ensure information security, but some parameters were not established in addition to configurations based on continuous audits, for this reason it is considered that the processes that are managed within their platforms can be improved and better maintain the integrity of the data of its users, thus, it would also control that there is no disclosure of information either by its users (direct employees) and those of the service that provide maintenance.
In this way, the confidentiality, integrity, availability and traceability of the information is achieved more efficiently, avoiding that these deficiencies could lead to service, financial and reputational losses. The current state of Information Security in Distribuciones Mariano contemplates a high knowledge of the criticality of the information that is treated in the great majority of the company's business processes, besides having contemplated the RGPD keeping the rules to the letter. But the lack of audits and and good continuous practices in their systems, among employees and external personnel, The lack of information security regulations means that most of the actions and information processing are carried out by means of common sense rules or behaviors and/or the experience acquired during their professional career, although it is not possible to find an extreme or atypical case.
It is worth highlighting positive aspects on the management and treatment of information in a secure manner. Of special mention is the security inside the Data Processing Centers (DPC), where it has been evidenced the adoption of perimeter and environmental security measures, capable of safeguarding the physical security of the assets inside. But it needs a mirror backup server in case of any type of incident.
All this can be due to the following deficiencies:
- The lack of training, awareness and sensitization in Information Security, especially in audits and good practices can cause negligence in the actions of the personnel and increase the level of risk on the organization. (It is recommended to train the employees of systems in these practices).
- The current Information Security normative body in Distribuciones Mariano is not able to reflect any action and casuistry that can be performed on the treated information, since it depends on the support provided by the service. The lack of information leakage control sanctions could cause important vulnerabilities in the information security, the company's business object and in its reputation.
- There is a lack of global and formal definition of roles, responsibilities and incompatibilities, capable of constituting the necessary basis to maintain the Information Security and to be able, in this way, to define a non-compliance framework based on the applicable regulatory body and legislation in force.
- The need for a backup server has been detected in certain contractual cases.
- A deficient level of security has been identified in remote accesses.
- The lack of a continuous audit process, which can be carried out by systems employees.
For all these reasons, we suggest implementing a series of organizational, procedural, technical and contractual actions, both internal, as well as models of relationship and supervision of suppliers (third parties) in order to avoid, among others, possible information leaks or failures in the security of the same. The following graph shows the current level of compliance in each of the areas that make up Annex A of ISO/IEC 27001 (Information Security Management System). This level of compliance has been calculated based on the following values:

![image-20200519201954045](/assets/images/iso-sample/iso-sample-3.PNG)

## Development of the tasks
For the development of the Risk table, I use the slides where we are given an example of generic EDR tables taking into account 5 columns which are Risk, Control Objective, Control, Compliance Test and Substantive Test. Additionally the threats that I have in consideration will be obtained from the risk table obtained from Emarisma for ISO 27001. This table will be inside my annexes but I will not be able to reference it since it belongs to the tool.
Due to the fact that this audit plan is focused on Access, DB and DPC Security, the most important risks for these criteria will be considered. 

| Risk                                                  | Control Objective                                                                                                                                          | Control                                                                                                                          | Compliance Test                                                                                                                                                                    | Test substantive                                                                                                                                         |
|-------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------|
| [A.10] Unauthorized Access (ACCESSES)                 | The Information Systems Systems Department should establish permission-based access policies for access to data and computer systems.                      | Logical data access procedures include the review and approval of user profiles based on their characteristics and requirements. | Verify that a written procedure is in place to subject all access profiles to an approvals process, and that it has been communicated to all involved or interested areas.         | Select a sample of profiles and identify those that have not been adequately reviewed and approved, assessing the impact/risk of the incidents detected. |
| [A.5] User Impersonation (Access)                     | The systems department shall establish access policies that are based on user access verification that indicates that the user is who he/she claims to be. | Logical data access procedures include review and confirmation of user profiles when accessing the platform.                     | Verify that a procedure has been implemented that allows the evaluation of user verification when accessing their accounts.                                                        | This type of checks can be performed by means of digital signatures or biometric devices that allow access control.                                      |
| [A.6] Abuse of Access Privileges (Access)             | The Information Systems Systems Department should establish permission-based access policies for access to data and computer systems.                      | Logical access procedures to certain restricted functions of the systems approval of user profiles based on permissions.         | Check that a written procedure is in place to subject all access profiles to an approvals process, and that it has been communicated to all involved or interested areas.          | Such checks can be performed by verifying privilege escalation of user accounts.                                                                         |
| [A.4] Manipulation of configuration (Access and DB's) | The systems department must ensure that there is no additional configuration by the third party service, which provides maintenance.                       | Backdoor access procedures to certain restricted functions of internal systems or important data.                                | Verifying that a written procedure is in place to submit all configurations is a testing process.                                                                                  | This type of testing can be done using tools that monitor access control.                                                                                |
| [A.19] Disclosure of information (DB)                 | The systems department must ensure that there is no disclosure of information.                                                                             | Restricted information procedures and maintain user confidentiality.                                                             | Check that a written procedure is in place to subject all workers to non-disclosure of DB information.                                                                             | This type of checks can be performed using tools that monitor the control of services.                                                                   |
| [A.7] Unintended use                                  | The Systems department shall ensure that no unintended misuse of user information is made.                                                                 | Restricted information procedures and maintain the confidentiality of relevant user information.                                 | Check that a written procedure has been implemented to subject all workers to not using DB information in processes for which they are not intended.                               | This type of checks can be performed using tools that monitor the use of data by knowing where it is being referenced.                                   |
| [N.2] Water damage                                    | The IT department must ensure that there is no way for the DPC to be flooded, taking into account architectural issues and physical reviews.               | Control and backup procedures in the event of water damage to the data center.                                                   | Check that a procedure has been implemented for the protection of the DPC against water damage or the backup of the DPC in case it happens in order to have the service available. | This type of checks can be done by physical checks or by having a backup mirror server if necessary.|

## Action Plan

| Control | Code | Suggestion | Term |
|------------------|-------|-------------------------------|------------|
| Asset Management | Reco1 | Access control implementation | Short term |

Description of the recommendation

The implementation of user access control should be taken into consideration to verify that permissions are being well controlled, this is done by verifying the accesses to the system.

Actions

- Identification of the types of permissions handled.
- Identification of the permissions per system.
- Inventory all types of access to access the systems.

Benefits

- Significant improvement in the security of access to the systems. 

| Control | Code | Suggestion | Term |
|------------------|-------|-------------------------------|------------|
| Asset Management | Reco2 | Implementation of user identity verifier (Accesses) | Medium term |

Description of the recommendation

It is verified that the implementation of access control to manage user identity should be taken into consideration.

Actions

- Identification of the access process to a given system
- Identification of how the identity of a user is checked.
- Inventory all access processes
- Enable access through digital signatures or biometric devices.
  
Benefits

- Significant improvement in system access security

| Control | Code | Suggestion | Term |
|------------------|-------|-------------------------------|------------|
| Asset Management | Reco3 | Implementation of user privilege verifier | Medium term |

Description of the recommendation

The implementation of access control to manage user privileges should be taken into consideration.

Actions

- Identification of user permissions and privileges
- Identification of privilege escalation.
- Mapping system servers with vulnerability and privilege escalation tools.
  
Benefits

- Significantly improves access through privileges 

| Control | Code | Suggestion | Term |
|------------------|-------|-------------------------------|------------|
| Information Management | Reco4 | Configuration Manipulation checker implementation | Short term |

Description of the recommendation

It is verified that the implementation of control of to verify configuration manipulation should be taken into consideration.

Actions

- Identification of server configurations
- Block access to server permissions settings for third party service.
- Map accesses to information and logs of entries and executions by third parties.
 
Benefits

- Significantly improves the failures that can occur when a third party has access to non-displayed tools. 

| Control | Code | Suggestion | Term |
|------------------|-------|-------------------------------|------------|
| Information Management | Reco5 | Configuration Manipulation checker implementation | Short term |

Description of the recommendation

It is found that the implementation of control of to verify configuration manipulation should be taken into consideration.

Actions

- Identification of server configurations
- Block access to server permissions settings for third party service.
- Map accesses to information and logs of entries and executions by third parties.

Benefits

- Significantly improves bugs and vulnerabilities that can occur when a third party has access to tools that they should not.

| Control | Code | Suggestion | Term |
|------------------|-------|-------------------------------|------------|
| Information Management | Reco6 | Implementation of policies against Disclosure of information (BBDD) | Short term |

Description of the recommendation

It is verified that the implementation of an organizational policy against the disclosure of information to workers and the contract with the third party service that provides maintenance should be taken into consideration.

Actions

- Identification of current policies on information disclosure.
- Map the accesses to information and users who have access to sensitive information that could at some point affect customers.
- Create objective sanctions for users who disclose information depending on the degree of disclosure.
  
Benefits

- Condition users who violate the rules to have a present responsibility for the stipulated policies. 

| Control | Code | Suggestion | Term |
|------------------|-------|-------------------------------|------------|
| Technology Management | Reco7 | Deployment of mirrored backup servers when having Water Damage | Short term |

Description of recommendation

Consideration of implementing a mirrored server if water damage were to occur is tested.

Actions

- Identify the physical area of the DPC
- Identify if there are any architectural or visually verifiable flaws.
- Identify the physical location of the DPC.
- Create a mirror server for the DB that receives backups of the DB day.
- Implement a contingency policy and deploy the backup server in case of water damage.

Benefits

- Allows to provide almost immediate availability in case of server failure.
- Allows the company's service not to be down if something were to happen. 

## Annexes

Planning

Next, we will detail the time and resources that will be needed for the development of the audit. Two auditors will be required to travel to Distribuciones Mariano's facilities between the months of June and September 2022.
BeAuditors, through the Account Manager, is committed to the 2 auditors meet the following requirements:
Senior Auditor
- Degree in Computer Engineering/Telecommunications. 5 years or more of experience in performing technology audits.
- Possess any of the following certifications: CISM, CISP, CISA, PMP, ISO Lead Auditor 27001, CSA STAR Certification, Lead Auditor 22301 and ITIL. Distribuciones Mariano undertakes to provide the necessary equipment and tools for the performance of the technological audit to the external personnel that will travel to its facilities.
Junior Auditor
- Degree in Computer Engineering/Telecommunications. 1 year or more of experience in performing technology audits.
- Possess any of the following certifications: eJPT, eJPTx, OSCP, OCISM, CISP, CISA, PMP, ISO Lead Auditor 27001, CSA STAR Certification, Lead Auditor 22301 and ITIL.
  
Distribuciones Mariano is committed to provide the necessary equipment and tools to carry out the technological audit to the external personnel that will travel to its facilities.
It consists of 2 computers with good processor and memory, 2 monitors, access to the Internet and the company's network, tools such as ACL, Visio, Nessus, OWASP ZAP, etc. 
Phases during the development of the Audit:
1) Opening: opening meeting where the objectives and the bulk of the activities proposed to be carried out in the framework of the fulfillment of the audit objective are explained.
of the audit objective 
- Identification of potential risks: a first approach is made to the risks already mentioned in this audit by the approach is requested as part of the process of the web portal itself (Inherent) and those that are external but can place risks in the established processes.
2) Identification of controls (strong and weak): Study of the controls in place at the current stages of the process and their degree of influence on it. A value is given on how these are being considered.
![image-20200519201954045](/assets/images/iso-sample/iso-sample-4.PNG)
3) Selection of the tests and techniques and methodology to be used: based on the previous information, it is established which of these will allow the fulfillment of the objectives depending on the particularities of the processes that are executed for the fulfillment of the portal's mission and vision. In the current case, vulnerability scanning tools such as owasp zap, burpsuite, Nessus, etc. would be used. Log reviews would also be done from monitoring tools. Patterns of privilege escalation attacks would be established according to the permissions held. And ultimately the CPD checklist verifications.
4) Detailed planning of activities: each activity is detailed in terms of human, technical and economic resources to be allocated according to time. 
5) Testing, meetings with the person in charge, interviews and obtaining results: execution of the proposed activities according to the established methodology. At this stage, the results obtained from the application of the control procedures and the tests carried out will be obtained in order to determine whether or not the control objectives defined above have been met. The data obtained will be recorded in spreadsheets made to measure for each procedure in order to have the results perfectly catalogued with the objective of facilitating their interpretation and avoiding erroneous interpretations.
6) Record of tests: Record taking of each of the tests that are required as part of the Annex of the report to determine the necessary improvement actions.
7) Conclusions and comments: The summary of the analysis of the activities, tests and methodology is framed to determine the corrective actions or improvements to be implemented in the framework of the results obtained. In this step the summary of all the information obtained will be detailed, as well as what is derived from that information, be it security, organizational or business structure failures.
8) Document reviews and closure: A review of the documents generated and / or obtained as part of the documentary heritage of the audit is performed.
9) Drafting of the preliminary audit report: a first draft of the report containing a version control is made so that both the data obtained and the comments generated are fed back by the actors of the processes in order to enter their adjustments or suggestions, mitigating a possible error of interpretation.
10) Provision of preliminary version: a first version of the report is generated with the consolidation of all the information obtained.
11) Conceptualization of the direct participants: the opportunity is given for a light review of the people who participated in the audit.
12) Preparation of the final audit report: the preliminary report is taken and the observations received from those involved in the previous stage are analyzed and, if applicable, incorporated into the final audit report.
13) Preparation of high-level audit report: based on the consolidation obtained in the previous phase, an executive report is generated to be presented to the high-level management of Distribuciones Mariano.
14) Final version control record (final version): a final version of the audit report is generated and assigned the final version control sequential that will be delivered as the final product of the process.
15) Final meeting and document delivery: This is the last part of the audit and a meeting is held to formalize the delivery of the final report with the results obtained in the audit. Below is an image that contains the proposed phases for the development of the methodology and the planned times for the execution of the same, in consideration of what has been proposed should be taken into account:
  
![image-20200519201954045](/assets/images/iso-sample/iso-sample-5.PNG)

## GDPR

![image-20200519201954045](/assets/images/iso-sample/iso-sample-6.PNG)

![image-20200519201954045](/assets/images/iso-sample/iso-sample-7.PNG)

## Risks 27001

![image-20200519201954045](/assets/images/iso-sample/iso-sample-8.PNG)

![image-20200519201954045](/assets/images/iso-sample/iso-sample-9.PNG)


