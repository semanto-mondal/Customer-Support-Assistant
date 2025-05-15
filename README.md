# 🚀 Automated Customer Support System with n8n + AI Chatbot

This project implements a fully automated, minimul code customer support system using n8n, integrated with a chatbot agent powered by a vector store and multiple backend automations to streamline issue tracking and resolution workflows.

---

## 🧩 Key Features

- 💬 **Chatbot Agent** – Ask company-related questions via a chatbot connected to a document-based knowledge base (vector store).
- 📋 **Issue Submission Form** – Users can report technical, billing, HR, or general issues through a structured form.
- ✉️ **Acknowledgement Email** – Instant ticket ID confirmation sent to the customer.
- 🗃️ **Google Sheets Integration** – All submissions are logged with timestamps, categories, priorities, and status.
- 📤 **Auto-routing to Departments** – Issues are emailed to the relevant department based on category.
- 🔁 **Status Tracking & Updates** – Status updates trigger emails to both departments and users.
- ⏰ **Escalation Rules** – 24-hour inactivity triggers follow-up with the department and customer.
- 📊 **Daily Digest for Leads** – Summary report of open, pending, and resolved tickets sent to team leads.

---

## 🛠️ Tools Used

- **n8n** – Visual workflow automation
- **Google Sheets** – Issue database backend
- **Gmail (SMTP)** – Email notifications
- **Vector Store / RAG Tool** – Document-based chatbot responses
- **Cron Scheduler** – Time-based triggers for escalation and reporting
- **Groq** – Time-based triggers for escalation and reporting

---

## ⚙️ How It Works

## Workflow of Chatbot 

<img width="1042" alt="image" src="https://github.com/user-attachments/assets/740f40c7-3a14-472e-b431-ed743ed412e2" />


## Workflow of Issue Submission form, Acknowledgement Email, Google Sheets Integration*, Auto-routing to Departments and Status Assignment

<img width="796" alt="image" src="https://github.com/user-attachments/assets/ad25c1d2-bc8f-4ec6-862a-7e4f63f04692" />

## Workflow of Escalation Rules, Daily Digest for Leads
<img width="689" alt="image" src="https://github.com/user-attachments/assets/8b4718f7-ede0-47aa-a62f-082854a099e6" />


## Sample Output

## Sample Chatbot output 
<img width="677" alt="chat feature" src="https://github.com/user-attachments/assets/4168c3b7-faa2-4e4d-9e5c-2ce700836e46" />
<img width="676" alt="chatbot 2" src="https://github.com/user-attachments/assets/d931501f-3114-441c-aa1b-53838ebe4306" />

## Sample of ACK Mail to the customer: 
<img width="587" alt="image" src="https://github.com/user-attachments/assets/a38493a0-e2d5-4eb0-887f-1331338791d8" />

## Sample of Issue Assignment to the Department
<img width="483" alt="image" src="https://github.com/user-attachments/assets/f088d711-6f5a-40b8-945d-1d9d82a7d1f3" />

## Sample of Issue Database in Google Sheet 
<img width="1048" alt="image" src="https://github.com/user-attachments/assets/77289328-e836-4622-adee-5d1700e8c720"/> 
  
## Sample of Daily Report 
<img width="719" alt="image" src="https://github.com/user-attachments/assets/a70d95af-6f09-43ed-ac7d-47e70576314d" />


## How to use 
You can download the file and can directly use this by importing this while creating a workflow in n8n platform. 

## Video Demo

https://github.com/user-attachments/assets/7941023f-d736-48b8-9758-f1fe0a768aac




