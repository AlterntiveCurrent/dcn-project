# dcn-project
This project aimed to record and analyze five minutes of network traffic to identify the types of protocols in use, their frequency, and any potential security risks. The goal was to understand communication patterns and highlight areas that may require performance or security improvements.
Methodology
Data Capture:
● Time Frame: A 5-minute window was used to record network traffic, giving an overview
of what was going on on the network during that time.
● Network Interface: Although the assignment did not specify which network interface was
used to collect the data, it is presumed that the interface was crucial to the network
traffic of interest.
● Filters: Since no particular filters were given, it's possible that all traffic going through the
selected network interface was captured.
Data Analysis:
● Tool Utilization: Wireshark, NetStat
● Protocol Identification: The captured packets were parsed to identify the
protocols in use, with a focus on the most frequently used protocols.
● Traffic Pattern Analysis: Source and destination IP addresses were examined to
understand the flow of traffic and to identify any central nodes or unusual
patterns.
Findings:
● Network Protocols Observed: The analysis revealed that TCP (protocol number
6) and UDP (protocol number 17) were the most frequently used protocols within
the network traffic.
