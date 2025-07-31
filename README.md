# MCP-integration-project
AI-powered outbound voice agent using MCP Server, ElevenLabs, and Twilio
# MCP Integration Project – AI Outbound Voice Agent

## 📌 Overview
This project showcases the integration of **Model Context Protocol (MCP)** with **ElevenLabs** and **Twilio** to create an **AI-powered outbound voice agent**.

The agent can make outbound calls, use natural-sounding voice (via ElevenLabs), and deliver **real-time tech updates** in a conversational tone.  
Even though source code is private, this repository documents **the architecture, setup process, and screenshots** to demonstrate the project in action.

---

## 🚀 Features
✅ **AI Voice Calls** – Uses ElevenLabs MCP Server for human‑like voice generation.  
✅ **Twilio Integration** – Handles outbound calls and call routing.  
✅ **MCP JSON Configuration** – Managed via Cursor IDE for seamless orchestration.  
✅ **Screenshots Included** – Every step documented for recruiters and developers.  

---

## 🛠 Tech Stack
- **Python 3.10+**  
- **Model Context Protocol (MCP)**  
- **ElevenLabs API**  
- **Twilio Voice API**  
- **Cursor IDE**

---

## 📂 Repository Structure
mcp-integration-project/
│
├── README.md # Project documentation (this file)
├── docs/
│ └── screenshots/ # All project screenshots
│ ├── call-history.png
│ ├── twilio-console.png
│ ├── mcp-setup.png
│ └── ...
└── app.py # (Optional) Placeholder file

yaml
Copy
Edit

---

## ⚙️ Setup Overview
This project involved configuring several key services:

1️⃣ **ElevenLabs Setup**  
- Created an ElevenLabs account  
- Generated API key  
- Configured MCP integration  

2️⃣ **Twilio Setup**  
- Purchased Twilio phone number (using free trial credits)  
- Set webhook for incoming calls to ElevenLabs MCP  

3️⃣ **MCP Server Setup**  
- Configured MCP JSON inside Cursor IDE  
- Connected APIs for ElevenLabs + Twilio  

4️⃣ **Agent Creation**  
- Built an **AI agent** that calls and delivers **tech updates** in a friendly voice

---

## 📸 Screenshots
👉 Screenshots of the process are stored in `docs/screenshots/`:

- **Call History** – Outbound call logs from the AI agent  
- **Twilio Console** – Number configuration setup  
- **MCP Setup in Cursor IDE** – JSON integration steps  

---

## 📜 Notes
This project was created as part of a **workshop on MCP server integrations**.  
Source code is **private** but the **architecture, screenshots, and process** are fully documented here for learning & reference.

---

## 📜 License
MIT License – Free to use and learn from this documentation.
