# Algorithm for File Updates in Python: Detection Lab Simulation

## Objective
The goal of this project was to build an algorithm that updates an IP address allow-list by parsing the file and removing unauthorized IPs. This simulation is part of a broader study of security event management and detection in cybersecurity, providing practical experience in managing network restrictions through automation.

### Skills Learned
- Practical understanding of Python for automation in file handling.
- Expertise in network security principles related to IP access control.
- Experience in parsing and modifying text files with structured data (IP addresses).
- Development of skills for simulating attack detection scenarios by updating and managing IP allow-lists.
- Critical thinking in addressing real-world cybersecurity challenges by automating security policy updates.

### Tools Used
- Python for text file parsing and algorithm development.
- Jupyter Notebook for scripting and testing the algorithm.

## Steps
Step 1: Open the File Containing the Allow List - 
In the first step, I opened the text file containing the list of authorized IP addresses. This file was the source of the IP addresses that required evaluation.

![8-Importing and Parsing a Text File in a Security-Related Scenario-1](https://github.com/user-attachments/assets/f07e123a-545d-4861-a7a8-13943e5dcd1a)

Step 2: Read the File Contents - 
After opening the file, I read its contents into the program. The content included all the IP addresses currently allowed access, which needed to be filtered based on the "remove list."

![8-Importing and Parsing a Text File in a Security-Related Scenario-2](https://github.com/user-attachments/assets/541cb1b0-c906-4b82-b978-b2dba05e5120)


Step 3: Convert the IP Addresses to a List - 
To efficiently process the IP addresses, I converted the string of IPs into a Python list, enabling easier manipulation and removal of unauthorized addresses.

![8-Importing and Parsing a Text File in a Security-Related Scenario-3](https://github.com/user-attachments/assets/b11f6fd8-20db-44b6-a759-e4031c04155d)


Step 4: Iterate Through and Remove Unauthorized IPs - 
The next step involved iterating through the list of IP addresses and removing those that matched any addresses on the "remove list." This automated step ensured only valid IP addresses remained in the allow-list.

Step 5: Update the File with the Revised IP List - 
Finally, I updated the original file by writing the cleaned list of IP addresses back into the file, ensuring that the unauthorized IPs were no longer present.

![8-Importing and Parsing a Text File in a Security-Related Scenario-4](https://github.com/user-attachments/assets/30c5ccca-5714-453a-8e40-5c0c0d34c3f3)


This project enhanced my understanding of how file handling in Python can be applied to real-world security scenarios, such as managing access control lists. It also built on my cybersecurity knowledge by simulating the detection and removal of unauthorized network activity.
