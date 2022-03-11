# Security-Engineering-Project

In this project, I acted as a security engineer supporting an organization's SOC infrastructure. 

Scenario: 
The SOC analysts have noticed some discrepancies with alerting in the Kibana system and the manager has asked the security engineering team to investigate and confirm that newly created alerts are working.
If the alerts are working, you will then monitor live traffic on the wire to detect any abnormalities that aren't reflected in the alerting system. Then, you will report back your findings to the manager with appropriate analysis.


Days 1 and 2: Alert and Attacking Target 1

Configure alerts in Kibana
Attack a machine on the network.
Capture the flag on the victim machine.


Day 3: Wireshark Strikes Back

Capture network traffic
Investigate a number of suspicious activities
Collect corporate misuse evidence
Work in groups to create a presentation


Day 4:

Create an offensive red team analysis
Create a defensive blue team analysis
Create a network forensic analysis


Lab Environment

This is a diagram of the network and the machines that will be used in this lab:
Open the Hyper-V Manager to access the nested machines:

ELK machine credentials: The same ELK setup that you created in Project 1. It holds the Kibana dashboards.
Username: 
Password: 
IP Address: 192.168.1.100


Kali: A standard Kali Linux machine for use in the penetration test on Day 1.
Username:
Password:
IP Address: 192.168.1.90


Capstone: Filebeat and Metricbeat are installed and will forward logs to the ELK machine.
IP Address: 192.168.1.105
Please note that this VM is in the network solely for the purpose of testing alerts.


Target 1: Exposes a vulnerable WordPress server.
IP Address: 192.168.1.110
