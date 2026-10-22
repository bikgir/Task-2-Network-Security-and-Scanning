# Task-2-Network-Security-and-Scanning
**Nmap Scan Report and OpenVAS Vulnerability Assessment**
**1.	Executive Summary**
This report presents the results of network reconnaissance and vulnerability-assessment activities conducted in an authorized virtual lab for educational purposes. The assessment used Kali Linux to scan the Metasploitable-2 target at 10.0.0.6 within the 10.0.0.0/24 lab network.

Nmap was used to discover active hosts, identify open ports, detect service names and versions, estimate the target operating system, and enumerate SMB user accounts. The scan identified numerous exposed services, including FTP, SSH, Telnet, SMTP, HTTP, SMB, MySQL, PostgreSQL, VNC, and other network services. Several services were identified as running legacy software versions that require further security review.

The report also includes evidence from the OpenVAS vulnerability-assessment interface. The findings provide a basis for identifying potential security weaknesses and recommending remediation. However, detected services and version information alone do not establish that a system is exploitable; findings should be validated and prioritized before remediation.



**2.	Objective**
The primary objective of this assessment was to develop practical skills in network reconnaissance, service enumeration, and vulnerability assessment within a controlled virtual lab.

The specific objectives were to:

•	Discover active hosts on the lab network.

•	Identify open TCP ports and associated services.

•	Determine service names and software versions using Nmap.

•	Estimate the target operating system.

•	Practice TCP SYN and FIN scanning techniques.

•	Enumerate SMB user accounts to understand information exposure
.
•	Review the OpenVAS vulnerability-assessment interface and available findings.

•	Identify potential security weaknesses and recommend appropriate mitigation measures.

