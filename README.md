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
<img src="https://github.com/user-attachments/assets/4ff811b1-341d-4010-ae01-aabc5ae05869" width="600" alt="Screen Recording 2025-08-03 200739">





