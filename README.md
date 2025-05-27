# Task-2-Analyze-a-Phishing-Email-Sample

## Introduction
In this project, you will learn how to analyze phishing emails, Phishing email analysis is a critical cybersecurity practice that involves systematically examining emails suspected of being fraudulent to identify and mitigate threats. This process helps organizations understand the tactics used by cybercriminals, enhance email security protocols, and protect sensitive information. By analyzing email content, sender details, and technical markers, analysts can identify common phishing techniques like spoofed addresses, urgent language, and suspicious attachments. 

## Pre-requisites
- Basic understanding of phishing concepts.
- Knowledge on how to use online header analyzer.


## Tasks
In Online free tools


# Analyze a Phishing Email Sample
**. Objective:** Identifying phishing characteristics in a suspicious email sample.
**. Tools:** Email client or saved email file(text),free online header analyzer.

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

Find publicly available examples on trusted cybersecurity blogs or security awareness sites.
- 📨 [Download Email Sample (.eml)](https://github.com/RohitaBokam/Task-2-Analyze-a-Phishing-Email-Sample/blob/main/sample.eml)  
  

<img width="957" alt="image" src="https://github.com/user-attachments/assets/a73ba6ce-6103-422e-841b-b75cef441179" />


## 2.Examine sender's email address for spoofing.

Look for:
*Minor misspellings(e.g.,support@paypa1.com instead of paypal.com).

<img width="959" alt="image" src="https://github.com/user-attachments/assets/adcf3f83-c1fb-4884-82fd-b3e69bf75f57" />


## 3.Run: nmap -sS 192.168.1.0/24 to perform TCP SYN scan

<img width="959" alt="image" src="https://github.com/user-attachments/assets/074d5c29-c600-4bc0-982f-c949d65adb24" />


## 4.Note down IP addresses and open ports found.

**. Detailed Results :**

192.168.29.66 -  this port is typically used for DNS (Domain Name System)

All 1000 scanned ports are filtered

Port 3306/tcp is filtered 

192.168.29.246

The remaining 999 ports are closed, which means the system received the request but actively rejected the connection

192.168.29.178

All 1000 scanned ports are filtered

This is most likely a router or firewall-protected device that blocks incoming scan requests

192.168.29.178 (Your own system)

All 1000 scanned ports are in ignored state.

This indicates that the scan reached the system, but all ports rejected the connection attempts

## 5.Optionally analyze packet capture with Wireshark

<img width="959" alt="image" src="https://github.com/user-attachments/assets/975ec83d-1f68-4560-978e-5172923c16ac" />


## 6.Research common services running on those ports.

there is no services running because off no port is running

## 7.Identify potential security risks from open ports.

i have nothing found suspicious on this services because off no port is open

## 8.Save scan results as a text or HTML file.

here i save these output in test file like nmap.txt

comand;

> nmap -sS 192.168.117.0/24 -oN nmap.txt
> 

<img width="958" alt="image" src="https://github.com/user-attachments/assets/510e14d7-f53d-4486-a906-c3a533ab4acc" />


scan of result in nmap.txt file

<img width="956" alt="image" src="https://github.com/user-attachments/assets/b4dccba8-0fea-4759-a120-33a3d173c22b" />


