BASH SCRIPTING & SYSTEM AUTOMATION REPORT 
Cybersecurity Track | CampusPe Assessment 
 
SUBMITTED BY:   SANGEETHA MB 
COURSE:                CYBERSECURITY 
ASSIGNMENT :     BASH SCRIPTING ASSIGNMENT 
COMPLETION STATUS: 100% (5/5 Tasks) 
---------------------------------------------------------------------------------------------------------------- 
1.	PROJECT OBJECTIVE 
---------------------------------------------------------------------------------------------------------------- 
This project serves as a comprehensive demonstration of Linux system automation using Bash. The primary focus was to develop tools for system administration, forensic log analysis, and automated security auditing. Each script was developed to follow standard Linux scripting best practices, including error handling and user input validation. 
---------------------------------------------------------------------------------------------------------------- 
2.	CORE SCRIPT DIRECTORY 
Below is a breakdown of the automated tools included in this assignment: 
q1_system_info.sh: Conducts a quick audit of the local environment (Hostname, OS version, and active users). 
q2_file_manager.sh: An interactive CLI utility for secure file operations, directory creation, and search functions. 
q3_log_analyzer.sh: A forensic tool that parses server logs to identify traffic patterns and unique IP hits. 
q4_backup.sh: An automation script for creating timestamped, compressed archives of sensitive data. 
q5_user_report.sh: A security auditor that scans system files to identify root privileges and inactive user accounts. 
---------------------------------------------------------------------------------------------------------------- 
3.	TECHNICAL IMPLEMENTATION & EXECUTION 
All scripts require execution permissions before use. 
Initialization: chmod +x *.sh Individual Tool Execution: 
System Audit: ./q1_system_info.sh 
Log Forensics: ./q3_log_analyzer.sh  
User Security Check: sudo ./q5_user_report.sh 
---------------------------------------------------------------------------------------------------------------- 
4.	MODULE BREAKDOWN & FEATURES 
Q1: Environmental Intelligence 
Retrieves real-time system metadata including Uptime, Kernel version, and current working environment paths to assist in system diagnostics. 
Q2: Interactive File Management 
A menu-based system designed for efficiency. It includes safe-delete protocols, file counting mechanisms, and directory management to keep the filesystem organized. 
Q3: Forensic Log Analysis 
Utilizes powerful text-processing commands (awk, grep, sort) to extract intelligence from access.log files. It identifies the top 3 visiting IPs and summarizes HTTP status codes to detect potential errors or attacks. 
Q4: Data Redundancy (Backup) 
Automates the backup workflow by generating .tar.gz archives. The script includes logic for custom source/destination paths and calculates the total archive size for verification. 
Q5: Identity & Access Management (IAM) Report 
A high-level security script that audits the /etc/passwd file. It specifically flags accounts with UID 0 (Root privileges) and lists inactive users to help reduce the system's attack surface. 
---------------------------------------------------------------------------------------------------------------- 
5.	DEVELOPMENT & TESTING ENVIRONMENT 
Platform: Ubuntu Linux 22.04 LTS 
Shell: GNU bash, version 5.0+ 
Quality Assurance: * ShellCheck: Used for linting and syntax optimization. 
Debug Mode: Verified logic flow using bash -x. 
Validation: All user inputs are sanitized to prevent execution errors. 
 
 
 

 
6.	KEY LEARNING OUTCOMES 
Mastery of Text Processing utilities (sed, awk, uniq). 
Implementation of Conditional Logic and loops for task automation. 
Understanding of Linux System Security and user privilege management. 
Hands-on experience with Data Archival and system auditing. 
---------------------------------------------------------------------------------------------------------------- 
END OF REPORT 
---------------------------------------------------------------------------------------------------------------- 
# bash-scripting-automation
