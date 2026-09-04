<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0052D4,50:4364F7,100:6FB1FC&height=180&section=header&text=Vijayan%20Naidu&fontSize=38&fontColor=ffffff&animation=fadeIn&fontAlignY=38" alt="Vijayan Naidu" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=21&duration=2800&pause=900&color=4364F7&center=true&vCenter=true&width=750&lines=AI+%2F+ML+Developer+%7C+Applied+AI+Engineer;Former+AI%2FML+Developer+Intern+%40+Vedika.Health;MSc+Data+Science+%40+Fergusson+College%2C+Pune;Multimodal+AI+%E2%80%A2+GenAI+%E2%80%A2+Intelligent+Document+Processing;Architecting+High-Performance+AI+Pipelines+%F0%9F%9A%80" alt="Typing introduction" />
</p>

<p align="center">
  <a href="https://github.com/vj220803">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="https://www.linkedin.com/in/vijayan-naidu-ba9494330">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:venkatesh45naidu@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://komarev.com/ghpvc/?username=vj220803&label=Profile%20Views&color=4364F7&style=for-the-badge">
    <img src="https://komarev.com/ghpvc/?username=vj220803&label=Profile%20Views&color=4364F7&style=for-the-badge" alt="Views" />
  </a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=4364F7&height=2&section=header" width="70%" alt="" />
</p>

---

## 👨💻 About Me

I'm an **Applied AI/ML Developer and Data Science Postgraduate Student at Fergusson College, Pune**, and former **AI/ML Developer Intern at Vedika.Health** (Jan 1 – Aug 30, 2024).

My expertise centers on developing production-grade machine learning pipelines, multimodal AI architectures, and resilient backend systems. I specialize in **Multimodal Information Verification, Intelligent Document Processing (IDP), Speech/Audio Analytics, and Sovereign Data Systems**, bridging theoretical ML models with high-throughput engineering.

* 🎓 **MSc in Data Science** — Fergusson College, Pune
* 💼 **Former AI/ML Developer Intern** at **Vedika.Health** (Jan 2024 – Aug 2024)
* 🏛️ **Fellowship Contributor** — **Bharat Digital Fellowship (2026 Cohort)** for *Project Samarth*
* 🤖 **Applied AI & GenAI Systems**: Hybrid ensemble models, local LLM inference (Ollama/LLaMA-3.2), and semantic embeddings
* 📄 **Intelligent Document Processing (IDP)**: End-to-end OCR pipelines, layout analysis, OpenCV preprocessing, and entity extraction
* 🎙️ **Multimodal Processing**: Audio analytics (Faster-Whisper STT, Coqui-TTS, Librosa acoustic pitch/energy analysis)
* ⚡ **High-Performance Backends**: Low-latency RESTful APIs (FastAPI, Flask), in-process OLAP engines (DuckDB), and columnar storage (Parquet)
* 🔒 **Data Sovereignty & Provenance**: Zero-cost, privacy-first local AI architectures with cryptographic verification

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&duration=3200&pause=1200&color=0052D4&center=true&vCenter=true&width=660&lines=%E2%9A%A1+Transforming+complex+data+into+production+AI;%F0%9F%A4%96+Building+multimodal+verification+engines;%F0%9F%8C%BE+Engineering+sovereign+data+architectures;%F0%9F%9A%80+Delivering+100%25+reproducible+%26+scalable+systems" alt="Currently building" />
</p>

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&color=0:0052D4,50:4364F7,100:6FB1FC&height=70&text=Featured%20Projects&fontSize=28&fontColor=ffffff&animation=fadeIn" alt="Featured Projects" />
</p>

# 🚀 Featured Projects

## 🧠 SmartCareer — AI-Powered Career Intelligence & Recruitment Platform

An enterprise-grade, dual-portal AI recruitment platform bridging candidate upskilling and recruiter talent acquisition, backed by empirical research: *"SmartCareer: An AI-Powered Integrated Career Development and Recruitment Intelligence Platform"*.

### ✨ Highlights

* 🎙️ **Multimodal AI Mock Interview Engine**: Integrated **Faster-Whisper** (Speech-to-Text) and **Coqui-TTS** with **Librosa acoustic feature extraction** (evaluating pitch standard deviation for confidence, RMS energy consistency, and pause ratios) and **SentenceTransformers (`all-MiniLM-L6-v2`)** for semantic answer scoring.
* 📄 **ATS Compatibility Scoring & Dynamic LaTeX PDF Engine**: Engineered a 4-dimensional scoring algorithm (Keyword match, Skill alignment, Formatting, Section completeness) with a **ReportLab** rendering pipeline generating pixel-perfect, ATS-optimized single-page PDF resumes.
* 👥 **Multi-Factor Candidate Matcher & 5-Tier Ranker**: Calibrated candidate scores across Skills (40%), Experience (25%), Education (15%), and Semantic Embeddings (20%), segmenting applicants into 5 qualification tiers (*Excellent ≥85*, *Strong 70–84*, *Good 55–69*, *Average 40–54*, *Below Average <40*).
* 🎯 **Domain & Competency Gap Prediction**: Deployed multi-label classifiers to parse resume text via **PyMuPDF & Tesseract OCR**, detect domain (IT vs. Non-IT), isolate competency deltas, and dynamically recommend targeted courses and certifications.

**Tech:** Python · Flask · React 18 · PyTorch · Hugging Face SentenceTransformers · Faster-Whisper · Librosa · MongoDB · MySQL · ReportLab

---

## 🛡️ FactualAI — Multimodal Fake News Detection & Verification System

A high-performance multimodal verification platform combining statistical machine learning and local LLM reasoning to evaluate credibility across text, documents, audio, speech, and video.

### ✨ Highlights

* 🏗️ **Architected a Dual-Engine Classification Pipeline**: Blended a 200-estimator **Random Forest Classifier** trained on 768-dimensional `all-mpnet-base-v2` dense semantic embeddings with a local **Ollama LLaMA-3.2:1B** model via a weighted decision formula (`0.60 * RF + 0.40 * LLM`), achieving **95.26% test accuracy**, **0.95 precision**, and an ultra-low **3.57% False Negative Rate** across 44,898 ISOT news articles.
* ⚡ **Engineered a 5-Channel Multimodal Ingestion Pipeline**: Ingested unverified media across raw text, image OCR (OpenCV histogram equalization + pytesseract), audio files (Faster-Whisper base model via CTranslate2), live voice (HTML5 Web Audio API waveform canvas), and YouTube streams (yt-dlp + FFmpeg 128kbps) with **sub-50ms text classification latency**.
* 🌐 **Implemented Multilingual & Live-Stream Surveillance**: Automated real-time RSS scraping across 5 global news agencies (BBC, Reuters, Al Jazeera, The Hindu, NDTV) refreshed every 60s, paired with automated language detection (`langdetect`) and translation (`deep-translator`) supporting **100+ languages**.
* 📊 **Spearheaded Real-Time Telemetry & Full-Stack UI**: Developed a reactive React 19 and Tailwind CSS dashboard featuring 5-second polling telemetry, interactive Recharts distribution analytics, and audit logging for the last 50 queries backed by an asynchronous Flask-CORS backend.

**Tech:** Python 3.11 · Flask · React 19 · Ollama (LLaMA-3.2:1B) · Sentence-Transformers (`all-mpnet-base-v2`) · Faster-Whisper · OpenCV · Scikit-Learn · Recharts · Tailwind CSS

---

## 🌾 Project Samarth — Open Government Data & Climate-Agri Intelligence Engine

*Developed for the Bharat Digital Fellowship (2026 Cohort)*  
A sovereign, zero-cloud-cost analytical engine transforming open government data (`data.gov.in`) across 117 years of IMD climate records (4,188 rows) and Himachal Pradesh agricultural yield records (13 districts, 10 crops).

### ✨ Highlights

* 📉 **Accomplished 75%+ storage reduction** across 117 years of multi-decade government climate and agricultural records by **migrating raw tabular datasets into compressed, columnar Apache Parquet files**.
* ⚡ **Achieved sub-5ms analytical query latency** on multi-dimensional climate-yield correlation queries by **architecting an in-process DuckDB OLAP execution pipeline** directly over columnar Parquet partitions.
* 🎯 **Guaranteed 100% mathematical accuracy and 0% hallucination risk** in conversational data queries by **implementing a deterministic Regex-based NLU-to-SQL compiler** instead of ungrounded generative LLMs.
* 🔒 **Ensured 100% data sovereignty at $0 cloud API expense** by **deploying a fully offline, self-hosted Streamlit analytical suite backed by cryptographic MD5 hash provenance verification**.

**Tech:** Python · Streamlit · DuckDB · Apache Parquet · Pandas · Regex NLU · Cryptographic MD5 Hashing

---

# 🛠️ Technologies & Tools

## 💻 Programming Languages

<p align="center">
  <img src="https://skillicons.dev/icons?i=python" width="55" alt="Python" />
  <img src="https://skillicons.dev/icons?i=r" width="55" alt="R" />
  <img src="https://skillicons.dev/icons?i=cpp" width="55" alt="C++" />
  <img src="https://skillicons.dev/icons?i=c" width="55" alt="C" />
  <img src="https://skillicons.dev/icons?i=js" width="55" alt="JavaScript" />
  <img src="https://skillicons.dev/icons?i=mysql" width="55" alt="SQL" />
</p>

<p align="center">
  <b>Python</b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <b>R</b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <b>C++</b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <b>C</b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <b>JavaScript</b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <b>SQL</b>
</p>

---

## 🤖 Machine Learning & Deep Learning

<p align="center">
  <img src="https://skillicons.dev/icons?i=pytorch" width="55" alt="PyTorch" />
  <img src="https://skillicons.dev/icons?i=tensorflow" width="55" alt="TensorFlow" />
  <img src="https://skillicons.dev/icons?i=sklearn" width="55" alt="Scikit-Learn" />
</p>

<p align="center">
  <b>PyTorch</b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <b>TensorFlow / Keras</b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <b>Scikit-Learn</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Pandas-111827?style=flat-square&logo=pandas&logoColor=white" alt="Pandas" />
  <img src="https://img.shields.io/badge/NumPy-111827?style=flat-square&logo=numpy&logoColor=white" alt="NumPy" />
  <img src="https://img.shields.io/badge/SciPy-111827?style=flat-square&logo=scipy&logoColor=white" alt="SciPy" />
  <img src="https://img.shields.io/badge/Matplotlib-111827?style=flat-square" alt="Matplotlib" />
  <img src="https://img.shields.io/badge/Seaborn-111827?style=flat-square" alt="Seaborn" />
  <img src="https://img.shields.io/badge/MLflow-111827?style=flat-square&logo=mlflow&logoColor=white" alt="MLflow" />
</p>

---

## 🧠 Generative AI, LLMs & Multimodal AI

<p align="center">
  <img src="https://skillicons.dev/icons?i=opencv" width="55" alt="OpenCV" />
</p>

<p align="center">
  <b>OpenCV (Computer Vision)</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Ollama%20(Local%20LLM)-111827?style=flat-square" alt="Ollama" />
  <img src="https://img.shields.io/badge/Hugging%20Face-111827?style=flat-square&logo=huggingface&logoColor=yellow" alt="Hugging Face" />
  <img src="https://img.shields.io/badge/SentenceTransformers-111827?style=flat-square" alt="SentenceTransformers" />
  <img src="https://img.shields.io/badge/Faster--Whisper%20(STT)-111827?style=flat-square" alt="Faster-Whisper" />
  <img src="https://img.shields.io/badge/Coqui--TTS-111827?style=flat-square" alt="Coqui-TTS" />
  <img src="https://img.shields.io/badge/Librosa%20(Acoustics)-111827?style=flat-square" alt="Librosa" />
  <img src="https://img.shields.io/badge/Tesseract%20OCR-111827?style=flat-square" alt="Tesseract OCR" />
  <img src="https://img.shields.io/badge/PyMuPDF-111827?style=flat-square" alt="PyMuPDF" />
  <img src="https://img.shields.io/badge/Vector%20Search%20%26%20Embeddings-111827?style=flat-square" alt="Embeddings" />
</p>

---

## ⚙️ Backend, OLAP & Web Engineering

<p align="center">
  <img src="https://skillicons.dev/icons?i=fastapi" width="55" alt="FastAPI" />
  <img src="https://skillicons.dev/icons?i=flask" width="55" alt="Flask" />
  <img src="https://skillicons.dev/icons?i=react" width="55" alt="React.js" />
  <img src="https://skillicons.dev/icons?i=tailwind" width="55" alt="Tailwind CSS" />
</p>

<p align="center">
  <b>FastAPI</b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <b>Flask</b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <b>React 19</b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <b>Tailwind CSS</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/DuckDB%20(OLAP)-111827?style=flat-square" alt="DuckDB" />
  <img src="https://img.shields.io/badge/Apache%20Parquet-111827?style=flat-square" alt="Apache Parquet" />
  <img src="https://img.shields.io/badge/Streamlit-111827?style=flat-square&logo=streamlit&logoColor=white" alt="Streamlit" />
  <img src="https://img.shields.io/badge/RESTful%20APIs-111827?style=flat-square" alt="REST APIs" />
  <img src="https://img.shields.io/badge/ReportLab%20(PDF)-111827?style=flat-square" alt="ReportLab" />
  <img src="https://img.shields.io/badge/Postman-111827?style=flat-square&logo=postman&logoColor=white" alt="Postman" />
</p>

---

## 🗄️ Databases, Cloud & Storage

<p align="center">
  <img src="https://skillicons.dev/icons?i=postgres" width="55" alt="PostgreSQL" />
  <img src="https://skillicons.dev/icons?i=mysql" width="55" alt="MySQL" />
  <img src="https://skillicons.dev/icons?i=mongodb" width="55" alt="MongoDB" />
  <img src="https://skillicons.dev/icons?i=firebase" width="55" alt="Firebase" />
  <img src="https://skillicons.dev/icons?i=gcp" width="55" alt="GCP" />
</p>

<p align="center">
  <b>PostgreSQL</b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <b>MySQL</b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <b>MongoDB</b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <b>Firebase</b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <b>Google Cloud</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Google%20BigQuery-111827?style=flat-square&logo=googlecloud&logoColor=white" alt="BigQuery" />
  <img src="https://img.shields.io/badge/Cloud%20Storage-111827?style=flat-square" alt="Cloud Storage" />
  <img src="https://img.shields.io/badge/ETL%20Data%20Pipelines-111827?style=flat-square" alt="ETL Pipelines" />
</p>

---

## 🔧 Developer Workflow & DevOps

<p align="center">
  <img src="https://skillicons.dev/icons?i=git" width="55" alt="Git" />
  <img src="https://skillicons.dev/icons?i=github" width="55" alt="GitHub" />
  <img src="https://skillicons.dev/icons?i=docker" width="55" alt="Docker" />
  <img src="https://skillicons.dev/icons?i=linux" width="55" alt="Linux" />
  <img src="https://skillicons.dev/icons?i=vscode" width="55" alt="VS Code" />
</p>

<p align="center">
  <b>Git</b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <b>GitHub</b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <b>Docker</b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <b>Linux / Bash</b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <b>VS Code</b>
</p>

---

# 🔥 GitHub Contribution Streak & Activity

<p align="center">
  <img
    src="https://streak-stats.demolab.com/?user=vj220803&theme=tokyonight&hide_border=true"
    alt="GitHub Contribution Streak"
  />
</p>

<p align="center">
  <img
    src="https://github-stats-extended.vercel.app/api?username=vj220803&show_icons=true&theme=tokyonight&hide_border=true&count_private=true"
    height="175"
    alt="GitHub Stats"
  />
  <img
    src="https://github-stats-extended.vercel.app/api/top-langs/?username=vj220803&layout=compact&theme=tokyonight&hide_border=true"
    height="175"
    alt="Top Languages"
  />
</p>

---

# 🏆 Education & Professional Highlights

* 🎓 **MSc in Data Science** — Fergusson College, Pune
* 💼 **Former AI/ML Developer Intern** — Vedika.Health (Jan 1, 2024 – Aug 30, 2024)
* 🏛️ **Fellowship Contributor** — Bharat Digital Fellowship (2026 Cohort) for *Project Samarth*
* 📜 **Academic Research**: Author & Developer of *"SmartCareer: An AI-Powered Integrated Career Development and Recruitment Intelligence Platform"*
* 🛡️ **Verification Systems**: Developed *FactualAI*, evaluating 44,898 articles with 95.26% accuracy across 5 multimodal channels

---

# 🎯 Core Focus & Competencies

<p align="center">
  <img src="https://img.shields.io/badge/Applied%20AI%20%26%20Machine%20Learning-111827?style=for-the-badge" alt="AI & ML" />
  <img src="https://img.shields.io/badge/Multimodal%20Speech%20%26%20NLP-111827?style=for-the-badge" alt="Speech & NLP" />
  <img src="https://img.shields.io/badge/Intelligent%20Document%20Processing%20(IDP)-111827?style=for-the-badge" alt="IDP" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Local%20LLMs%20%26%20Decision%20Ensembles-111827?style=for-the-badge" alt="Local LLMs" />
  <img src="https://img.shields.io/badge/High--Performance%20OLAP%20%26%20APIs-111827?style=for-the-badge" alt="OLAP & APIs" />
  <img src="https://img.shields.io/badge/Data%20Sovereignty%20%26%20Governance-111827?style=for-the-badge" alt="Data Sovereignty" />
</p>

---

# 📫 Let's Connect

<p align="center">
  <a href="mailto:venkatesh45naidu@gmail.com">
    <img src="https://img.shields.io/badge/Email-venkatesh45naidu%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://www.linkedin.com/in/vijayan-naidu-ba9494330">
    <img src="https://img.shields.io/badge/LinkedIn-Vijayan%20Naidu-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://github.com/vj220803">
    <img src="https://img.shields.io/badge/GitHub-Follow%20%40vj220803-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</p>

<p align="center">
  📍 Pune, Maharashtra, India
</p>

---

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&duration=3000&pause=1000&color=4364F7&center=true&vCenter=true&width=700&lines=Building+impactful+AI+systems+%E2%80%A2+Solving+real-world+problems;From+raw+data+to+production+deployments;%F0%9F%9A%80+Let's+build+the+future+of+AI+together!" alt="Footer animation" />
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:6FB1FC,50:4364F7,100:0052D4&height=100&section=footer" alt="" />
</p>
