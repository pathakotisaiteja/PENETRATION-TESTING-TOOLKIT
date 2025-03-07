# PENETRATION-TESTING-TOOLKIT
# CODTECH-AD-TASK3
BUILD A TOOLKIT WITH MULTIPLE MODULES (E.G., PORT SCANNER, BRUTE-FORCER) FOR PENETRATION TESTING.

# PERSONAL DETAILS
Name : Pathakoti saiteja

Company : CODTECH IT SOLUTIONS

ID : CT08WA29

Domain : Cyber security and Ethical hacking

Duration : March 5th, 2025 to May 5th, 2025

Mentor : Neela Santhosh Kumar

# Overview of the project
•	This project is a Python-based modular penetration testing toolkit designed to assist ethical hackers, cybersecurity professionals, and developers in identifying vulnerabilities in network services and web applications.
•	It provides a simple interface for performing two essential security tests: Port Scanning and Brute Forcing.

# Modules in the Toolkit
****1. Port Scanner****

A. Purpose:- Scans a target IP/hostname for open ports.

B. Features:-

o	Uses multithreading for faster scanning.

o	Reports open ports to the user.

C. Workflow:-

o	Takes a target IP/hostname and a list of ports as input.

o	Iterates through each port and checks if it is open by attempting a TCP connection.

D. Use Case:-Useful for identifying which services are running on a target machine.


**2. Brute-Forcer**

A. Purpose:- Attempts to crack HTTP Basic Authentication using a username and a password list.

B. Features:-

o	Automates the brute-forcing process.
o	Reads passwords from a user-specified file.
o	Stops the attack as soon as valid credentials are found.

C. Workflow:-

o	Takes a target URL, a username, and a password file as input.

o	Tries each password in the list and checks if the HTTP response indicates successful authentication.

D. Use Case:- Useful for testing the strength of passwords used in basic authentication.

# How the Toolkit Works
**1.	Toolkit Menu:-**
The user interacts with a menu to choose a module:

Option 1: Run the Port Scanner.

Option 2: Run the Brute-Forcer.

Option 3: Exit the toolkit.

**2.	Port Scanner:-**

o	Prompts the user for the target hostname/IP and a list of ports (comma-separated).

o	Concurrently scans each port and reports if it's open.

**3.	Brute-Forcer:-**

o	Prompts the user for the target URL, a username, and a path to a password file.

o	Reads the password file line-by-line, trying each password for HTTP Basic Authentication.

# Dependencies
**1.	Python Modules:-**

o	socket:- Used for creating TCP connections in the port scanner.

o	threading:-Enables multithreaded port scanning.

o	requests:-Used for sending HTTP requests in the brute-forcer.

**2.	Input Files:-** Password file for the brute-forcer module (plain text file with one password per line).

# Future Enhancements

1.	Add modules for:-

a)	SQL Injection testing.

b)	Cross-Site Scripting (XSS) detection.

c)	Directory brute-forcing.

d)	Subdomain enumeration.

2.	Implement logging to save results for later analysis.

3.	Add support for scanning networks with multiple hosts.

# OUTPUT

![image](https://github.com/user-attachments/assets/4a904ab0-5c05-4890-8ff6-9811b4e36d13)
