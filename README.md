# 🚀 Automated Employee Onboarding & Offboarding System (ServiceNow)

## 📌 Project Overview
The Automated Employee Onboarding & Offboarding System is a ServiceNow-based solution designed to streamline employee lifecycle processes. It reduces manual work and improves efficiency across departments like IT, HR, and Security.

## 🎯 Objectives
- Automate onboarding process
- Reduce manual errors
- Improve employee experience
- Track tasks efficiently

## ⚙️ Technologies Used
- ServiceNow
- Workflow Automation
- Catalog Items
- Flow Designer

## 🔄 Features
- Employee onboarding requests
- Approval workflows
- Task assignment
- Offboarding automation

##🧩 System Architecture
The system consists of the following components:
  Service Catalog Item

      “Employee Request”

Collects employee details such as:

Employee ID
Manager
Department
Joining Date / Exit Date
Assets Required / Assets to Collect
Request Type (Onboarding / Offboarding)
Catalog UI Policies

Dynamically show/hide fields based on request type
Enforce mandatory fields
Flow Designer

Automates the entire workflow:

Trigger → Approval → Task Creation → Completion → Notification
Custom Table

Stores lifecycle data (Employee Lifecycle)
⚙️ Workflow Explanation
🔹 Step 1: Trigger
Flow starts when a user submits a catalog request
🔹 Step 2: Get Catalog Variables
Fetch user input values from the form
🔹 Step 3: Create Lifecycle Record
Insert record into Employee Lifecycle table
🔹 Step 4: Approval Process
Approval sent to Manager (dynamic reference)
✅ If Approved:
🔸 Task Creation
IT Task → Account setup & hardware
Facilities Task → Workspace preparation
Security Task → ID & access provisioning
🔸 Wait Condition
Flow waits until all tasks are marked Closed Complete
🔸 Completion
Update Lifecycle Status → Completed
Update RITM → Closed Complete
Send completion email
❌ If Rejected:
Update status → Rejected
Send rejection email to requester
🔄 End-to-End Flow
User submits request → Manager approval → Tasks assigned to departments → Tasks completed → System updates status → Notification sent

## 📷 Screenshots
<img width="1907" height="865" alt="Screenshot 2026-05-02 154725" src="https://github.com/user-attachments/assets/d12e886b-0d10-4df9-9794-617eb6635f49" />
<img width="1911" height="838" alt="Screenshot 2026-05-02 153634" src="https://github.com/user-attachments/assets/ca759bb3-883a-44c0-a1fd-06e9342bbcab" />
<img width="1881" height="838" alt="Screenshot 2026-05-02 153613" src="https://github.com/user-attachments/assets/7ae2020c-8827-448a-917d-f96a6d5b9987" />
<img width="1918" height="843" alt="Screenshot 2026-05-02 153551" src="https://github.com/user-attachments/assets/7c05b01b-5767-4ac5-85a8-c109a8fa22db" />
<img width="1914" height="814" alt="Screenshot 2026-05-02 153529" src="https://github.com/user-attachments/assets/7bfcf24e-92ef-4e05-8ad5-31c596131207" />
<img width="1869" height="793" alt="Screenshot 2026-05-02 153459" src="https://github.com/user-attachments/assets/d287c919-2a45-43d8-a243-1ddc49d2460c" />
<img width="1914" height="866" alt="Screenshot 2026-05-02 153256" src="https://github.com/user-attachments/assets/9b5f04d0-5660-4dc5-b89e-01d362b257d7" />
<img width="1920" height="1080" alt="Screenshot 2026-05-02 153158" src="https://github.com/user-attachments/assets/ea4fb1e2-6314-4bbd-b626-889e562c29df" />
<img width="1850" height="711" alt="Screenshot 2026-05-02 153106" src="https://github.com/user-attachments/assets/52694457-dc37-40ca-bcab-f838b03163e3" />
<img width="1819" height="803" alt="Screenshot 2026-05-02 152931" src="https://github.com/user-attachments/assets/4c295b18-1616-4045-a949-91a3951e1d6a" />


## 👤 Author
Your Name
