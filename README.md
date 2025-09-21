# 📜 PoetAI — Personalized AI Poetry Generator 🎨🤖

> A low-code AI Agent project powered by n8n,Gemini and Airtable that collects user details, analyzes their profession,User Sentiment Choice  and generates a customized poem based on their name, looks, and profession ,User Sentiment Choice — all automatically.

---

## 🌟 Project Overview

**PoetAI** is a creative automation workflow built using n8n. It captures user input through a form, stores it in Airtable, evaluates the profession's rating, and generates a personalized poem using Gemini's GPT model. 

---

## 🚀 Key Features

- 🔗 **Automated Workflow** using n8n
- 📝 **User Input Form**: Name, Looks, and Profession,User Sentiment Choice 
- 📊 **Profession Popularity Analysis**
- 🧠 **Poem Generation** with Google Gemini
- 🗂️ **Airtable Integration** for data logging and storage
- - 📊 **Analytics-ready** with Airtable views or Google Sheets

---

## 🧩 Tech Stack

| Tool         | Purpose                        |
|--------------|--------------------------------|
| **n8n**      | Workflow Automation            |
| **GoogleGemini**   | Poem Generation (GPT-2.5 flash)|
| **Airtable** | Data Storage and Rating Logs   |
| **Webhook**  | Collect Form Submissions       |


---

## 📌 Workflow Steps

1. **User fills a form** with:  
   - Name  
   - Looks (appearance)  
   - Profession  
   - User Sentiment Choice  (e.g., Happy, Sad, Romantic)

2. **n8n Webhook Trigger** receives the data.

3. **Airtable Record Creation** to store the submission.

4. **Profession Rating Utility**:  
   - Checks or assigns a popularity rating to the profession.

5. **Google Node (Gemini)**:  
   - Generates a poem using input and profession rating.

6. **Update Airtable** with the generated poem.

   

---

## 🗃️ Airtable Base Schema

| Field        | Type          | Description                       |
|--------------|---------------|-----------------------------------|
| Name         | Text          | User's name                       |
| Looks        | Text          | Description of user's appearance  |
| Profession   | Text          | User's profession                 |
| Rating       | Number        | Popularity score of profession    |
| User Sentiment Choice         | Single Select |              |
| Poem         | Long Text     | Generated poem                    |


---
<img width="1668" height="611" alt="image" src="https://github.com/user-attachments/assets/4b53949d-7d33-4519-9949-c3f97b0368c0" />

Cusotmer Feedback:

<img width="1461" height="687" alt="image" src="https://github.com/user-attachments/assets/59f599f1-dd46-4d64-8797-d338f72a9400" />

Gmail reply Automation:
<img width="1452" height="536" alt="image" src="https://github.com/user-attachments/assets/654836c4-c4ed-4515-99b5-865e464718d7" />

Introducing My AI-Powered Incident Resolution Automation: “AuricDefence AI Agent”

I’m excited to share a project I recently developed — an AI Agent Automation that streamlines incident reporting and resolution. Here’s how it works:

User Submission: A user fills out a simple form with details like incident type, severity level, incident description (what happened step by step), name, and email.

AI Analysis: The AI Agent reviews the incident type and description, then suggests a potential solution.

Cybersecurity Team Review: The suggested solution is sent to the AuricDefence cybersecurity team for validation. The team can approve or reject the solution.

User Notification: Once approved, the solution is sent directly to the user’s email in a clear, step-by-step format — converting JSON-based incident solutions into easy-to-follow instructions.

This automation significantly reduces response time, ensures accuracy, and enhances the overall incident management process.
<img width="1483" height="336" alt="image" src="https://github.com/user-attachments/assets/3d4a3f68-41ae-4a9e-aa4c-2adb8fe31a9d" />


---

🔮 **AI-Powered Churn Prediction & Retention Agent**

Customer churn is one of the biggest hidden costs for any business. Retaining existing customers is significantly more cost-effective than acquiring new ones. Yet, companies across SaaS, retail, e-commerce, and services consistently face this challenge.

⚙️ **How It Works with n8n:**

**Trigger:**
Capture new customer data from CRMs like HubSpot, Salesforce, Zoho, Airtable, or Google Sheets—including last login, purchase history, support tickets, and subscription renewals.

**AI Analysis:**
An LLM or ML model (via OpenAI/Gemini node) evaluates churn risk as High, Medium, or Low.

*Example Prompt:*
*"Based on activity history: last login = 45 days ago, last purchase = 90 days ago, 2 unresolved tickets. Predict churn probability (0–100%) and suggest the best retention action."*

**Retention Actions:**

* **High Risk →** Automatically send personalized retention emails or offers (discounts, free upgrades, loyalty rewards)
* **Medium Risk →** Notify your team via Slack for follow-up

✅ **Benefits:**

* Minimize lost revenue from silent customer drop-offs
* Gain early warning for potential churn
* Boost customer lifetime value (CLV)
* Scales across industries including SaaS, retail, healthcare, finance, and e-commerce

💡 **Proactively manage churn. Retain customers smarter with AI.**
<img width="1483" height="568" alt="image" src="https://github.com/user-attachments/assets/07a7dc89-efb2-4bc8-b9e1-29813beb09b9" />




---
## 🎯 AI-Powered Event Idea Generator Workflow
Here’s how I built an automation where users can submit event details and instantly get structured event ideas stored in Airtable:

# 🔹 Steps in the Workflow
# 1️⃣ Form Submission
The user submits their Name and selects an Event Type (e.g., Technical, Sports, Cultural).

# 2️⃣ AI Agent 
The AI Agent takes the event type and generates event ideas in multiple dimensions like:
 ✅ Event Name
 
 ✅ Description
 
 ✅ Preparation Plan
 
 ✅ Promotion Plan
 
 ✅ Execution Plan

 ✅ Post-Event Actions
 
 ✅ Scores (Feasibility, Cost, Engagement)

# 3️⃣ Airtable Integration

The structured event details are stored in Airtable as a record.

This helps organizers pick the best idea from AI-generated suggestions with clear feasibility insights.
<img width="1339" height="547" alt="image" src="https://github.com/user-attachments/assets/019ae887-0b80-4a9a-8b5c-78c3f5cd2e92" />







