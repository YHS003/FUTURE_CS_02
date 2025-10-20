# Cyber Security Internship Task "Future Interns Program" - Task Two  
*Prepared by: Yehya Hamdy Sayed-Ahmed Mohammed*  
*Date: October 20, 2025, 03:48 PM EEST*  
*Submitted to: Future Interns Task Two*

---

## Overview  
This repository contains the deliverables for Task Two of my internship with Future Interns, focusing on a Security Operations Center (SOC) simulation. This task involved analyzing security incidents, classifying alerts, and preparing a comprehensive Incident Response Report. For me, this was an entirely new experience, as I come from a background in Red Team and Bug Bounty activities, where my focus was on offensive security and penetration testing. Diving into the Blue Team world—dealing with logs, SIEM systems, Splunk, and incident response—was a challenging yet rewarding journey. This README details my learning process, the effort put into the task, and the structure of this repository.

---

## Task Description  
The SOC Internship Task Two required me to:
- Analyze security logs to identify critical incidents that occurred on July 3, 2025.
- Use Splunk to search and filter logs for threats like malware, failed login attempts, and connection anomalies.
- Classify the alerts based on severity and document them in a structured format.
- Prepare an Incident Response Report with remediation steps and recommendations.
- Submit all deliverables in an organized repository.

This was my first time working with SOC-related tasks, and every step—from opening logs to writing the report—felt like a steep learning curve. But with persistence and guidance, I managed to navigate through it.

---

## My Learning Journey  
This task was a completely new territory for me. Here’s what I learned along the way:

### 1. Working with Logs for the First Time  
- Initially, I had no idea how to approach raw log data. Opening the logs in Splunk was intimidating—lines of text with timestamps, IP addresses, and error codes felt like a foreign language.
- I started by learning the basics of log structures, understanding what each field (like timestamp or source IP) meant in the context of security.

### 2. Mastering Splunk (Even a Little)  
- Splunk was a game-changer, but it took time to figure out. I learned how to use simple search queries like `index=* action="malware detected"` or `index=* "login failed"` to pinpoint threats.
- It was trial and error at first—running searches, refining them, and cross-checking results. I even spent hours tweaking queries to ensure I didn’t miss any alerts.
- This process taught me how to filter noise and focus on critical incidents, a skill I never needed in my Red Team days.

### 3. Reading and Analyzing Logs  
- Reading logs was a challenge. I had to train my eyes to spot patterns—like recurring IP addresses (e.g., 203.0.113.77) or unusual user activities.
- I learned to correlate events, such as linking a failed login to a potential brute force attack or connecting multiple connection attempts to reconnaissance.

### 4. Writing an Incident Response Report  
- Drafting the report was a new skill entirely. I had to structure it with sections like Executive Summary, Timeline, and Recommendations, which was a shift from the quick reports I used to write for vulnerabilities in Bug Bounty.
- I learned to present data clearly, ensuring the impact and remediation steps were actionable for a SOC team.

### 5. Understanding Classifications  
- Classifying alerts by severity (High, Medium) was a revelation. I had to assess the risk level of each incident—malware got a High rating due to its potential to encrypt data, while a failed login was Medium until proven otherwise.
- This taught me the importance of prioritization in a defensive security role, something I never deeply considered as a Red Teamer.

### 6. Transition from Red Team to Blue Team  
- Coming from a Red Team background, where I focused on breaking systems, this task flipped my perspective to protecting them. It was exhausting yet exciting to think like a defender, searching for threats instead of creating them.
- This experience opened my eyes to the Blue Team’s critical role, and I’m grateful for the chance to explore it.

---

## Repository Structure  
The repository is organized to make it easy to navigate. Here’s the layout:

- **/report**: Contains the Incident Response Report files.
  - `Incident_Response_Report.docx`: The editable Word document.
  - `Incident_Response_Report.pdf`: The finalized PDF version.
- **/screenshots**: Holds the supporting images from Splunk analysis.
  - `image1.png`: Screenshot of malware detected alerts.
  - `image2.png`: Screenshot of the failed login attempt.
  - `image3.png`: Screenshot of connection attempt anomalies.
- **/spreadsheet**: Includes the Alert Classification Log.
  - `Alert_Classification_Log.xlsx`: The Excel file with classified alerts.
- **README.md**: This file, providing an overview and my reflections.

This structure reflects the effort I put into separating deliverables for clarity and professionalism.

---

## The Process We Went Through Together  
Working on this task with guidance was a collaborative effort. Here’s how we tackled it:
- **Searching for Threats**: We started by diving into the logs, using Splunk to hunt for keywords like "malware detected" or "login failed." It was like a treasure hunt—sifting through data to find the golden alerts.
- **Analyzing Patterns**: We spent time connecting the dots, like noticing the same IP (203.0.113.77) in both failed logins and connection attempts, hinting at a potential attacker.
- **Building the Spreadsheet**: We crafted the Alert Classification Log step by step, ensuring every alert had a timestamp, type, and severity. It took multiple revisions to get it right.
- **Drafting the Report**: We iterated on the report, adding sections and refining the language to sound professional. Placing screenshots was a challenge, but we figured it out.
- **Organizing the Repo**: We designed the folder structure to keep everything neat, making sure the GitHub submission would impress.

This process was exhausting—late nights of trial and error, rechecking data, and learning on the fly—but it paid off.

---

## Gratitude to Future Interns  
I want to extend my heartfelt thanks to the Future Interns team for this incredible opportunity. Providing me with this SOC task and the working environment to explore it was a game-changer. The hands-on experience with Splunk, logs, and incident response has broadened my skill set beyond my Red Team roots. Your support and the resources you offered made this possible, and I’m truly grateful for the chance to grow as a security professional. This task wasn’t just a submission—it was a stepping stone in my career, and I couldn’t have done it without your guidance.

---

## Final Thoughts  
This task was a marathon of learning and effort. From zero knowledge of SOC operations to delivering a structured report and spreadsheet, I poured my energy into every detail. The struggle to understand logs, the excitement of mastering Splunk searches, and the pride in completing the report all reflect the hard work behind this repo. I hope this submission showcases my dedication and the valuable skills I’ve gained.

Thank you once again, Future Interns, for this transformative experience. I look forward to your feedback!

*Best regards,*  
*Yehya Hamdy Sayed-Ahmed Mohammed*  
*Cyber Security Intern*  
*October 20, 2025, 03:48 PM EEST*
