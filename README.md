Log Analysis Script for Cybersecurity using Python

In this project, I developed a Python script to analyze log files and extract important information such as the number of requests per IP address, the most accessed endpoints, and any suspicious activity like failed login attempts. This script is a useful tool for cybersecurity tasks, as it helps monitor traffic, identify potential threats, and organize the findings for further review.

Key Features:
Request Count per IP Address: The script processes the log file, extracts IP addresses, and counts the number of requests made by each IP. It then sorts the IPs in descending order based on their request count.
Most Accessed Endpoint: It analyzes the log data to identify the endpoint (like URLs or resource paths) that was accessed the most times.
Suspicious Activity Detection: The script flags IP addresses that have failed login attempts above a set threshold (default is 10) as potential brute-force login attempts.
CSV Report: The results are displayed in the terminal and saved to a CSV file for easy sharing and further analysis.

Tools Used:
Python (with libraries like re, csv, and collections)
File handling and regular expressions for parsing the log data

Deliverables:
A Python script that processes log files and provides the required outputs.
A CSV file (log_analysis_results.csv) containing the results, with sections for IP requests, the most accessed endpoint, and suspicious activity.
This script can be easily adapted to analyze different log formats or scaled to handle larger datasets. It was created with efficiency and usability in mind.
