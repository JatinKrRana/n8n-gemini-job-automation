# n8n + Gemini Job Automation

This project automates the process of **finding jobs, matching them to a candidate profile, generating cover letters, and notifying users** — all powered by **n8n** workflows and Google Gemini.

---

## 📌 Project Description

Job hunting is repetitive: searching for jobs, checking eligibility, and writing cover letters.  
This automation streamlines the workflow by:

- Fetching job postings  
- Filtering jobs based on location & experience  
- Matching job descriptions with a user profile  
- Scoring compatibility  
- Auto-generating tailored cover letters  
- Sending results to **Google Sheets**  
- Sending notifications via **email**  

---

## ✨ Features

- 🔎 **Job Fetch** – Retrieve job postings dynamically.  
- 📊 **Match Scoring** – Compare job requirements with your profile.  
- 📝 **Cover Letter Generation** – Auto-generate role-specific cover letters.  
- 📑 **Google Sheets Integration** – Store job matches and scores in Google Sheets.  
- 📧 **Email Notification** – Get job matches + cover letters directly in your inbox.  

---

## ⚙️ How to Run

### 1. Run Locally (Development)
1. Clone the repository:
   ```bash
   git clone https://github.com/JatinKrRana/n8n-gemini-job-automation.git
   cd n8n-gemini-job-automation
   ```
2. Install dependencies (for any supporting scripts):
   ```bash
   npm install
   ```
4. Start n8n locally:
   ```bash
   n8n start
   ```
5. Import the workflow from:
   ```bash
   n8n_workflow/My workflow.json
   ```
### 2. 🚀 Run with n8n (Cloud / Self-Hosted)

1. 🌐 Open your **n8n instance**.  
2. 📥 Import the JSON workflow:  
   ```bash
   n8n_workflow/My workflow.json
   ```
3. 🔑 Configure credentials:  
   - 📊 **Google Sheets** → For storing job matches  
   - 📧 **Email SMTP** → For sending notifications  
   - 🤖 **Gemini API Key** → For AI-powered features  
4. ✅ Activate the workflow.

## 📸 Screenshots  

🔹 **Google Sheet Output** – Job data with match scores
<img width="2122" height="1012" alt="Screenshot 2025-08-20 210619" src="https://github.com/user-attachments/assets/b761fd68-8547-4f9a-b25a-4c03f4f6012d" />

🔹 **Email Notification** – Automated job recommendations in your inbox
<img width="2000" height="884" alt="Screenshot 2025-08-20 210728" src="https://github.com/user-attachments/assets/c2090b69-0334-4fe6-90fc-c91b23c9fb2a" />

🔹 **n8n Workflow** – Visual automation flow connecting all steps
<img width="2056" height="394" alt="Screenshot 2025-08-20 210436" src="https://github.com/user-attachments/assets/ab735033-8cca-43ce-87b2-d8dc9ad891a1" />











