# 🧠 AI-Powered Betting Assistant – Chrome Extension
![Made with HTML](https://img.shields.io/badge/Frontend-HTML%2FCSS%2FJS-blue)
![Chrome Extension](https://img.shields.io/badge/Platform-Chrome--Extension-green)
![AI Integration](https://img.shields.io/badge/AI-OpenAI%2FDeepSeek-purple)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)



A smart, lightweight Chrome Extension that uses AI to analyze sports betting odds, detect arbitrage opportunities, and offer intelligent, real-time betting suggestions — all inside a floating calculator panel that works on any website.

> Built for real bettors, with real-time insights — right where the action happens.

---
## 🌟 Project Highlights

- 🎯 **Modes**: Arbitrage Calculator, AI-Based Prediction, Multi-Bet Placer (in progress)  
- 🧠 **AI Integration**: Uses OpenAI / DeepSeek via API (no ML expertise required)  
- 💡 **Real-Time Use**: Injects a floating panel into any betting site  
- ⚙️ **Built With**: HTML, CSS, JS, Chrome APIs, OpenAI API, marked.js  
- 🔐 **No Backend**: 100% client-side – lightweight and privacy-safe

---

## 🚀 Key Features

### 🎯 Mode 1: Arbitrage Calculator
Gives bettors a **mathematical edge** by leveraging odds differences across bookmakers:
- Detects flaws in the bookie system
- Calculates precise stake splits across outcomes
- Locks in **risk-free profit** regardless of match outcome
- Empowers users to **back both teams intelligently**

### 🤖 Mode 2: Bet Possibility Analyzer *(AI-Powered)*
Integrates with DeepSeek/OpenAI APIs to assist in decision-making:
- Accepts team odds or manual match query
- Generates **short, point-wise analysis** — no long paragraphs
- Focuses on **live or upcoming matches only**
- Includes reset buttons, toggles, and markdown rendering (cleaned output)

### 🔄 Mode 3: Multi Bet Placer *(In Progress)*
Designed to support **parlay/multi-leg betting** with:
- Input of multiple bets across different matches
- Real-time calculation of **combined probability** and **expected payout**
- Smart stake suggestions to maximize returns and manage risk
- Helps users plan **accumulator** or **combo** bets efficiently

> This mode is under active development, with a focus on becoming the go-to tool for advanced bettors using strategy, probability, and AI to stay ahead.

---

## 📊 Modes Overview

| Mode                | Purpose                         | Status         | Tech Used                 |
|---------------------|----------------------------------|----------------|----------------------------|
| Mode 1: Arbitrage    | Detect risk-free profit from odds | ✅ Completed    | HTML, JS, Math Logic       |
| Mode 2: AI Analyzer  | Predict team win chances          | ✅ Completed    | OpenAI/DeepSeek, marked.js |
| Mode 3: Multi-Bet    | Plan combo bets + payout calc     | 🔄 In Progress | Planned: Smart Math, UI UX |

---


## 🧪 Real-Life Use Case

> Imagine you're on a betting site watching live odds.  
You click the extension — a floating calculator appears.  
You enter odds from two bookmakers.  
The tool tells you:
- Whether arbitrage is possible  
- How much to stake on each side  
- Which team has better winning chances via AI  

All within the same tab. No switching apps. No guesswork. Just clarity.

---

## 💡 Why a Chrome Extension?

Instead of building a separate website, this tool runs directly on betting platforms through a Chrome Extension:
- Injects a **floating calculator** into the right side of any webpage
- Offers **immediate, context-aware analysis** without switching tabs
- Built for speed, simplicity, and real-time execution — exactly where decisions are made

---

## 🎥 Demo & Screenshots

## 📸 Feature Walkthrough (Screenshots)

### 🧮 Arbitrage Calculator – Identify Profitable Betting Opportunities

#### ✅ Real-Time Arbitrage Calculation
![Arbitrage Output](./screenshots/Mode1/1.1.png)

#### 📊 Bet Bet Entries
![Arbitrage History](./screenshots/mode1/1.2.png)

#### 🧾 Final Win Slip with Profit Summary
![Arbitrage Result](./screenshots/mode1_result.png)

---

### ⚔️ AI-Powered Team Comparison – Predict Likely Winners

#### 🧠 AI Analysis of Team Odds & Match Potential
![Team Comparison Output](./screenshots/mode2_output.png)

#### 📊 Bet Entries
![Team Comparison History](./screenshots/mode2_history.png)

#### 🧾 Final Win Slip Based on AI Recommendation
![Team Comparison Result](./screenshots/mode2_result.png)

---

### 🎯 Manual Bet Analyzer – Custom Scenario Evaluation

#### 🧠 AI Output for User-Defined Betting Scenario
![Manual Query Output](./screenshots/mode3_output.png)

#### 📊 Bet Entries
![Manual Query History](./screenshots/mode3_history.png)

#### 🧾 Final Win Slip with Suggested Outcome
![Manual Query Result](./screenshots/mode3_result.png)


<!-- 
### 🎬 Video Demo

> *(Insert Loom or YouTube demo link here)*  
> Example: [Watch the Demo](https://your-demo-link.com)
-->

---

## ⚙️ How It Works

- Uses **HTML, CSS, JavaScript** — completely frontend-based
- Injects via **Chrome Extension APIs** (Manifest V3)
- AI features powered via **DeepSeek/OpenAI APIs**
- Output rendering via `marked.js` (clean markdown parser)
- No backend, no hosting, no delays

---
## 🔧 Manual Install Instructions (for GitHub Users)

Want to try the extension locally before it’s published on the Chrome Web Store? You can get it running in under a minute:

1. 📦 **Download** this repository as a ZIP file from GitHub  
2. 🗂️ **Extract** the ZIP anywhere on your computer  
3. 🌐 Open **Google Chrome** and go to: `chrome://extensions/`  
4. 🧪 Enable **Developer Mode** (top right corner toggle)  
5. 📂 Click on **“Load unpacked”**  
6. ✅ Select the **folder you just extracted**

You’re almost there! 🚀

---

### 🔐 Setting Up the API Key (for AI Analysis)

To use Mode 2 (Bet Possibility Analyzer), you'll need an API key from OpenAI or DeepSeek:

1. Go to your API provider (like [OpenAI](https://platform.openai.com/) or [OpenRouter](https://openrouter.ai/))  
2. Copy your **API key**  
3. In the project folder, open the file called `config.js`  
4. Replace the placeholder value like this:

```js
// Inside config.js
const API_KEY = "your-api-key-here";
```

---

## 🧱 Tech Stack

- HTML / CSS / JavaScript
- Chrome Extensions (Manifest V3)
- OpenAI / DeepSeek APIs
- Markdown rendering with `marked.js`

---

## 🌱 Future Enhancements

- Final release of **Mode 3: Multi Bet Placer**
- Auto-fetch odds from top sportsbooks
- Dark mode / Compact UI options
- Past bet history (using `localStorage`)
- Language support for global markets

---

## 🎯 Why This Project?

> “I wanted to blend AI with something practical — where seconds matter and every edge counts. This extension reflects my interest in intelligent, real-time user experiences, and shows how Chrome Extensions can go beyond automation into meaningful decision support.”

---

## 🙋‍♂️ About Me

**Deepbendu Debnath**  
Full Stack Developer | Chrome Extension Builder | AWS Certified SA | C++ Problem Solver  
Made with ❤️ in India 🇮🇳

---

## 📬 Contact

I'm always open to connect for internships, full-time roles, mentorship, or collaborative builds:

> ✉️ debnathdeepbendu@gmail.com  
💼 [LinkedIn](http://linkedin.com/in/deepbendu-debnath) | 📁 [GitHub](https://github.com/Deepbendu) | 🧩 [LeetCode](https://leetcode.com/deepbendu)


---

## 📌 Disclaimer

This extension is intended for **educational and demonstration purposes only**. Betting involves risk. Always bet responsibly and in accordance with your local laws.

