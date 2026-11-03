# Fady Hassanein

**AI engineer — I build LLM agents, RAG systems, and bilingual (Arabic/English) products that ship.**

Most of my work sits where language models meet a real constraint: Egyptian Arabic dialect, accessibility needs that a checkbox can't capture, procurement documents that must never be hallucinated. I care about systems that are honest about what they don't know.

`Python` · `TypeScript` · `LangChain` · `FastAPI` · `Next.js` · `React` · `Streamlit` · `OpenAI / Claude / Gemini` · `PyTorch`

---

## Selected work

### 🟢 [Baseera · بصيرة](https://github.com/FadyHassanein/baseera) — bilingual AI accessibility intelligence
**[Live demo →](https://baseera.up.railway.app/)**

Reads photos of any venue and produces a confidence-scored accessibility report tailored to one visitor's functional needs — not a binary "accessible / not."

- Vision models estimate threshold heights, grab-bar placement, transfer space and lighting **from pixels**, not from venue-supplied tags
- Four explicit confidence states (*Confirmed · Uncertain · Unknown · Likely inadequate*) — a confident wrong answer is worse than no answer
- Full Arabic RTL support; handles Saudi and Egyptian dialect input directly
- Asks about *experience*, never about diagnosis

Submitted to the **King Salman Center for Disability Research AI Hackathon for Persons with Disabilities** (Riyadh, 2026), Daily Life & Assistive Technologies track.
`Next.js` `TypeScript` `vision models` `i18n/RTL`

---

### 🤖 [MIR](https://github.com/FadyHassanein/Miragent3) — Egyptian Arabic support chatbot
An AI assistant for Egyptian women, built to understand and reply in Egyptian dialect rather than Modern Standard Arabic — a distinction most Arabic NLP tooling ignores.

- LangChain agent with Tavily web search for current information
- FastAPI backend, WebSocket real-time messaging, WhatsApp integration
- React + Material-UI interface

`FastAPI` `LangChain` `OpenAI` `WebSockets` `React`

---

### 🗣️ [English Dialect Classification](https://github.com/FadyHassanein/English-Accent-Classification2) — accent detection from video
Paste a video URL from any of 1000+ sources; get ranked dialect predictions with confidence scores. Built for recruitment screening workflows.

- Transformer audio-classification models from Hugging Face
- Nine English dialects with probability distribution, not a single label
- React + Material-UI frontend over a Python inference backend

`transformers` `Hugging Face` `audio classification` `React`

---

### 📄 [RFQ Document Intelligence](https://github.com/FadyHassanein/RFQ-V2) — grounded Q&A over tender PDFs
Chat with procurement documents under a strict no-hallucination constraint: every answer is extracted from retrieved context or the model declines to answer.

- PyMuPDF4LLM parsing tuned for the tables and clause structure RFQs actually contain
- Session-scoped document cache so repeat queries don't re-parse

`OpenAI` `RAG` `PyMuPDF4LLM` `Streamlit`

---

### 🦯 [Voice Obstacle Detection](https://github.com/FadyHassanein/Voice_Obstacle_Detection) — spoken navigation alerts
Real-time YOLOv8 webcam detection that speaks obstacles aloud for visually impaired users, with thread-safe TTS so speech never blocks the detection loop.

`YOLOv8` `OpenCV` `pyttsx3`

---

### 📘 [Mind AI](https://github.com/FadyHassanein/RAG-With-Deep-Seek) — fully local research assistant
RAG over your PDFs with **zero data leaving the machine** — DeepSeek-R1 served by Ollama, LangChain retrieval, PDFPlumber extraction.

`Ollama` `DeepSeek-R1` `LangChain`

---

## Also here

| Repo | What it is |
|---|---|
| [InsightAgentBot](https://github.com/FadyHassanein/ATE-AIV2) | LLM agent over an internal database **and** the live web, with session management and search analytics |
| [Business Analytics Dashboard](https://github.com/FadyHassanein/Business-Analytics-Dashboard) | Workforce analytics — multi-dimension filtering, salary and tenure distributions, CSV export |
| [YouTube Analytics Dashboard](https://github.com/FadyHassanein/Youtube_Dashboard) | Channel performance, audience segmentation by country and subscription status |
| [Face Detection App](https://github.com/FadyHassanein/Face_Detection_App) | OpenCV face / eye / smile detection with real-time webcam mode |

---

## Stats

![Fady's GitHub stats](https://github-readme-stats.vercel.app/api?username=FadyHassanein&show_icons=true&theme=radical&include_all_commits=true)
![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=FadyHassanein&layout=compact&theme=radical&langs_count=8)

---

## Contact

📍 Egypt · open to AI / ML engineering roles and collaborations

- 📧 **[fadyhass3@gmail.com](mailto:fadyhass3@gmail.com)**
- 💼 **[LinkedIn](https://www.linkedin.com/in/fady-tarek-f1t1/)**
