<!-- ══════════════════════════════════════════════════════════════════════ -->
<!--                   SANIDHYA DWIVEDI — GITHUB PROFILE README             -->
<!-- ══════════════════════════════════════════════════════════════════════ -->

<div align="center">

```
 ███████╗ █████╗ ███╗   ██╗██╗██████╗ ██╗  ██╗██╗   ██╗ █████╗ 
 ██╔════╝██╔══██╗████╗  ██║██║██╔══██╗██║  ██║╚██╗ ██╔╝██╔══██╗
 ███████╗███████║██╔██╗ ██║██║██║  ██║███████║ ╚████╔╝ ███████║
 ╚════██║██╔══██║██║╚██╗██║██║██║  ██║██╔══██║  ╚██╔╝  ██╔══██║
 ███████║██║  ██║██║ ╚████║██║██████╔╝██║  ██║   ██║   ██║  ██║
 ╚══════╝╚═╝  ╚═╝╚═╝  ╚═══╝╚═╝╚═════╝ ╚═╝  ╚═╝   ╚═╝   ╚═╝  ╚═╝
```

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=22&duration=2800&pause=900&color=00FFD1&center=true&vCenter=true&multiline=false&width=700&lines=AI+%2F+ML+Engineer+%7C+Full-Stack+Architect;RAG+Pipelines+%7C+LLMs+%7C+Computer+Vision;Building+Systems+That+Think+%F0%9F%A7%A0;VIT+Bhopal+%E2%86%92+IIT+Kanpur+%E2%86%92+Beyond" alt="Typing SVG" />

<br/>

[![Visits](https://komarev.com/ghpvc/?username=sanidhyadwivedi2004&style=for-the-badge&color=00FFD1&label=PROFILE+VISITS)](https://github.com/sanidhyadwivedi2004)
[![LinkedIn](https://img.shields.io/badge/LINKEDIN-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sanidhya-dwivedi-a75a7427a/)
[![Gmail](https://img.shields.io/badge/MAIL-Reach+Out-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sanidhyadwivedi2004@gmail.com)

</div>

---

## `> whoami`

```yaml
name        : Sanidhya Dwivedi
role        : AI/ML Engineer + Full-Stack Developer
degree      : B.Tech CSE @ VIT Bhopal (2023–2027)
experience  :
  - IIT Kanpur — Project Intern (RAG/MLOps)
  - HEPro AI   — AI & ML Intern (Mentoring Intelligence System)
focus_areas : [LLMs, RAG, Computer Vision, Full-Stack Web, MLOps]
hackathons  : [IIT BHU — Merit, IIT Guwahati — Merit Award]
currently   : Exploring Agentic AI & Scalable ML Systems
motto       : "Build systems that are smarter than their creators."
```

---

## `> ls -la /skills`

<div align="center">

### ⚙️ AI / ML Stack

![Python](https://img.shields.io/badge/Python-Expert-3776AB?style=flat-square&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF5733?style=flat-square)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=flat-square&logo=google&logoColor=white)

### 🌐 Full-Stack & Backend

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)

</div>

---

## `> cat /projects --verbose`

<details>
<summary><b>🧠 Swasthya Sarthi — Medical RAG Chatbot</b> &nbsp;<code>[IIT Kanpur · 2025]</code></summary>

<br/>

> **Stack:** Ollama LLM · HuggingFace Embeddings · ChromaDB · Flask · AWS · MLOps

- 🔬 Engineered a production-grade RAG pipeline processing **55,000+ medical records**
- ⚡ Achieved sub-10 second end-to-end query latency on AWS-automated ML pipelines
- 📈 Boosted vector retrieval performance by **20%** through ChromaDB optimization
- 🛠️ Integrated Flask API layer for real-time chatbot inference and deployment

```python
# Architecture snapshot
pipeline = RAGPipeline(
    llm       = Ollama(model="llama3"),
    embedder  = HuggingFaceEmbeddings(model="all-MiniLM-L6-v2"),
    vectordb  = ChromaDB(collection="medical_corpus_55k"),
    retriever = Retriever(top_k=5, rerank=True)
)
```

🔗 [GitHub](https://github.com/sanidhyadwivedi2004)

</details>

---

<details>
<summary><b>✋ Real-Time Hand Gesture Detection</b> &nbsp;<code>[Computer Vision · 2025]</code></summary>

<br/>

> **Stack:** Python · OpenCV · MediaPipe · JSON Model Storage

- 🎯 Achieved **90%+ classification accuracy** on custom-labeled gesture datasets
- 🎥 Sustained **30 FPS real-time inference** on live video streams
- 📦 Deployed with lightweight JSON-based model storage for portability & scalability
- 🧪 Benchmarked against 15+ gesture classes with robust edge-case handling

🔗 [GitHub](https://github.com/sanidhyadwivedi2004/Sign-language-detection)

</details>

---

<details>
<summary><b>🧾 AI Memory Jar — Emotional Analytics Platform</b> &nbsp;<code>[Full-Stack AI · 2025]</code></summary>

<br/>

> **Stack:** Next.js · TypeScript · PostgreSQL · Prisma · OpenAI API · NLP · Sentiment Analysis

- 📔 Built a scalable AI journaling platform supporting **100+ user memory entries**
- 🤖 Integrated LLM-driven sentiment & emotion analysis with **sub-second inference**
- 📊 Developed an analytics dashboard with **5+ sentiment filters** and temporal visualizations
- 🔐 Implemented secure server-side auth with credit-controlled LLM workflows

</details>

---

<details>
<summary><b>⚖️ NyaySetu — Legal Assistance Platform</b> &nbsp;<code>[Startup Prototype · 2025–Present]</code></summary>

<br/>

> **Stack:** React · Node.js · Express.js · MongoDB · JavaScript

- 🏛️ Building a full-stack platform for scalable digital legal assistance delivery
- 📱 Engineered responsive React UIs with RESTful backend services
- 🗄️ MongoDB-backed secure and efficient data architecture

</details>

---

<details>
<summary><b>📡 Smart Server Health Monitor</b> &nbsp;<code>[DevOps · 2025]</code></summary>

<br/>

> **Stack:** Python · Flask · Docker · Prometheus · REST APIs · Email Alerts

- 🖥️ Real-time monitoring of CPU, memory, and service uptime via REST APIs
- 🚨 Automated email alerting system on threshold breaches
- 🐳 Fully containerized with Docker for zero-friction deployment

</details>

---

## `> git log --experience`

```
commit a3f91c2 (HEAD -> main)
Author: Sanidhya Dwivedi <sanidhyadwivedi2004@gmail.com>
Date:   Jan–Mar 2026

    feat: AI & ML Intern @ HEPro AI (AI Product Development)
    - Designed data-driven student academic, wellness & career mentoring framework
    - Built scoring algorithms → Academic Score, Productivity Score, Career Readiness Score
    - Applied K-Means Clustering for behavioral segmentation of 1000s of students
    - Tech: Python, Pandas, NumPy, scikit-learn, Matplotlib, Jupyter, CSV Pipelines

commit 7bc04d1
Author: Sanidhya Dwivedi <sanidhyadwivedi2004@gmail.com>
Date:   May–Jul 2025

    feat: Project Intern @ IIT Kanpur — Swasthya Sarthi RAG Chatbot
    - Built & deployed end-to-end medical RAG chatbot with AWS MLOps pipeline
    - 55K+ records | <10s latency | 20% retrieval improvement
    - Tech: Ollama, HuggingFace, ChromaDB, Flask, AWS
```

---

## `> cat certifications.txt`

| 🏅 Certification | 🏢 Issuer |
|---|---|
| Oracle Cloud Infrastructure 2025 Generative AI Professional | Oracle |
| IBM SkillsBuild AI Fundamentals | IBM |
| Google IT Support Certificate | Google |
| Software Engineer Certificate | HackerRank |
| Bits and Bytes of Computer Networking | Google / Coursera |
| Python Essentials 1 | Cisco |

---

## `> ./stats --github`

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=sanidhyadwivedi2004&show_icons=true&theme=chartreuse-dark&hide_border=true&bg_color=0d1117&title_color=00FFD1&icon_color=00FFD1&text_color=c9d1d9&count_private=true" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sanidhyadwivedi2004&layout=compact&theme=chartreuse-dark&hide_border=true&bg_color=0d1117&title_color=00FFD1&text_color=c9d1d9&langs_count=8" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=sanidhyadwivedi2004&theme=dark&hide_border=true&background=0d1117&stroke=00FFD1&ring=00FFD1&fire=FF6B6B&currStreakLabel=00FFD1" />

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=sanidhyadwivedi2004&bg_color=0d1117&color=00FFD1&line=00FFD1&point=FFFFFF&area=true&hide_border=true" />

</div>

---

## `> cat achievements.log`

```
[MERIT]  Serve Smart Hackathon         — IIT BHU
[MERIT]  Business Case Competition     — IIT Guwahati
[HONOR]  Certificate of Honor          — Dainik Jagran, Kanpur
[INTERN] AI & ML Project Intern        — HEPro AI (Jan–Mar 2026)
[INTERN] RAG/MLOps Project Intern      — IIT Kanpur (May–Jul 2025)
```

---

<div align="center">

### `> ping sanidhyadwivedi2004`

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sanidhya-dwivedi-a75a7427a/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sanidhyadwivedi2004)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sanidhyadwivedi2004@gmail.com)

<br/>

```
╔══════════════════════════════════════════════════════════╗
║  "The best code is the kind that doesn't need comments,  ║
║   the best AI is the kind that doesn't need apologies."  ║
╚══════════════════════════════════════════════════════════╝
```

![Footer](https://capsule-render.vercel.app/api?type=waving&color=00FFD1&height=100&section=footer)

</div>
