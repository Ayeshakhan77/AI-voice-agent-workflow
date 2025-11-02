# 🎙️ AI Voice Agent Workflow (n8n)

![Workflow](n8n\ 1.png)

This repository contains an **AI Research & Voice Summary Automation Workflow** built using **n8n**.  
The workflow allows a user to enter a **topic title** and a **time period**, and the system will:

1. Research the topic based on the given input  
2. Generate a **clear and concise text summary**  
3. Convert the summary into a **voice note**  
4. Send the voice note directly to the user via **Gmail**

This automation can be used for:
- Learning summaries
- Research overviews
- Audio study notes
- Topic-based knowledge recaps

---

## 🧠 Features

| Feature | Description |
|--------|-------------|
| Topic-based Research | Searches and gathers relevant information based on user input |
| Summary Generation | Creates a simplified explanation of the topic |
| Voice Note Conversion | Converts summary text to speech automatically |
| Gmail Delivery | Sends generated audio directly to the user’s email inbox |
| Fully Automated Workflow | No manual steps after user input |

---

## 🚀 Tech & Tools Used

| Tool | Purpose |
|-----|---------|
| **n8n** | Automation workflow engine |
| **LLM / AI Model (OpenAI / gemini)** | Summary generation *(API required)* |
| **Text-to-Speech Service** | Converts summary to voice |
| **Gmail Node** | Sends the final voice note to the user |

> ⚠️ **Note:** API keys are required for full functionality.  
No keys are included in this workflow for security reasons.

---

## 📦 Files Included in This Repository

| File | Description |
|------|-------------|
| `ai-voice-agent-workflow.json` | The exported n8n workflow file |
| `README.md` | Overview and setup instructions (this file) |

---

## 🛠️ Setup Instructions

### 1. Import Workflow Into n8n
1. Open your n8n instance
2. Go to **Workflows**
3. Click **Import**
4. Select `ai-voice-agent-workflow.json`

### 2. Add Required Credentials
You will need to configure:

| Service | Required Credential |
|--------|---------------------|
| LLM Provider | API Key (e.g., OpenAI, Gemini, etc.) |
| Text-to-Speech Service | API Key or built-in provider |
| Gmail | OAuth or App Password |

> Make sure **not to expose** your API keys publicly.

---

## 🎯 Usage

1. Run the workflow manually or trigger it automatically (e.g., form input, webhook, Telegram bot, etc.)
2. Enter the **topic title** and **time period**
3. Wait for the automation to finish
4. Check your **Gmail inbox** for the voice summary 🎧

---

## 🔄 Future Enhancements (Planned)

- UI form input (web or Telegram bot)
- Option to return both **text + audio**
- Multi-language output
- Save audio to Google Drive or Notion

---

## 🤝 Contributing
Feel free to **fork** this repository and improve the workflow.  
Pull requests are welcome!

---

## ⭐ If You Found This Useful
Give this repo a **star** ⭐ — it helps others discover it!

---

### Made with ❤️ and Automation  
