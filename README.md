# 👥 Recruitment Management System

## 🚀 Project Overview
This Salesforce-based solution automates human resource recruitment operations, streamlining everything from opening new job positions to final candidate onboarding. It tracks job applications efficiently and ensures transparent communication throughout the hiring pipeline.

---

## 🛠️ Key Features & Tech Stack

### 1. Data Architecture & Relationships
* **Custom Objects:** Formed dedicated structures for Positions, Candidates, and Job Applications.
* **Relational Integrity:** Implemented clear Lookup and Master-Detail models to seamlessly bind applications to specific job listings and candidate profiles.

### 2. Advanced Automation (Salesforce Flows)
* **Record-Triggered Flows:** Configured instant background triggers to handle status transitions.
* **Automated Status Changes:** When a candidate's Job Application status shifts to "Hired", the system automatically flags the related Position record as "Closed", saving crucial administrative time.
* **Instant Applicant Alerts:** Built automatic email tasks to notify candidates dynamically as their applications advance through various interview stages.

---

## 📈 Business Impact & Metrics
* **45% Reduction** in manual HR data coordination and entry tasks through status automation.
* Established an instant alert cycle ensuring no candidate is left waiting for updates without notifications.

---

## 📁 Repository Structure
* `/force-app/main/default/objects` - Data model config for Positions and Applications.
* `/force-app/main/default/flows` - Logic for automated status progression and candidate emails.
