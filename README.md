# 🌐 Suchismita Sarkar — Data & AI Portfolio

> A fully responsive personal portfolio with an AI-powered chatbot assistant (SuchiBot), built with HTML, CSS, JavaScript, and deployed on Netlify with Groq AI integration.

🔗 **Live Site:** [suchismitasportfolio.netlify.app](https://suchismitasportfolio.netlify.app)

---

## ✨ Features

- **SuchiBot** — AI-powered portfolio assistant built with Groq (LLaMA 3.3 70B)
- **Role Fit Engine** — recruiters can check how well Suchismita fits their job requirements
- **Project Showcase** — detailed cards for 5 ML/Data Science projects with accuracy metrics
- **Research Publication** — Springer ICCCNet-2025 paper highlight
- **Audio Introduction** — voice intro for a personal touch
- **Responsive Design** — works on mobile, tablet, and desktop
- **Smooth Animations** — scroll effects, gradient orbs, and profile ring animation

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML5, CSS3, Vanilla JavaScript |
| AI Backend | Netlify Serverless Functions (Node.js) |
| AI Model | Groq API — LLaMA 3.3 70B Versatile |
| Hosting | Netlify (CI/CD via GitHub) |
| Fonts | Google Fonts (Syne, DM Sans, JetBrains Mono) |
| Icons | Font Awesome 6 |

---

## 📁 Project Structure

```
suchismitasportfolio/
├── index.html                  # Main portfolio page (HTML + CSS + JS)
├── netlify.toml                # Netlify configuration
├── chatbot-avatar.png          # SuchiBot avatar image
├── portfolioimage.jpg          # Hero profile image
├── suchi-intro.mp3             # Audio introduction
└── netlify/
    └── functions/
        └── chat.js             # Serverless function — Groq AI integration
```

---

## 🤖 How SuchiBot Works

SuchiBot is an AI assistant trained on Suchismita's portfolio data. It answers recruiter questions about her skills, projects, experience, and more.

```
User Message
     ↓
index.html (frontend JS)
     ↓
POST /.netlify/functions/chat
     ↓
chat.js (Netlify serverless function)
     ↓
Groq API (LLaMA 3.3 70B)
     ↓
Response → displayed in chatbot UI
```

The API key is stored securely as a **Netlify environment variable** (`GROQ_API_KEY`) and never exposed to the browser.

---

## 🚀 Run Locally

### Prerequisites
- [Node.js](https://nodejs.org/) installed
- [Netlify CLI](https://docs.netlify.com/cli/get-started/) installed
- A [Groq API key](https://console.groq.com/keys)

### Steps

```bash
# 1. Clone the repository
git clone https://github.com/suchismittaa/suchismitasportfolio.git
cd suchismitasportfolio

# 2. Install Netlify CLI
npm install -g netlify-cli

# 3. Create a .env file for local development
echo "GROQ_API_KEY=your_groq_api_key_here" > .env

# 4. Run locally
netlify dev
```

Then open `http://localhost:8888` in your browser.

---

## 🔑 Environment Variables

| Variable | Description |
|---|---|
| `GROQ_API_KEY` | Your Groq API key from [console.groq.com](https://console.groq.com/keys) |

Set this in Netlify → Project Configuration → Environment Variables.

---

## 📊 Projects Featured

| Project | Accuracy | Domain |
|---|---|---|
| OTT Consumer Segmentation | 94% | Streaming / ML |
| Heart Failure Mortality Prediction | 97% | Healthcare |
| Credit Risk EDA | — | Finance |
| Energy Consumption Prediction | 91% | Energy |
| Cardiovascular Viral Impact Prediction | 91% | Healthcare / Research |

---

## 📄 Research Publication

**Precise Prediction of Cardiovascular Impact in Patients with Viral Infections Using Intelligent Analytics**
— ICCCNet 2025, Springer Nature, Manchester Metropolitan University, UK

---

## 📬 Contact

- 📧 [ssarkar4483@gmail.com](mailto:ssarkar4483@gmail.com)
- 💼 [LinkedIn](https://www.linkedin.com/in/suchismita-sarkar-09ba2430b/)
- 🐙 [GitHub](https://github.com/suchismittaa)

---

## 📝 License

This project is personal portfolio work by Suchismita Sarkar. Feel free to take inspiration, but please do not copy content or claim it as your own.

---

*Built with 💜 by Suchismita Sarkar*
