# Task-2-Analyze-a-Phishing-Email-Sample

## Introduction
In this project, you will learn how to analyze phishing emails, Phishing email analysis is a critical cybersecurity practice that involves systematically examining emails suspected of being fraudulent to identify and mitigate threats. This process helps organizations understand the tactics used by cybercriminals, enhance email security protocols, and protect sensitive information. By analyzing email content, sender details, and technical markers, analysts can identify common phishing techniques like spoofed addresses, urgent language, and suspicious attachments. 

## Pre-requisites
- Basic understanding of phishing concepts.
- Knowledge on how to use online header analyzer.


## Tasks
In Online free tools


## Analyze a Phishing Email Sample
**Objective:** Identifying phishing characteristics in a suspicious email sample.

**Tools:** Email client or saved email file(text),free online header analyzer.

## 🛠️ **Lab Setup**

- 📨 [Download Email Sample (.eml)] (https://github.com/RohitaBokam/Task-2-Analyze-a-Phishing-Email-Sample/blob/main/sample.eml)
- 💻 Tools Recommended:
  - [MX Toolbox Email Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx)
  - [EML Analyzer](https://eml-analyzer.herokuapp.com/#/)
  - IP reputation check (e.g., VirusTotal, AbuseIPDB, Cisco Talos)
  - Whois lookup (e.g., whois.domaintools.com)
  - URL and Domain analysis (e.g., urlscan.io, VirusTotal)

## Lab Task :Analyze the Suspicious Email
-📥 Scenario:
You received an email from BANCO DO BRADESCO LIVELO claiming that your card has 92,990 points expiring today, sent from banco.bradesco@atendimento.com.br.


## 1. Obtain a sample phishing email(many free samples online)

**Find publicly available examples on trusted cybersecurity blogs or security awareness sites.**
- 📨 [Download Email Sample (.eml)](https://github.com/RohitaBokam/Task-2-Analyze-a-Phishing-Email-Sample/blob/main/sample.eml)  
  

<img width="957" alt="image" src="https://github.com/user-attachments/assets/a73ba6ce-6103-422e-841b-b75cef441179" />


## 2.Examine and Analyze the sender's email address for spoofing.

Look for:
**Minor misspellings(example:support@ paypa1.com instead of paypal.com). :**
Use: [EML Analyzer](https://eml-analyzer.herokuapp.com/#/)
Step 1: Drag and Drop the email text file by downloading the raw file of sample.eml(https://github.com/RohitaBokam/Task-2-Analyze-a-Phishing-Email-Sample/blob/main/sample.eml)  
  
<img width="777" alt="image" src="https://github.com/user-attachments/assets/4e3770d1-8f68-49ad-9bf9-1165d8bc0d8d" />


**Examining the sender's email:**

<img width="955" alt="image" src="https://github.com/user-attachments/assets/c1787136-8077-4920-b88f-d2daea79ba55" />




## 3.Identify Suspicious Links or Attachments
**Hover over links to see actual URLs(don't click them).**

<img width="953" alt="image" src="https://github.com/user-attachments/assets/7a30ebee-a972-411a-8abe-1ff3fb26bcfb" />



## 4.Look for urgent or threatning language in the email body
**Common phrases:Example:"Your account will be suspended".etc...**


## 5.Note mismatched URLs:

**Compare visible text with actual URL.**


## 6.Checking for Spelling mistakes and Grammar Errors:

**Many phishing emails contain:**
**1.Awkward phrasing**
**2.Typos**
**3.Misused punctuation**

## 7.Summarizing phishing traits found in the email:
 **To create a phishing traits checklist**
**1.Spoofed sender IP address:137.184.34.4**
<img width="955" alt="image" src="https://github.com/user-attachments/assets/14f93b41-6b86-43d8-ac95-d7af0e25a9d4" />

**2.Bad header authentication**
<img width="957" alt="image" src="https://github.com/user-attachments/assets/99b3ead0-90f2-4bea-b099-6f0b86692611" />

**3.Malicious or Mismatched link**
<img width="953" alt="image" src="https://github.com/user-attachments/assets/7a30ebee-a972-411a-8abe-1ff3fb26bcfb" />

**4.Total virus scanning**
To check the sender IP address is blacklisted by using:VirusTotal(https://www.virustotal.com/gui/home/upload)

<img width="947" alt="image" src="https://github.com/user-attachments/assets/ac3dd316-6fcf-430e-8feb-444219081fd9" />

## Result of the IP address shows that the phishing indicators found and the security vendor flagged this IP address as malicious .
