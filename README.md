# 🧠 MindBridge — Mental Health Awareness & Suicide Prevention Agent

> An AI-powered, single-file web application for mental health awareness, crisis support, and suicide prevention — built with HTML, CSS, and JavaScript, with an embedded IBM watsonx Orchestrate conversational agent.

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Live Demo](#-live-demo)
- [Features](#-features)
- [Page Sections](#-page-sections)
- [Tech Stack](#-tech-stack)
- [IBM watsonx Orchestrate Integration](#-ibm-watsonx-orchestrate-integration)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Configuration](#-configuration)
- [Crisis Resources](#-crisis-resources)
- [Coping Techniques](#-coping-techniques)
- [Warning Signs](#-warning-signs)
- [Disclaimer](#-disclaimer)
- [License](#-license)

---

## 🌐 Overview

**MindBridge** is a compassionate, AI-powered mental health awareness platform delivered as a **single HTML file**. It combines:

- A fully responsive, modern UI with empathetic design
- An interactive **mood check-in** system with personalised responses
- Clinically-grounded **coping technique guides**
- A curated list of **global crisis hotlines and resources**
- **Warning signs** of suicide risk, sourced from clinical literature
- A live **IBM watsonx Orchestrate AI chat agent** for real-time, empathetic conversation

The goal is to reduce stigma, increase awareness, and ensure anyone in distress can immediately access help — directly from their browser, 24/7.

---

## 🚀 Live Demo

To run the application:

1. Download or clone this repository
2. Open `mental_health_agent.html` directly in any modern browser (Chrome, Edge, Firefox)
3. Ensure you have an active internet connection (required for the IBM watsonx AI agent)
4. The IBM watsonx chat widget will appear as a **floating panel** in the bottom-right corner

> **No server, no build step, no dependencies.** Just open and use.

---

## ✨ Features

| Feature | Description |
|---|---|
| 💬 **AI Chat Agent** | Embedded IBM watsonx Orchestrate agent for empathetic, real-time conversation |
| 🎭 **Mood Check-In** | 8-option interactive mood selector with personalised, clinically-informed responses |
| 🚨 **Crisis Detection** | Prominent crisis banner with 988 and Crisis Text Line numbers always visible |
| 📚 **Psychoeducation** | Clear explanations of depression, anxiety, PTSD and more |
| 🧘 **Coping Techniques** | Evidence-based tools: Box Breathing, 5-4-3-2-1 Grounding, CBT, PMR |
| ⚠️ **Warning Signs** | 12 clinically-recognised suicide risk indicators |
| 📞 **Crisis Resources** | 6 major global hotlines with names, numbers, and descriptions |
| 📊 **Awareness Stats** | Key mental health statistics to educate and reduce stigma |
| 📱 **Fully Responsive** | Mobile-first design, works on all screen sizes |
| 🌙 **24/7 Available** | Static file — no downtime, no server required |

---

## 📄 Page Sections

### 1. 🔵 Navigation Bar
Sticky top navigation with links to all major sections and a **"Talk to Agent"** CTA button that opens the IBM watsonx chat widget.

```
MindBridge | Features | Mood Check | Warning Signs | Resources | Coping Tools | [Talk to Agent]
```

### 2. 🦸 Hero Section
- Bold headline: *"You Are Not Alone. Help Is Here For You."*
- Subtext describing the platform's mission
- Two CTA buttons: **Chat with AI Agent** and **Crisis Resources**

### 3. 🚨 Crisis Banner
Always-visible red alert banner with:
- Emergency callout text
- **988 Suicide & Crisis Lifeline** (USA)
- **Crisis Text Line** — Text HOME to 741741

### 4. 📊 Statistics Bar
Four key awareness statistics displayed as cards:
- 1 in 5 adults experience a mental health condition each year
- 700M+ people worldwide live with mental health disorders
- 90% of suicide deaths involve a treatable mental health condition
- 24/7 AI agent availability

### 5. ⚙️ Features Grid
Six feature cards explaining the core capabilities of MindBridge:
- Empathetic Conversation
- Crisis Detection & Escalation
- Evidence-Based Coping Tools
- Mood Tracking
- 24/7 Availability
- Psychoeducation

### 6. 🎭 Mood Check-In (`#mood`)
Interactive panel with 8 mood buttons:

| Mood | Emoji | Response Type |
|---|---|---|
| Great | 😊 | Positive reinforcement |
| Okay | 🙂 | Self-care suggestions |
| Anxious | 😰 | Breathing exercise guide |
| Sad | 😢 | Validation + support |
| Angry | 😠 | De-escalation techniques |
| Numb | 😶 | Sensory grounding |
| Hopeless | 😔 | Crisis escalation + 988 |
| Overwhelmed | 🤯 | Grounding + chat redirect |

### 7. ⚠️ Warning Signs (`#warning-signs`)
12 evidence-based warning indicators of suicide risk, displayed in a responsive grid with amber accent styling to communicate urgency without being alarming.

### 8. 📞 Crisis Resources (`#resources`)
Six resource cards with hotline details:

| Organisation | Contact |
|---|---|
| 988 Suicide & Crisis Lifeline | Call or Text **988** |
| Crisis Text Line | Text **HOME** to **741741** |
| IASP Crisis Centres | [Directory Link](https://www.iasp.info/resources/Crisis_Centres/) |
| NAMI Helpline | **1-800-950-NAMI** |
| Veterans Crisis Line | Call **988**, Press **1** |
| SAMHSA National Helpline | **1-800-662-4357** |

### 9. 🧘 Coping Techniques (`#coping`)
Four evidence-based techniques with step-by-step instructions:

1. **Box Breathing (4-4-4-4)** — Inhale, hold, exhale, hold — 4 seconds each
2. **5-4-3-2-1 Grounding** — Engage all five senses to anchor to the present
3. **Thought Reframing (CBT)** — Identify and challenge negative automatic thoughts
4. **Progressive Muscle Relaxation** — Systematically tense and release muscle groups

### 10. 🤖 AI Chat Section (`#chat`)
Full-width CTA panel with a live AI pulse indicator, introductory copy, and an **"Open Chat Window"** button that triggers the IBM watsonx Orchestrate widget.

### 11. ⚠️ Medical Disclaimer
Amber-styled disclaimer box clarifying the tool is not a clinical substitute, with a direct reminder to call **988** in an emergency.

### 12. 🔗 Footer
Brand logo, navigation links, copyright, and IBM watsonx Orchestrate attribution.

---

## 🛠 Tech Stack

| Layer | Technology |
|---|---|
| **Markup** | HTML5 (semantic, accessible) |
| **Styling** | Vanilla CSS3 (CSS custom properties, Grid, Flexbox) |
| **Interactivity** | Vanilla JavaScript (ES6+) |
| **AI Agent** | IBM watsonx Orchestrate (embedded via `wxoLoader.js`) |
| **Fonts** | System font stack (`-apple-system`, `Segoe UI`, `system-ui`) |
| **Icons** | Inline SVG (no external dependencies) |
| **Deployment** | Static file — no build tool, no framework, no server |

---

## 🤖 IBM watsonx Orchestrate Integration

The AI chat agent is embedded using IBM's official `wxoLoader.js` script. The configuration lives in `<head>` so it is available globally before the loader initialises.

### Configuration Block (in `<head>`)

```html
<script>
  window.wxOConfiguration = {
    orchestrationID: "f6be8f3b04eb44c6af56921bdf117162_8bc5eaa9-c5b3-4ddb-bee7-efc00a9ac12b",
    hostURL: "https://au-syd.watson-orchestrate.cloud.ibm.com",
    rootElementID: "root",
    deploymentPlatform: "ibmcloud",
    crn: "crn:v1:bluemix:public:watsonx-orchestrate:au-syd:a/f6be8f3b04eb44c6af56921bdf117162:8bc5eaa9-c5b3-4ddb-bee7-efc00a9ac12b::",
    chatOptions: {
        agentId: "ae38731f-4286-4b2c-ad25-531d88265984",
    }
  };
  setTimeout(function () {
    const script = document.createElement('script');
    script.src = `${window.wxOConfiguration.hostURL}/wxochat/wxoLoader.js?embed=true`;
    script.addEventListener('load', function () {
        wxoLoader.init();
    });
    document.head.appendChild(script);
  }, 0);
</script>
```

### Mount Point (in `<body>`)

```html
<div id="root"></div>
```

### How It Works

```
Browser loads page
      │
      ▼
wxOConfiguration set in window (head)
      │
      ▼
setTimeout(0) → createElement('script')
      │
      ▼
wxoLoader.js fetched from IBM CDN
      │
      ▼
wxoLoader.init() called
      │
      ▼
Chat widget mounts into <div id="root">
      │
      ▼
Floating chat bubble appears (bottom-right)
```

### Requirements for Agent to Work

- ✅ Active internet connection (loads `wxoLoader.js` from IBM CDN)
- ✅ Valid `orchestrationID`, `crn`, and `agentId`
- ✅ IBM watsonx Orchestrate instance active in `au-syd` region
- ✅ File opened directly in a browser (not inside an iframe sandbox)

---

## 📁 Project Structure

```
Mental_Awareness_Agent/
│
├── mental_health_agent.html     # Single-file application (all HTML + CSS + JS)
└── README.md                    # This file
```

---

## 🚀 Getting Started

### Option 1 — Open directly (simplest)
```
Double-click mental_health_agent.html
```

### Option 2 — Serve locally (recommended for development)
```bash
# Python 3
python -m http.server 8080

# Node.js (npx)
npx serve .

# Then open: http://localhost:8080/mental_health_agent.html
```

### Option 3 — Deploy to static hosting
Upload `mental_health_agent.html` to any static host:
- **GitHub Pages** — push to a repo, enable Pages
- **Netlify** — drag & drop the file
- **Vercel** — `vercel deploy`
- **IBM Cloud Object Storage** — static website hosting

> ⚠️ Ensure your IBM watsonx Orchestrate instance has the correct CORS/allowed-origins configured if hosting on a custom domain.

---

## ⚙️ Configuration

To adapt this project for your own IBM watsonx Orchestrate agent, update the config block in `<head>` of `mental_health_agent.html`:

| Property | Description |
|---|---|
| `orchestrationID` | Your IBM Orchestrate instance ID |
| `hostURL` | Regional endpoint (`au-syd`, `us-south`, `eu-de`, etc.) |
| `rootElementID` | ID of the HTML element the widget mounts into (default: `"root"`) |
| `deploymentPlatform` | Always `"ibmcloud"` for IBM Cloud deployments |
| `crn` | Your IBM Cloud Resource Name for the watsonx Orchestrate instance |
| `chatOptions.agentId` | The specific agent ID to load inside the widget |

---

## 📞 Crisis Resources

> If you or someone you know is in crisis, please reach out immediately. Help is free and confidential.

| Resource | Contact | Availability |
|---|---|---|
| **988 Suicide & Crisis Lifeline** | Call or Text `988` | 24/7 — USA |
| **Crisis Text Line** | Text `HOME` to `741741` | 24/7 — USA, UK, CA, IE |
| **IASP Crisis Centres** | [iasp.info](https://www.iasp.info/resources/Crisis_Centres/) | Worldwide directory |
| **NAMI Helpline** | `1-800-950-6264` | Mon–Fri 10am–10pm ET |
| **Veterans Crisis Line** | Call `988`, press `1` | 24/7 — USA Veterans |
| **SAMHSA Helpline** | `1-800-662-4357` | 24/7 — USA |

---

## 🧘 Coping Techniques

### Box Breathing (4-4-4-4)
1. Inhale through nose — **4 seconds**
2. Hold — **4 seconds**
3. Exhale through mouth — **4 seconds**
4. Hold — **4 seconds**
5. Repeat 4–6 cycles

### 5-4-3-2-1 Grounding
- **5** things you can **see**
- **4** things you can **feel**
- **3** things you can **hear**
- **2** things you can **smell**
- **1** thing you can **taste**

### Thought Reframing (CBT)
1. Write the negative thought
2. Identify the triggered emotion
3. Find evidence for and against it
4. Write a balanced, realistic alternative
5. Notice the mood shift

### Progressive Muscle Relaxation
1. Sit or lie comfortably
2. Tense feet/calves for 5 seconds, release
3. Work upward — thighs, abdomen, hands, arms, shoulders
4. Scrunch face muscles for 5 seconds, release
5. Notice full-body relaxation

---

## ⚠️ Warning Signs

The following are clinically recognised warning signs of suicide risk. If you notice these in yourself or someone else, seek help immediately.

- Talking about wanting to die or to kill oneself
- Looking for ways to kill oneself (searching online, acquiring means)
- Talking about feeling hopeless or having no reason to live
- Talking about feeling trapped or in unbearable pain
- Increasing use of alcohol or drugs
- Withdrawing from friends, family, and community
- Extreme mood swings or sudden calmness after deep distress
- Giving away prized possessions
- Sleeping too little or too much
- Displaying extreme agitation or reckless behaviour
- Saying goodbyes as if they will not be seen again
- Dramatic changes in behaviour, appearance, or appetite

---

## ⚖️ Disclaimer

> **MindBridge is an AI-powered awareness and support tool. It is NOT a substitute for professional mental health care.** It does not provide diagnosis, therapy, or medical advice. If you are in crisis or experiencing a psychiatric emergency, call **988** (USA) or your local emergency services immediately. Always consult a qualified mental health professional for personalised care.

---

## 📄 License

This project is intended for educational and awareness purposes. All crisis hotline information is publicly available. The IBM watsonx Orchestrate integration uses your own licensed IBM Cloud instance.

---

<div align="center">

**MindBridge** — *Because every mind matters.*

Powered by [IBM watsonx Orchestrate](https://www.ibm.com/products/watsonx-orchestrate)

</div>
