# 🚀 Learning n8n Automation Platform

## 📌 What is n8n?

**n8n** (short for *"nodemation"*) is a powerful open-source workflow automation tool that allows you to connect different apps, APIs, and services to automate tasks without writing extensive code.

It works using a **node-based visual interface**, where you can design workflows by connecting triggers and actions.

### 💡 Why n8n is useful in real-world:

* Automates repetitive tasks (emails, data entry, notifications)
* Connects multiple platforms (APIs, databases, apps)
* Saves time and reduces manual effort
* Helps build **AI-powered workflows and agents**
* Useful in **backend automation, DevOps, and productivity tools**

---

# 📂 My Learning Project: n8n Workflows

This repository demonstrates my hands-on learning of n8n by building **real-world automation workflows and AI agents**.

---

## 📰 1. News Aggregator Agent

### 📖 Description:

This workflow is designed to automatically fetch and send the **top 10 news headlines daily at 7 AM**.

### ⚙️ Workflow Steps:

1. **Schedule Trigger** → Runs every day at 7 AM
2. **HTTP Request** → Fetches news using the News API
3. **Split Out** → Splits the response into individual news items
4. **Limit** → Selects top 10 news articles
5. **Code (JavaScript)** → Formats the data
6. **Send Email** → Sends news via email

### 🌟 Use Case:

* Daily news automation
* Personal assistant systems
* Content aggregation platforms

### 🖼️ Workflow Image:

![image alt](https://github.com/NithinSangsi/n8n/blob/908d84fc101bbaedc685371eedbb10ff199b4d13/Agent-1.png)

---

## 📋 2. Form Submission Agent

### 📖 Description:

This workflow handles form submissions by storing user data and sending a confirmation email.

### ⚙️ Workflow Steps:

1. **Form Submission Trigger**
2. **Append Row in Google Sheets** → Stores form data
3. **Send Email** → Sends confirmation to user

### 📥 Data Captured:

* Name
* Email
* Query
* Submission Time

### 🌟 Use Case:

* Lead collection systems
* Contact forms
* Feedback forms
* CRM automation

### 🖼️ Workflow Image:

![image alt](https://github.com/NithinSangsi/n8n/blob/908d84fc101bbaedc685371eedbb10ff199b4d13/Agent-2.png)

---

## 🤖 3. AI Team Lead Agent (App Assistant)

### 📖 Description:

This is an **AI-powered agent** that answers questions related to the application.

It acts like a **team lead or assistant**, capable of handling queries asked by users or interview panels.

### ⚙️ Workflow Steps:

1. **Form Submission Trigger** → User asks a question
2. **AI Agent (Gemini Model)** → Processes and answers the query
3. **Memory Node** → Maintains conversation context
4. **Send Email** → Sends response to user

### 🧠 Features:

* AI-powered responses
* Context awareness using memory
* App-specific question answering

### 🌟 Use Case:

* AI chatbot for apps
* Interview demo projects
* Customer support automation

### 🖼️ Workflow Image:

![image alt](https://github.com/NithinSangsi/n8n/blob/908d84fc101bbaedc685371eedbb10ff199b4d13/Agent-3.png)
---

# 🛠️ Tech Stack

* n8n (Workflow Automation)
* Google Sheets API
* Email Integration (Gmail)
* News API
* JavaScript (for data transformation)
* AI Model Integration (Gemini)

---

# 🎯 What I Learned

* Building automation workflows using n8n
* Working with APIs and data pipelines
* Integrating AI into workflows
* Designing real-world automation systems
* Using triggers, actions, and logic nodes effectively

---

# 🚀 Future Improvements

* Add database integration (MongoDB / MySQL)
* Build full chatbot UI
* Deploy workflows in production
* Add error handling and logging
* Integrate more AI capabilities

---

# 📌 Conclusion

This project reflects my journey in learning **workflow automation and AI integration using n8n**.
It demonstrates how automation can simplify real-world tasks and improve productivity.

---

# 📎 How to Add Your Images

1. Upload your images to GitHub (inside your repo)
2. Replace the URLs above with:

```
![Image Name](./images/your-image.png)
```

OR use external hosting:

```
![Image Name](https://your-hosted-link.com/image.png)
```

---

⭐ *This repository is part of my continuous learning journey in automation and AI systems.*

