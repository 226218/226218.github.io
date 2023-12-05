---
layout: single
title: Appointment - Hack The Box
excerpt: "Appointment is a machine of Starting Point of HTB. The machine has a PHP web app and the objetive is find a command injection vulnerability in the site to claim the flag."
date: 2023-08-13
classes: wide
header:
  teaser: /assets/images/htb-appointment/appointment_logo.png
  teaser_home_page: true
  icon: /assets/images/hackthebox.webp
categories:
  - hackthebox
  - sql_injection
tags:
  - php
  - mysql
  - injection
  - A03:2021
---

![](/assets/images/htb-appointment/appointment_logo.png)

Appointment is a machine of Starting Point of HTB. The machine has a PHP web app and the objetive is find a command injection vulnerability in the site to claim the flag.

## 1st HTB Task Solving

The initials goals of the HTB in this Starting Point are connect with the machine. We only need download vpn and connect with OVPN. Later, for the first task is about the name of SQL, that is an acronym of "Structured Query Language". The second task is the name of one the most common vulnerability, as it begin with three letters, the response is "SQL injection".

![image-20200519201954045](/assets/images/htb-appointment/answer.png)

## 2nd HTB Task Solving

The third task is about the classification of the vulnerability SQL injection in 2021 Owasp Top 10. The correct name of this classification is "A03:2021-Injection".

![image-20200519201954045](/assets/images/htb-appointment/answer1.png)

## 3rd HTB Task Solving

In the fourth task we need response which version of Apache has the machine, i got it using nmap -sV (Probe open ports to determine service/version info) -sC (equivalent to --script=default, it is using all defaults scrips of the nmap ) -p- (search in all ports) -T4 (it is the time for the requests, in the case of T5 is very aggresive and makes paranoic attack) IP (finally the IP of the objective machine is "10.129.108.144" ).

![image-20200519201954045](/assets/images/htb-appointment/answer5.png)

I got the response for the task 4. "Apache httpd 2.4.38 ((Debian))"

![image-20200519201954045](/assets/images/htb-appointment/answer2.png)

## 4th HTB Task Solving

The standar port used for the HTTPS protocol is an easy response using google "443". Because the old common port was 80, but when we used only HTTP, currently the most common port for HTTP-S (http secure) is the port 443. The next task is the name for the folders in web applications, it is a word than finally with y, the most accurate response is "directory". 

![image-20200519201954045](/assets/images/htb-appointment/answer3.png)

## 5th HTB Task Solving

The 7th task is about the number of Not Found web errors, it is the most common "404", i like programmer saw this kind of errors. The next task is about discover directories and not subdomains using Gobuster. It is visible using command --help in Gobuster and the correct response is "dir".

![image-20200519201954045](/assets/images/htb-appointment/answer4.png)

## 6th HTB Task Solving

We used all previous commands mentioned in this document.

![image-20200519201954045](/assets/images/htb-appointment/answer5.png)

![image-20200519201954045](/assets/images/htb-appointment/answer6.png)

## 7th HTB Task Solving

We founded a web called LOG IN and how it is part of injection information, we only need use the most common users in this case "admin" + "/common injections strings like -- '#"  and for the password we use whatever password because we are doing SQL Injection.  

![image-20200519201954045](/assets/images/htb-appointment/answer7.png)

## 8th We founded the flag

We used the last credentials and we got the flag

![image-20200519201954045](/assets/images/htb-appointment/answer8.png)

## Last step

Finally the last step is to put all the answers how the word and the flag.

![image-20200519201954045](/assets/images/htb-appointment/answer9.png)
