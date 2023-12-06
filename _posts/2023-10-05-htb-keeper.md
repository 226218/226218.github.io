---
layout: single
title: Keeper - Hack The Box
excerpt: "Keeper is a machine of HTB. The machine has a Website with nginx WAF, for this reason has access limited, later u can join to the system with default credentials, later get the password of an user lisa for the connection ssh, later download the .dmp file and recovery old session, next using the old session with private-openssh ssh service join like root."
date: 2023-10-05
classes: wide
header:
  teaser: /assets/images/htb-keeper/keeper_logo.png
  teaser_home_page: true
  icon: /assets/images/hackthebox.webp
categories:
  - hackthebox
  - SSH
  - Default Credentials
  - Nginx
  - Weak Credentials
tags:
  - Nginx
  - HTTP
  - SSH
  - Nginx
  - WAF
  - dmp credentials
  - Privilege Escalation
  - Vulnerable and Outdated Components
  - A06:2021
---

![](/assets/images/htb-keeper/keeper_logo.png)

Keeper is a machine of HTB. The machine has a Website with nginx WAF, for this reason has access limited, later u can join to the system with default credentials, later get the password of an user lisa for the connection ssh, later download the .dmp file and recovery old session, next using the old session with private-openssh ssh service join like root.

## 1st HTB VPN connection

The initials goals of the HTB in this Starting Point are connect with the machine. We only need download vpn and connect with OVPN

![image-20200519201954045](/assets/images/htb-keeper/answer-0.png)

## 2nd Step to Solving

Create the folder for the machine Keeper

![image-20200519201954045](/assets/images/htb-keeper/answer-1.png)

## 3rd Step to Solving

Scanning all open ports and get two services open in the target machine 22/TCP and 80/TCP, a service ssh and service http

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
 
## 20th The First flag

We used a program in py trying to open the dmp file
![image-20200519201954045](/assets/images/htb-keeper/answer-24.png)
 
## 21th The First flag

![image-20200519201954045](/assets/images/htb-keeper/answer-25.png)
 
![image-20200519201954045](/assets/images/htb-keeper/answer-26.png)

![image-20200519201954045](/assets/images/htb-keeper/answer-27.png)

![image-20200519201954045](/assets/images/htb-keeper/answer-28.png)
 
## 22th The First flag

We founded a Putty-user-key session ssh-rsa

![image-20200519201954045](/assets/images/htb-keeper/answer-29.png)
 
## 23th The First flag

We search how to change ssh-rsa to ssh session 

![image-20200519201954045](/assets/images/htb-keeper/answer-30.png)
 
## 24th The First flag

Finally we joined to the root user in the target machine keeper
![image-20200519201954045](/assets/images/htb-keeper/answer-31.png)
 
##Answer

Finally we putted the flag in HTB

![image-20200519201954045](/assets/images/htb-keeper/answer-32.png)



