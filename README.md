# 🤖 Social-to-Lead Conversational AI Bot

## 📌 Project Overview
This project is a simple conversational AI chatbot that simulates a **social-to-lead workflow system** for a fictional video SaaS platform.

The bot can:
- Handle user greetings
- Answer queries about pricing and plans (Basic & Pro)
- Provide policy-related information
- Detect user intent for purchase
- Collect lead information (name, email, platform)
- Simulate a lead capture tool execution

The system is built using Python with rule-based intent detection and a simple retrieval-based response mechanism.

---

## ⚙️ Features

### 1. Intent Detection
The bot identifies user intent using keyword-based matching:
- Greeting intent → responds with friendly message
- Information intent → retrieves plan/policy details
- High-intent (buy/subscribe) → triggers lead capture flow

---

### 2. Retrieval-Based Responses (RAG-style simulation)
Instead of hardcoding responses in multiple places, a simple retrieval function:
- Fetches plan details from structured JSON data
- Returns relevant answers based on user query

---

### 3. Conversational Lead Capture
When a user shows purchase intent, the bot collects:
- Name
- Email
- Platform (e.g., YouTube, Instagram)

This simulates a **real-world lead generation system** used in SaaS workflows.

---

### 4. Mock Tool Execution
A mock function simulates backend processing:

- `mock_lead_capture(name, email, platform)`

This represents how real systems send data to CRM or databases.

---

## 🧠 Tech Stack
- Python 3
- JSON (data storage)
- Rule-based NLP (keyword intent detection)
- State machine logic (for conversation flow)

---

## 📂 Project Structure

---

## 🔄 Conversation Flow

1. User starts conversation  
2. Bot detects intent:
   - Greeting → friendly reply  
   - Info → shows pricing/plans  
   - Purchase intent → triggers lead collection  

3. Bot collects:
   - Name  
   - Email  
   - Platform  

4. Lead is captured using mock tool

---

## 🧪 Example Interaction


User: hey  
Bot: Hi! Ready to create amazing videos? 🚀

User: tell me price  
Bot: We offer Basic ($29/month) and Pro ($79/month)...

User: I want pro  
Bot: Please share your details...

User: Varshini  
Bot: What's your email?

User: varshu@gmail.com  
User: YouTube  

Bot: Lead captured successfully 🎉


---

## 🚀 Improvements / Future Scope
- Replace keyword matching with NLP model (spaCy / Transformers)
- Integrate real RAG using vector database (FAISS / Pinecone)
- Add frontend chat UI (Streamlit / React)
- Connect real CRM API for lead storage
- Deploy using Flask / FastAPI

---

## 🎯 Learning Outcome
This project demonstrates:
- Basic conversational AI design
- Intent detection logic
- Stateful chatbot behavior
- Simple retrieval-based response system
- Lead generation workflow simulation

---

## 👩‍💻 Author
Varshini Rawal  
MCA Student | Data Science & AI Enthusiast




# 🚀 If you want next upgrade

I can help you make this even stronger by adding:

👉 Streamlit UI (VERY impressive for submission)  
👉 or real RAG using embeddings (FAISS)  
👉 or convert into GenAI chatbot using OpenAI API style structure  

Just say:
**“upgrade this to pro level”** 😼
