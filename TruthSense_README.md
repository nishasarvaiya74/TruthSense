# 🧠 TruthSense  
### *Agentic AI that Detects Fake News & Delivers Verified Truth in Real Time*  
by **Team VeritasAI** — *Nisha Sarvaiya & Kunal Parmar*  

---

## 🏁 Overview  
**TruthSense** is an **Agentic AI-powered misinformation detector** that continuously scans online platforms, verifies claims using trusted APIs, and provides users with *clear, credible, and fast* fact-checked updates.  

When false or doubtful content appears online, TruthSense automatically:  
1️⃣ **Collects** trending posts from multiple sources (news, blogs, social media)  
2️⃣ **Verifies** facts using APIs like *Google Fact Check*, *Wikipedia*, and *official portals*  
3️⃣ **Explains** the verdict in simple language with a *credibility score (0–100)* and trusted links.  

During emergencies, TruthSense activates **Crisis Mode**, which pushes verified alerts instantly through a **Dashboard or WhatsApp Bot**, helping reduce panic and misinformation spread.  

---

## 🌐 Live Track  
**MumbaiHacks 2025 — Track 3: Misinformation**  
> Problem: *Create an Agentic AI system that continuously scans multiple sources of information, detects emerging misinformation, verifies facts, and provides easy-to-understand updates to the public.*  

---

## 🚀 Features  
✅ Real-time misinformation detection  
✅ Credibility score with 3 reason points  
✅ Source Provenance Card (timeline of claim evolution)  
✅ Cross-media verification (text, images, memes)  
✅ **Crisis Mode Dashboard & WhatsApp Bot**  
✅ Multilingual support (English, Hindi, Marathi, etc.)  
✅ Community Trust Layer — verified users can confirm/flag claims  

---

## ⚙️ Tech Stack  

| Layer | Tools / Frameworks |
|-------|--------------------|
| 🧠 AI Agents | **LangChain**, **LlamaIndex**, **OpenAI API**, **Ollama models** |
| 🔍 Data Sources | **Google Fact Check API**, **News API**, **Wikipedia API**, **Twitter API** |
| 💾 Database | **MongoDB** / **Firebase** |
| 🖥️ Backend | **FastAPI** / **Node.js (Express)** |
| 💡 Frontend | **React.js** / **Streamlit Dashboard** |
| ☁️ Deployment | **AWS**, **Hugging Face Spaces**, or **Render** |

---

## 🧩 Agentic Workflow  

```
[Collector Agent] → Finds trending topics from online data
      ↓
[Verifier Agent] → Checks claim using trusted APIs
      ↓
[Summarizer Agent] → Generates easy-to-understand explanations
      ↓
[Output] → Credibility Score + Reasons + Verified Sources
```

---

## 🧠 Example Output  

| Input | “Government announces free petrol for all citizens.” |
|--------|------------------------------------------------------|
| Credibility Score | 12 / 100 |
| Verdict | ❌ False |
| Verified By | Google Fact Check, PIB India |
| Explanation | No official government statement found. Misleading post traced to a meme page. |
| Sources | [PIB Fact Check](https://pib.gov.in/), [Google Fact Check Explorer](https://toolbox.google.com/factcheck/explorer) |

---

## 🧪 Setup Guide  

### 1️⃣ Clone Repository  
```bash
git clone https://github.com/yourusername/TruthSense.git
cd TruthSense
```

### 2️⃣ Install Dependencies  
```bash
pip install -r requirements.txt
# or for Node.js backend
npm install
```

### 3️⃣ Set Up API Keys  
Create a `.env` file and add:  
```
OPENAI_API_KEY=your_key_here
GOOGLE_FACTCHECK_API=your_key_here
NEWS_API_KEY=your_key_here
MONGO_URI=your_connection_string
```

### 4️⃣ Run App  
```bash
python app.py
# or
npm start
```

### 5️⃣ Open Dashboard  
Visit: [http://localhost:8501](http://localhost:8501) or [http://localhost:3000](http://localhost:3000)

---

## 🖼️ Screenshots / Demo  

| Feature | Preview |
|----------|----------|
| Dashboard | (insert dashboard.png) |
| Claim Card | (insert claim_card.png) |
| Crisis Mode | (insert crisis_mode.png) |
| WhatsApp Bot | (insert bot_demo.png) |

---

## 🎥 Demo Video  
[📺 Watch Demo (YouTube Link)](https://youtu.be/your-demo-link)  
*(3-minute explanation of problem, workflow, and demo UI)*

---

## 💡 Future Improvements  
- Add image deepfake detection  
- Improve accuracy via multi-agent reasoning loop  
- Integrate voice-based query system  
- Expand language support to all Indian regional languages  

---

## 🧑‍💻 Team VeritasAI  
| Name | Role | Responsibility |
|------|------|----------------|
| **Nisha Sarvaiya** | Lead Developer | Agent workflow, testing |
| **Kunal Parmar** | Backend Engineer | API integration, database |

---

## 🤝 Acknowledgements  
Thanks to **MumbaiHacks 2025**, **Devfolio**, and **OpenAI / Google APIs** for the platform and resources.  
> “Truth builds trust — and trust builds society.” 💬  

---

## 📜 License  
MIT License © 2025 **Team VeritasAI**
