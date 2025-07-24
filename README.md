# 📰✨ **AI-Powered Newspaper Synthesizer** – Smart, Trustworthy News from Multiple Sources

---

## ❓ PROBLEM STATEMENT

In an age where **misinformation and fake news flood the internet** every single minute, it's becoming incredibly difficult to distinguish between truth and manipulation.  
People no longer know what to trust... 🧠💣

A recent example that sparked our motivation was the **Operation Sindoor** coverage.  
🪖 While monitoring the internet during this event, we noticed **a surge in fake news, clickbait articles, and politically twisted narratives** — especially across social media and unverified blogs.

✅ **The only consistently reliable news?** – Traditional, editorially-reviewed **physical newspapers**.

But manually flipping through multiple papers to find unbiased, complete information is time-consuming and inefficient.

---

📌 That’s why we built **AI-Powered Newspaper Synthesizer** – a cutting-edge system that:
- 📚 Collects news from **multiple reliable newspapers**
- 🧠 **Synthesizes and summarizes** them using **AI + NLP models**
- 🖥️ Presents them on a sleek, **interactive web interface** that anyone can access

The goal? ➤ To empower the public with **fact-based, bias-reduced, digestible news summaries** — all in one place.

---

## 🏢 PROJECT BACKGROUND – **IOC Internship Experience**

This project was developed as part of our prestigious internship at **Indian Oil Corporation (IOC)** 🇮🇳💼

Through this internship, we gained **real-world industry exposure** and learned:
- How IT systems are integrated in large-scale industries
- The importance of information validation in enterprise environments
- Collaboration, agile workflows, and practical engineering in action

### 🛡️ IOC-Specific Extension:
As a byproduct, we are also working on a **dedicated negative-news filtering module** that:
- Detects and flags **news articles portraying IOC in a negative context**
- Helps protect brand reputation and assists in internal media monitoring

This project is not just academic – it's **impactful**, **industry-connected**, and **scalable**.

---

## 🧠 TECH STACK

| Area | Technologies Used |
|------|-------------------|
| ⚙️ Processing | Python, Google Colab |
| 📊 Data | Pandas, Numpy, NLTK |
| 🤖 AI/NLP | HuggingFace Transformers, BERT models |
| 🌐 Frontend | HTML, CSS, JavaScript |
| ☁️ Hosting | Google Drive (HTML + JSON access) |
| 📁 Output Format | JSON (auto-generated from Colab) |

---

## 🖥️ WORKFLOW OVERVIEW

### 🔁 Backend (Colab Notebook):
- Reads multiple newspaper articles
- Uses BART-like models to summarize and synthesize events
- Filters and structures data into JSON format
- Automatically saves the output file to **Google Drive**

### 🌐 Frontend (index.html):
- Reads `multi_source_event_synthesis.json` from the same Drive folder
- Loads news dynamically as cards on the webpage
- Includes:
  - 🔗 Source tags (clickable)
  - 📰 Titles
  - 🧾 AI-generated summary
  - 📖 "Read More ▼" toggle for full article synthesis

---

## ✅ SETUP STEPS

1. **Open** `NEWS_op.ipynb` in Google Colab  
2. **Run all cells** – this will generate `multi_source_event_synthesis.json` in your Google Drive  
3. **Upload** the provided `index.html` to the **same Google Drive folder**  
4. **Right-click** on `index.html` → _Open with_ → _Browser_  
5. ✅ **Done!** You now have an interactive, clutter-free news synthesis tool running live!

> ❗ **NOTE:**  
> JSON and HTML **must** be in the same Google Drive location.  
> Path is **hardcoded in JavaScript** inside `index.html`.

---

## ✨ FEATURES

- 📰 Multi-source news synthesis for a broader perspective  
- ✂️ AI-generated summaries that retain context and eliminate fluff  
- 🔗 Clickable source tags to validate or read full articles  
- 🌙 Dark-mode UI with stylish animations and interactive cards  
- 🧭 Entirely frontend-based – no server setup needed!

---

## 🔮 FUTURE SCOPE

We’ve built a strong foundation – and the possibilities ahead are 🔥

**Planned Features:**
- ⏱️ Real-time scraping using APIs like NewsAPI or RSS feeds  
- 🛡️ IOC brand protection module (Negative news detector)  
- 🔎 Search functionality – filter by keyword or topic  
- 🌐 Language translation support for multi-lingual content  
- 📲 PWA version – installable, offline-friendly version for mobile  
- 🧠 Topic clustering using semantic similarity (BERT/Universal Sentence Encoder)  
- 🧾 Admin panel to approve/reject articles or view insights  

---

## 🎯 IDEAL FOR

- 📚 Students building strong AI + Web integration projects  
- 💼 Interns and freshers showcasing real-world industry collaboration  
- 🧪 Developers experimenting with NLP and summarization  
- 📰 Media companies or researchers looking to automate editorial synthesis  

---

## 🗂️ FILE STRUCTURE

```bash
AI-News-Synthesizer/
├── NEWS_op.ipynb                      # 🔍 Jupyter Notebook (Run in Google Colab)
├── index.html                         # 🖥️ Frontend UI (Open via Google Drive)
└── multi_source_event_synthesis.json # 📦 Auto-generated summary JSON output
