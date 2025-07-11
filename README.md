# Splunkin Around
In this lab, we’re starting to work with Splunk, our first SIEM tool used in CodePath. SIEM stands for Security Information and Event Management, and it helps us pull in data from different systems, analyze it, and create visualizations. This makes it easier to spot possible security threats. The goal was to practice analyzing system logs, running searches, and building dashboards to spot potential security issues. After completing this lab, I learned how to search through log data, build visualizations, and create dashboards and reports that help track cybersecurity events.

## Tools & Technologies Used
- Ubuntu 22.04 LTS VM
- Splunk Enterprise (SIEM platform)
- auth.log Linux log file 
- Video game sales dataset 

## What This Lab Does
- Sets up and accesses Splunk on an Ubuntu VM.
- Searches through system logs (auth.log) to find login activity and potential attacks.
- Builds visualizations using the Top Video Game Sales dataset to practice creating dashboards.
- Creates a Splunk dashboard to monitor login attempts and other activity.
- Generates and saves reports to summarize log analysis findings.

## Screenshots
### Building a pie chart showing the top 5 video game genres
<img src="https://github.com/user-attachments/assets/3b555d66-ec0a-42b1-88a2-b30e2219da10" width="600"/>

### Changing the pie chart to show the top 5 video game platforms, and adding a top 5 video game genre bar graph
<img src="https://github.com/user-attachments/assets/3f480248-9d68-4193-8bbb-2da8757766c5" width="600"/>

### Building a bar graph showing the IPs of the top 10 failed login attempts
<img src="https://github.com/user-attachments/assets/b8248812-ff3d-4b6b-a65a-76371c8d1e3b" width="600"/>

### Scheduling a report to run every week for "Failed IPs" (the screenshot above)
<img src="https://github.com/user-attachments/assets/70fbc0ab-be2a-40bb-8422-e71a970c4ed7" width="600"/>
