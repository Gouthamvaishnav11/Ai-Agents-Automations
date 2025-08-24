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

Auricdefence incident report sloution :
<img width="1483" height="336" alt="image" src="https://github.com/user-attachments/assets/3d4a3f68-41ae-4a9e-aa4c-2adb8fe31a9d" />



