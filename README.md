# | Soumyadeep Nath | Data Scientist - Data Analyst - Full Stack AI Engineer |

[![Portfolio](https://img.shields.io/badge/Live_Portfolio-Visit-0A0A0A?style=for-the-badge&logo=github&logoColor=white)](https://sdn9300.github.io)

> 🚀 **For the complete interactive experience, visit [sdn9300.github.io](https://sdn9300.github.io)** — this repo is the source code behind the site.
Built with HTML, CSS, and JavaScript — single-file, no frameworks, no build step.
---

## 🎯 About Me

I'm a Data Scientist, Data Analyst and AI Engineer based in Kolkata, India — currently completing 
an **Executive PG Programme in Data Science & AI at IIT Roorkee**, working hands-on 
with Python, SQL, Machine Learning, and production-grade Generative AI systems.


I work across the full stack of a data/AI role: ETL pipelines, SQL analytics, supervised 
ML (scikit-learn), RAG systems with FAISS/Chroma, LLM API integration, and Next.js 
deployment on Vercel. Currently open to **Data Scientist, Data Analyst, and Generative 
AI Engineer** roles — on-site in Kolkata or remote.

I specialize in turning raw data into actionable business insights using Python, SQL, Machine Learning, and Generative AI.

---

## 🛠️ Tech Stack

### Languages

Python • SQL • TypeScript • R

### Frameworks & Platforms

Next.js • Tailwind CSS • Streamlit • Vercel • Git • GitHub

### Data Science & Analytics

NumPy • Pandas • SciPy • EDA • Data Cleaning • ETL Pipelines • Statistical Analysis • Hypothesis Testing • A/B Testing • Data Storytelling

### Machine Learning

scikit-learn • Regression • Classification • Random Forest • Gradient Boosting • Model Evaluation • Time Series Forecasting (Prophet) • Association Rule Mining (Apriori)

### Generative AI

LLM APIs (Groq) • Prompt Engineering • Structured JSON Pipelines • RAG • Embeddings • FAISS • Chroma • Guardrail Design

### Visualization

Plotly • Matplotlib • Seaborn • Jupyter Notebook • Power BI • Google Colab

### Full-Stack & Automation

Playwright • BeautifulSoup4 • Firecrawl API • Google Sheets API (gspread) • YAML • Zod


---

## ✨ Featured Project

### [Gleaner](https://github.com/sdn9300/gleaner-job-scout)
**Multi-Board Job Scraper & ETL Pipeline**  
- Architected a modular ETL pipeline using the Adapter Design Pattern to aggregate job listings from multiple platforms including Naukri, Indeed, RemoteOK, and Wellfound.
- Engineered resilient scraping workflows using custom headers, anti-bot techniques, and Firecrawl structured extraction.
- Built exact-match and similarity-based deduplication pipelines alongside role relevance and location filtering systems.
- Automated reporting through CSV exports and cloud-hosted Google Sheets synchronization.
- Developed a configurable CLI system driven by centralized YAML configuration files for flexible execution and logging control.

### [Overture Outreach](https://frontend-three-azure-97.vercel.app)
**AI-Powered Cold Email Outreach Platform**  
- Architected and implemented a modular backend outreach engine using Python that orchestrates a dual-stage execution pipeline — HTML formatting followed by dynamic tone polishing via the Groq LLM API.
- Configured secure Google OAuth2 flow handling using Google Client APIs to obtain authorization tokens for rate-safe email delivery via the Gmail API.
-  Implemented asynchronous background execution with a Redis queue system and instrumentation via a Prometheus metrics server.
-  Designed a responsive Next.js frontend dashboard using TypeScript and Tailwind CSS, deployed on Vercel, to display run histories, contact filters, and live mail preview.
  
### [AlignResume](https://align-resume-beta.vercel.app)
**AI-Powered Resume Optimization Platform**  
- Architected and deployed an end-to-end full-stack AI web application that parses resumes and job descriptions, scores
alignment quality, and generates ATS-optimized bullet rewrites via a structured JSON prompt pipeline over the Groq API —
with Zod schema validation ensuring deterministic, parseable LLM outputs.
- Implemented an automated truthfulness guardrail layer that validates rewritten bullets against the original resume, blocking
export if hallucinated metrics, employers, or skills are detected — prioritizing honesty over inflation.
- Engineered Playwright-based headless PDF export, rate-limited API proxy (10 runs/hr per IP), and GitHub-Vercel CI/CD
auto-deploy; deepened expertise in LLM application architecture, prompt engineering, and production-grade full-stack AI
deployment.

### [Future Fit](https://skilltrendanalysis-rf3zefgsjaa4l9f8pu2prb.streamlit.app)
**AI-Powered Skill Trend Intelligence Platform**  
- Built an end-to-end Time Series and NLP analysis platform processing 224,605 skill mentions extracted from 50,000+ global
AI/Data Science job postings (2020–2026), using a taxonomy-driven regex extraction engine with word-boundary matching across 100+ skills.
- Engineered a 10-step deterministic cleaning pipeline and developed a Market Basket Analysis (Apriori) engine mapping 230
frequent skill itemsets and extracting association rules (lift ≥0.90, confidence ≥0.38) to identify strong co-occurrence trends
like PyTorch → TensorFlow
- Implemented a tiered yearly forecasting model using Prophet to project demand shares into 2027, integrating a dynamic
fallback to linear trend extrapolation if the 80% confidence interval width exceeded a 1.5× variance threshold.
- Deployed a 6-panel Streamlit dashboard featuring Plotly charts, interactive association rules, and a Groq LLM-powered Skill
Gap Advisor enriched with association rule insights to generate contextual learning paths.
---
📫 Connect With Me

Email: soumyadeep9300@gmail.com

LinkedIn: linkedin.com/in/soumyadeep-nath-941780250

GitHub: github.com/sdn9300

Open to full-time Data Scientist, Data Analyst, and Generative AI opportunities.


## 📂 Repository Structure

```bash
sdn9300.github.io/
├── index.html          # Main portfolio website (single file)
├── profile.jpg         # Profile picture
├── resume.pdf          # Latest resume
└── README.md           # This file

