# ✅ EmailWriter (AI-Powered Chrome Extension & Web App for Smart Email Replies)

**EmailWriter** is a smart and lightweight AI-powered tool combining a **React frontend**, a **Chrome Extension**, and a scalable **Spring Boot backend**. It enables users to instantly generate polished email replies in various tones using **Google’s Gemini 1.5 Flash** (free and open-source GenAI model).

This project demonstrates modern backend-driven GenAI integration with seamless real-time user experience.

---

### ✨ Key Features:

📨 **AI-Based Email Reply Generation**  
Paste the received email into the web app, select a tone (Professional, Friendly, Casual, etc.), and generate a relevant reply using Gemini 1.5 Flash through backend APIs.

🧩 **Smart Chrome Extension**  
Activates only when you click **Reply** on an email (e.g., Gmail). A **"AI Reply"** button appears next to **Send**, which when clicked, captures the conversation and auto-generates a response into the text area.

🔁 **Regenerate On Demand**  
Click the **AI Reply** button again to regenerate a new version of the response.

📋 **Auto-Populated Text Area**  
The AI-generated reply is inserted directly into the email editor, ready to be sent or edited.

---

### 🧱 Tech Stack

#### 💻 Backend:
- **Spring Boot** – Core REST API development
- **Google Gemini 1.5 Flash API** – Tone-aware text generation
- **Layered Architecture** – Controller, Service, DTO
- **Simple Production-Ready Design** – Modular codebase, validation, logging

#### 🎨 Frontend:
- **React.js** – Interactive UI for email input and tone selection
- **Chrome Extension (JS/HTML)** – Injects dynamic button into email clients like Gmail

---

### 🚀 How to Use

#### 👉 Web Application:
1. Launch the React frontend.
2. Paste the received email into the input box.
3. Select a tone from the dropdown.
4. Click **Generate Reply** → a well-formed reply is returned from the backend and displayed.

#### 👉 Chrome Extension:
1. Load the extension in Chrome via developer mode.
2. Open Gmail and click **Reply** on an email.
3. A new **"AI Reply"** button appears next to **Send**.
4. Click it → email history is fetched, and the AI-generated reply is populated in the editor.

---

### 🎯 Highlights

- Modular and production-ready backend built with Spring Boot and layered architecture.
- RESTful API-first design enabling scalable and testable integration.
- Seamless full-stack communication between React frontend, Chrome Extension, and backend services.
- Real-world integration with open-source GenAI (Gemini 1.5 Flash) for tone-aware email replies.
- Dynamic Chrome Extension with real-time DOM manipulation and auto-populated email responses.

---

### 📸 Sample Screenshots

✨**Simple React Application**:
<!-- React App Screenshot -->
<img src="https://github.com/user-attachments/assets/e49a66f3-85c9-447a-91e1-16851593ebaa" alt="React App Screenshot" width="600"/>

✨**Chrome Extension in Gmail Reply Box:**
<!-- Chrome Extension Screenshot -->
<img src="https://github.com/user-attachments/assets/07a823f9-3d5e-425e-8c97-21294798add0" alt="Chrome Extension Screenshot" width="800"/>




---

Feel free to ⭐ star the repo or fork it for your own use or enhancements.

