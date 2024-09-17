# tryhackme-projects
This repository contains documentation of completed rooms on TryHackMe cybersecurity challenges
## Completed Rooms:
Room 1: FakeBank Application Hacking on TryHackMe
Date: September 2024
Objective: Execute a command-line application to brute-force FakeBank’s website to find hidden directories and pages
  
Tools Used:
- GoBuster
  
Step-by-Step Process:
1. Used terminal to execute command-line and interact with computer
2. Used GoBuster to find hidden pages on FakeBank’s website 
gobuster -u http://fakebank.com -w wordlist.txt dir
3. Discovered a secret bank transfer page and inputted the hidden page into FakeBank website
4. Gained access into the bank account and transferred $2000 from the bank account 

Results:
- Captured the flag by gaining access into the bank account and successfully transferring money out of the account
- Learned about GoBuster and its common usage scenarios in the real-world applications
