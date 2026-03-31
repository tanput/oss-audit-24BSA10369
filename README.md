# Open Source Software Audit Project

## Student Details
Name: Tanya Rajput  
Roll Number: 24BSA10369  


## Chosen Software
Git (Distributed Version Control System)



## Project Description
This project is a detailed audit of the open-source software Git. It explores the origin, purpose, and philosophy behind Git, along with its licensing model and role in the open-source ecosystem. The project also analyzes how Git works within a Linux environment and compares it with proprietary alternatives.

Additionally, the project includes five shell scripts that demonstrate practical Linux and bash scripting skills such as system information retrieval, package inspection, disk auditing, log analysis, and user interaction.


## Scripts Overview

###  Script 1: System Identity Report
Displays system information such as Linux distribution, kernel version, current user, uptime, date, and license information.

###  Script 2: FOSS Package Inspector
Checks whether Git is installed on the system, displays its version and details, and provides a short description using a case statement.

###  Script 3: Disk and Permission Auditor
Analyzes important system directories to display their disk usage, ownership, and permissions using loops and command-line tools.

###  Script 4: Log File Analyzer
Reads a log file line by line, counts occurrences of a specific keyword (default: "error"), and displays the last five matching lines.

###  Script 5: Open Source Manifesto Generator
Takes user input and generates a personalized open-source philosophy statement, saving it to a text file.


##  How to Run the Scripts

Follow these steps in a Linux terminal:

### Step 1: Give execute permission
chmod +x script1.sh
chmod +x script2.sh
chmod +x script3.sh
chmod +x script4.sh
chmod +x script5.sh

### Step 2: Run scripts

./script1.sh

./script2.sh

./script3.sh

./script4.sh /var/log/syslog

./script5.sh
