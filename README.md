# week8codepath
# Project 8 - Pentesting Live Targets

Time spent: **6** hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:
* Username Enumeration
* Insecure Direct Object Reference (IDOR)
* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Session Hijacking/Fixation

Each version of the site has been given two of the six vulnerabilities. (In other words, all six of the exploits should be assignable to one of the sites.)

## Blue

Vulnerability #1: __________________

Vulnerability #2: __________________


## Green

Vulnerability #1: Username Enumeration

<img src="https://i.imgur.com/kzUvlAb.gif" width="800">

  Steps:
  * Only in the green site
  * Type in `jmonroe99` into the username input box with a random password
  * Look at the pop up alert text
  * If the input field contains `jmonroe99` the alert text is **bold**
  * If the input field contains any other username; the alert text is not bold
    
  Notes:
  * Different class is called when there is a incorrect username input
    

Vulnerability #2: __________________


## Red

Vulnerability #1: __________________

Vulnerability #2: __________________


## Notes

Describe any challenges encountered while doing the work
