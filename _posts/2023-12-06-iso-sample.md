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

## Scope

The scope of this document will focus, as previously mentioned in the objectives, on 3 pillars.
objectives, in 3 pillars, which are:
  - Audit on accesses
  - Audit on DB
  - DPC security.
Thus, each of these should go hand in hand with the controls presented,
This will ensure that an audit of the same can be carried out in the subsequent term, as defined.
of the same, with the defined.

![image-20200519201954045](/assets/images/htb-keeper/answer-2.png)

## 4th Step to Solving

nmap consult for get the version of the service and more information using the command -sV

![image-20200519201954045](/assets/images/htb-keeper/answer-3.png)

## 5th  Step to Solving

We join to the website in the target machine

![image-20200519201954045](/assets/images/htb-keeper/answer-4.png)

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

## 10th Step to Solving

We founded information about the target machine, it is the name of the service server called "Request Tracker -- Best Practical" 

![image-20200519201954045](/assets/images/htb-keeper/answer-9.png)

## 11th Step to Solving

We search in the website exploit-db about request tracker

![image-20200519201954045](/assets/images/htb-keeper/answer-10.png)

## 12th Step to Solving

We founded a sql-injection method

![image-20200519201954045](/assets/images/htb-keeper/answer-11.png)

## 13th Step to Solving

We search if exist default credentials in google

![image-20200519201954045](/assets/images/htb-keeper/answer-12.png)

## 14th Step to Solving

We founded default credentials root and password

![image-20200519201954045](/assets/images/htb-keeper/answer-13.png)

## 15th Step to Solving

We joined to the system website of the target machine

![image-20200519201954045](/assets/images/htb-keeper/answer-14.png)


## 16th Step to Solving

We searched another credentials for the service ssh and founded the password 2023! for the user lnorgaard

![image-20200519201954045](/assets/images/htb-keeper/answer-15.png)

![image-20200519201954045](/assets/images/htb-keeper/answer-16.png)

![image-20200519201954045](/assets/images/htb-keeper/answer-17.png)
 
## 17th Step to Solving

We joined to the service ssh
![image-20200519201954045](/assets/images/htb-keeper/answer-18.png)

![image-20200519201954045](/assets/images/htb-keeper/answer-19.png)
 
## 18th The First flag
We founded the first flag
![image-20200519201954045](/assets/images/htb-keeper/answer-20.png)
 
## 19th The First flag

We founded a .dmp file with the database information

![image-20200519201954045](/assets/images/htb-keeper/answer-21.png)

![image-20200519201954045](/assets/images/htb-keeper/answer-22.png)

![image-20200519201954045](/assets/images/htb-keeper/answer-23.png)
 
## 20th Step to Solving

We used a program in py trying to open the dmp file
![image-20200519201954045](/assets/images/htb-keeper/answer-24.png)
 
## 21th Step to Solving

![image-20200519201954045](/assets/images/htb-keeper/answer-25.png)
 
![image-20200519201954045](/assets/images/htb-keeper/answer-26.png)

![image-20200519201954045](/assets/images/htb-keeper/answer-27.png)

![image-20200519201954045](/assets/images/htb-keeper/answer-28.png)
 
## 22th Step to Solving

We founded a Putty-user-key session ssh-rsa

![image-20200519201954045](/assets/images/htb-keeper/answer-29.png)
 
## 23th Step to Solving

We search how to change ssh-rsa to ssh session 

![image-20200519201954045](/assets/images/htb-keeper/answer-30.png)
 
## 24th Step to Solving

Finally we joined to the root user in the target machine keeper
![image-20200519201954045](/assets/images/htb-keeper/answer-31.png)
 
## Second Flag 

Finally we putted the second flag in HTB

![image-20200519201954045](/assets/images/htb-keeper/answer-32.png)



