# ⚡ n8n Automation Projects

Welcome to my **n8n projects ** 🎉 
This repository showcases real-world automation workflows I built using **n8n** for job search, email communication, and workflow optimization.  

These projects demonstrate my ability to **design, implement, and scale automations** with data handling, email integration, and error management.



## 📌 Projects

### 1️⃣ Bulk HR Email Automation
📧 Automated sending of **1841 personalized job application emails** to HR contacts.  

**Features:**
- Reads HR details from a CSV/Google Sheet.
- Generates **dynamic email content** using JavaScript.
- Sends messages via **Gmail node**.
- Verifies success with an **If condition**.
- Handled **1841 items in a single run**.

📂 Files: `hr_email_workflow.json`  
📸 Screenshot: `screenshots/hr_email_workflow.png`  



### 2️⃣ Interview Thank-You Email Automation
🙏 Automatically sends **thank-you messages** to interviewers after job interviews.  

**Features:**
- Triggered manually or by event.  
- Prepares a **personalized thank-you message**.  
- Sends email via Gmail/SMTP.  
- Ensures consistency and professionalism.  

📂 Files: `interview_thankyou.json`  
📸 Screenshot: `screenshots/interview_thankyou.png`  



### 3️⃣ Job Application Workflow (CSV → Email)
📝 Sends **job application emails** to multiple companies from a CSV file.  

**Features:**
- Reads **company, HR name, email** from CSV.  
- Generates a **cover letter** dynamically.  
- Sends application emails with attachments (resume).  
- Logs success/failure.  

📂 Files: `job_application_workflow.json`  
📸 Screenshot:https://1drv.ms/i/c/e83ea1b5054c9392/Ef1xiAbS4tBFqgK5hjRe6BMBZcWwXeBFwYQ2ynsLtaHi3Q?e=GvZNgN  



### 4️⃣ Error Handling & Retry Workflow
⚠️ Workflow that ensures emails **retry automatically** if sending fails.  

**Features:**
- Tracks failed messages.  
- Uses conditional logic for retries.  
- Prevents data loss during bulk operations.  
- Reliable execution for high-volume automation.  

📂 Files: `error_handling_workflow.json`  
📸 Screenshot: `screenshots/error_handling.png`  



## 🛠 Skills Demonstrated
- **Workflow Automation** with n8n  
- **Email Integration** (SMTP / Gmail API)  
- **Data Handling** from CSV/Sheets  
- **JavaScript scripting** inside workflows  
- **Error Handling & Retry Logic**  
- **Bulk Processing** (1000+ items at scale)  



## 🚀 How to Use
1. Clone/download this repository.  
2. Import any `.json` workflow into your n8n instance.  
3. Configure credentials (SMTP/Gmail).  
4. Adjust data sources (CSV/Sheets).  
5. Execute workflow → Automation runs instantly.  


