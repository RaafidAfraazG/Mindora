# 🧠 Mindora — Mental Health Support Chatbot

Mindora is a mental health support web application built using Flask, Supabase for authentication and data storage, and Gemini API for AI-powered empathetic responses. It allows users to register, login, and engage in supportive chatbot conversations, with full chat history management.

---

## 🚀 Features

- 📝 User registration and secure login system
- 🔒 Session-based authentication using Supabase
- 💬 Real-time mental health chatbot using Gemini API
- 🗂️ View previous conversations
- 🧾 Chat history saved and retrieved per user
- 🧠 AI generates empathetic responses based on user input and conversation history
- 🌐 Simple and clean UI with HTML templates

---

## 📁 Folder Structure

```

├── app.py
├── templates/
│ ├── home.html
│ ├── index.html
│ ├── login.html
│ └── register.html
```


---

## 🛠️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/mindora-chatbot.git
cd mindora-chatbot
```
### 2. Install Requirements
Create and activate a virtual environment:
```
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```
Then install dependencies:
```
pip install -r requirements.txt
```

### 3. Set up ```.env```
   Create a .env file in the root directory and add the following keys:
   ```
   SUPABASE_URL=your_supabase_url
   SUPABASE_KEY=your_supabase_anon_or_service_role_key
   GEMINI_API_URL=https://generativelanguage.googleapis.com/v1beta/models/gemini-pro:generateContent
   GEMINI_API_KEY=your_gemini_api_key
   ```

## ▶️ Running the Application
Visit:
```
 http://127.0.0.1:5000
````

## 📸 Screenshots

### 🔐 Home Page
<img width="959" alt="image" src="https://github.com/user-attachments/assets/098f251f-94ad-4079-97eb-809acadd01db" />

### 📝 Register Page
<img width="960" alt="image" src="https://github.com/user-attachments/assets/ed3ec518-f412-4d20-b84b-5f249b257681" />





### 💬 Chat Interface
<img width="958" alt="image" src="https://github.com/user-attachments/assets/a5f15ee0-ac44-4b9c-8028-87a83a8edb07" />

## 📄 Technologies Used

- Python + Flask – Backend & Routing
- Supabase – Auth, Database, and Session Management
- Gemini API – AI Chatbot Responses
- HTML/CSS – Frontend templates
- dotenv – Environment configuration
- requests – For external API interaction

## ⚠️ Notes
- Ensure Supabase Auth is enabled and chats table exists with user_id, name, chats, and created_at columns.

