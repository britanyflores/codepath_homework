# Project 9 - Pentesting Live Targets

Time spent: 5 hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:

* Username Enumeration
* Insecure Direct Object Reference (IDOR)
* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Session Hijacking/Fixation

Each color is vulnerable to only 2 of the 6 possible exploits. First discover which color has the specific vulnerability, then write a short description of how to exploit it, and finally demonstrate it using screenshots compiled into a GIF.

## Blue

Vulnerability #1: SQL Injections

Description: Website wasn't sanitized properly, we can manipulate the website and make it sleep using OR in the SQL injection

<img src="blue-vuln1.gif">


## Green

Vulnerability #1: Cross-site scripting 

Description: the website doesn't have protection agains XSS attacks in their feedback form

<img src="green-vuln1.gif">



## Red

Vulnerability #1: Insecure Direct Object Reference 

Description: Information can be access about salesperson that is not permitted, this can be done through the GET method and changing the user ID

<img src="red-vuln1.gif">




## Notes

It was difficult to identify the SQL Injection and get it to work
