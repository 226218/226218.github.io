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

| Risk                                                  | Control Objective                                                                                                                                          | Control                                                                                                                          | Compliance Test                                                                                                                                                            | Test substantive                                                                                                                                         |
|-------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------|
| [A.10] Unauthorized Access (ACCESSES)                 | The Information Systems Systems Department should establish permission-based access policies for access to data and computer systems.                      | Logical data access procedures include the review and approval of user profiles based on their characteristics and requirements. | Verify that a written procedure is in place to subject all access profiles to an approvals process, and that it has been communicated to all involved or interested areas. | Select a sample of profiles and identify those that have not been adequately reviewed and approved, assessing the impact/risk of the incidents detected. |
| [A.5] User Impersonation (Access)                     | The systems department shall establish access policies that are based on user access verification that indicates that the user is who he/she claims to be. | Logical data access procedures include review and confirmation of user profiles when accessing the platform.                     | Verify that a procedure has been implemented that allows the evaluation of user verification when accessing their accounts.                                                | This type of checks can be performed by means of digital signatures or biometric devices that allow access control.                                      |
| [A.6] Abuse of Access Privileges (Access)             | The Information Systems Systems Department should establish permission-based access policies for access to data and computer systems.                      | Logical access procedures to certain restricted functions of the systems approval of user profiles based on permissions.         | Check that a written procedure is in place to subject all access profiles to an approvals process, and that it has been communicated to all involved or interested areas.  | Such checks can be performed by verifying privilege escalation of user accounts.                                                                         |
| [A.4] Manipulation of configuration (Access and DB's) | The systems department must ensure that there is no additional configuration by the third party service, which provides maintenance.                       | Backdoor access procedures to certain restricted functions of internal systems or important data.                                | Verifying that a written procedure is in place to submit all configurations is a testing process.                                                                          | This type of testing can be done using tools that monitor access control.                                                                                |

## 6th Step to Solving

We added the dns of the target machine

![image-20200519201954045](/assets/images/htb-keeper/answer-5.png)

## 7th Step to Solving

We joined to the real website of the target machine

![image-20200519201954045](/assets/images/htb-keeper/answer-6.png)

## 8th Step to Solving
We used the tool nuclei for did pentesting in websites and another services

![image-20200519201954045](/assets/images/htb-keeper/answer-7.png)

## 9th Step to Solving

We tried to connect with the service ssh using anonymous credentials 

![image-20200519201954045](/assets/images/htb-keeper/answer-8.png)


 
## Second Flag 

Finally we putted the second flag in HTB

![image-20200519201954045](/assets/images/htb-keeper/answer-32.png)



