# SOC-Fundamentals_practice
This repository contains my hands-on SOC analyst training projects from LetsDefend and TryHackMe, including log analysis, EDR, Threat intelligence feed, SOAR.

 Case 1: Brute Force Detection on VPN
 Platform: LetsDefend
 Scenario: Login failure alert from one source IP with many different accounts.
 Action: Investigated logs, confirmed brute force attempt.
 Learning: Importance of identifying failed login patterns.


 Case 2: RDP Brute Force Detected
 Platform: LetsDefend
 Scenario: Login failure alert from one source IP with many user name accounts.
 Action: Investigated logs, confirmed brute force attempt.
 Learning: Importance of identifying failed login patterns, lerning external threat through log management.

  Case 3: Hacking website in legal  eniroment to depost funds
 Platform: TryHackMe (intro to offensive security)
 Scenario: Brute force attack to find hidden features used for depositing funds.
 Action:  Use Dirb tool to find hidden webpages, testing them one by one until find correct one and depost money.
 Learning:Understood how hidden directories can expose functionality (forms, upload pages) that increase attack surface.
  
 
 Case 4: Simulated SOC investigation using SIEM
 Platform: TryHackMe (intro to defensive security)
 Scenario: Investigation of malicious IP address by scanning tools
 Action:  Detected malicious activity, investigated IP addresses via scanning tools, and escalated to block malicious IPs as part of the incident response workflow.” 
 Learning: Understand Importance of Detection , investigation and response.



 Cases 5:
 
 Platform: 1- Completed TryHackMe rooms 
 Cyber kill chain(learned about the 7 stages of an attack), Unified Cyber kill chain(explored how multiple attack chains map together to cover persistence, privilege escalation, and defense evasion.)
 
2- LetsDefend SOC Case
 //////This alert was investigated in LetsDefend (training SOC environment). All hostnames/IPs are part of the simulated lab environment no real data exposed. 
 
 Investigated a Privilege Escalation alert in LetsDefend’s monitoring section.
 Queried EDR logs for suspicious process (svohost.exe).
 Analyzed parent process, file path, command line, and hash values.
 Learned how to determine if an alert is true positive vs false positive.
 Folder documents a case study with screenshots, notes including Investigation, IOC, Timeline and mitigation steps.






 

 
