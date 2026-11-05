<div align="center">

# Raymond (DevRay) Klanderman

**Software & AI Engineer · Applied Machine Learning · Agentic Systems**  
*Building AI systems that solve real-world problems.*

[![Portfolio](https://img.shields.io/badge/Portfolio-Explore%20My%20Work-1F6B47?style=for-the-badge&logo=googlechrome&logoColor=white)](https://rayklanderman.is-a.dev/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rayklanderman/)
[![Project Demos](https://img.shields.io/badge/YouTube-Project%20Demos-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/playlist?list=PLJa0i7fpyLmA)
[![Email](https://img.shields.io/badge/Email-Get%20in%20Touch-444444?style=for-the-badge&logo=gmail&logoColor=white)](mailto:info@devray.site)

![GitHub followers](https://img.shields.io/github/followers/rayklanderman?label=Followers&style=flat-square)
![Profile visitors](https://komarev.com/ghpvc/?username=rayklanderman&label=Profile%20Views&style=flat-square)
![WakaTime](https://img.shields.io/badge/WakaTime-Active-2D79C7?style=flat-square)

</div>

---

## What I build

I am an independent **Software & AI Engineer** developing applications for healthcare, education, accessibility, civic participation, and research. I work from problem definition through architecture and delivery: **data modeling, APIs, web/mobile interfaces, AI integration, evaluation, testing, and deployment**.

My priorities are practical: **useful software, measurable behavior, secure defaults, accessibility, and honest limitations**. I am particularly interested in reliable multimodal AI, machine learning, and agentic workflows that can serve people in African contexts and beyond.

> **Engineering principle:** A good demo proves possibility. Reliable software earns trust.

## Featured projects: the engineering behind the product

### 🩺 AI Health Chat — Multimodal health information and tracking

**[Live application](https://aihealthchat.qzz.io/)** · **[Technical case study](https://rayklanderman.is-a.dev/projects/ai-health-chat)** · **Public beta**

I founded and engineered a multilingual **web PWA and WhatsApp health-information platform** designed to help users ask questions through text, speech, and images, keep track of health observations, and prepare structured information to discuss with clinicians.

- **Reasoning and continuity:** Medium/High guidance modes share safety thresholds, while a case-state layer carries relevant history and visual findings across follow-up messages.
- **Structured health data:** Manual entry and consent-based extraction of biometrics; trend visualization and SOAP-style consultation summaries grounded in logged measurements.
- **Architecture and privacy:** React/TypeScript, serverless APIs, Groq with provider fallback, Mistral vision, Supabase PostgreSQL/RLS, webhook validation, and time-limited report sharing.
- **Engineering quality:** Automated type checks, linting, translations, build verification, and documented test suites; emergency escalation and model-output guardrails.

**Recognition:** First place in the **Power Learn Project Class of 2024 graduate hackathon** for the original AI Health Assistant. **Scope:** Educational and triage-support information only—not a diagnostic or prescribing service.

### 📈 Movie Recommendation Project — Applied ML at dataset scale

**[Repository](https://github.com/rayklanderman/mrp-2026)** · **[Case study](https://rayklanderman.is-a.dev/projects/movie-recommendation)** · **ALX optional final project**

I developed a recommendation model for an ExploreAI Academy Kaggle challenge: predict the ratings users would give to movies they had not watched.

- **Approach:** Hybrid recommendation with **50-factor SVD collaborative filtering** and a **LightGBM** predictor, combining interaction-derived and additional engineered features.
- **Data and iteration:** Worked with approximately **10 million ratings** and **156 reported features**, tuning the pipeline through eight public-leaderboard submissions.
- **Result:** Improved **public-leaderboard RMSE from 1.21 to 0.82**. This is a competition score, not a production deployment metric.

**Engineering focus:** Feature engineering, training efficiency, evaluation, reproducibility, and communicating quantitative results responsibly.

### 👁️ EyeSense — Visual assistance designed for accessibility

**[Repository](https://github.com/RealDevRay/eyesense)** · **[Case study](https://rayklanderman.is-a.dev/projects/eyesense)** · **Android-first prototype**

I built a Flutter visual-assistance application for blind and low-vision users, emphasizing predictable speech interaction and careful boundaries around AI-generated interpretations of the physical world.

- **On-device first:** Google ML Kit performs **offline text recognition**; text can be read aloud without uploading images.
- **Cloud vision:** Snapshot-based scene descriptions and image-grounded questions via a **Cloudflare Worker + Groq** architecture, with explicit consent before cloud analysis.
- **Accessible interaction:** TalkBack-aware controls, interruptible text-to-speech, voice-command routing, large touch targets, and high-contrast interface options.
- **Safety and verification:** Output policies prohibit risky claims about road crossing or clear paths. Documentation reports **24 Flutter tests + 10 Worker tests**, with further real-device accessibility checks identified.

**Engineering focus:** Flutter/Dart, accessibility, cloud-edge security, privacy-by-design, and meaningful limitations in assistive AI.

### 🏙️ Sauti Mtaani Nairobi — Privacy-conscious civic intelligence

**[Live platform](https://www.sautimtaani.site/)** · **[Repository](https://github.com/RealDevRay/Sauti-Mtaani-Nairobi)** · **[Case study](https://rayklanderman.is-a.dev/projects/sauti-mtaani-nairobi)**

I developed a structured resident-feedback platform associated with the Office of the Nairobi Woman Representative, designed to make community priorities more understandable without turning resident submissions into unchecked automated decisions.

- **Participation architecture:** Ward-level feedback, bilingual English/Kiswahili interface elements, protected staff access, and aggregate reporting with privacy suppression thresholds.
- **Bounded AI:** A grounded resident FAQ; advisory theme suggestions, moderation pre-filtering, and summaries based on suppressed aggregate counts. **Staff review remains authoritative.**
- **Privacy controls:** PII scrubbing before AI calls, rate limits, audit logging, RLS, and careful separation of identity information from AI inputs.
- **Delivery quality:** Repository documents **GitHub Actions gates for type checking, linting, Vitest, and production builds**.

**Engineering focus:** Responsible AI, public-sector workflows, Next.js, Supabase, Zod, Groq, and human-in-the-loop decisions. Participation does not affect access to public assistance.

### 📚 TutaLearn — AI learning tools for Kenya's CBC

**[Live application](https://tutalearn.qzz.io/)** · **[Case study](https://rayklanderman.is-a.dev/projects/tutalearn)** · **Active development**

I am building a learning platform around **Kenya's Competency-Based Curriculum**, bringing tutoring, lessons, assessments, and learner progress into one application.

- **Learning experience:** Grade/subject-aware AI tutoring, lesson navigation, timed assessments, automated marking, learning streaks, report cards, and parent-facing views.
- **Content engineering:** Curriculum mapping and an AI-assisted generation pipeline with schema validation and review/publishing controls to reduce inaccurate content.
- **Platform design:** Next.js, React, TypeScript, Supabase Auth/PostgreSQL/RLS, and integrations designed for WhatsApp and M-Pesa.
- **Quality:** The current implementation includes automated tests and CI/CD; verify the latest workflow status and test totals in the repository before citing counts. Some third-party features require production configuration.

**Engineering focus:** Reliable educational content, full-stack delivery, assessment logic, data access control, and operational readiness.

### 🔬 Luminae — Five-agent research analysis with Mistral

**[Live application](https://luminae.qzz.io/)** · **[Repository](https://github.com/RealDevRay/luminae)** · **[Video demo](https://youtu.be/ODygWunOA6Y)** · **Mistral Worldwide Hackathon entry**

I developed an agentic research-analysis platform that ingests academic documents and coordinates specialized analysis tasks using Mistral's OCR and language models.

- **Five roles:** Methodology Critic, Dataset Auditor, Experiment Designer, Synthesis Agent, and Grant Generator.
- **Orchestration:** Parallel analysis stages, structured JSON outputs, a FastAPI backend, Next.js frontend, and a PostgreSQL-backed application layer.
- **Cost-aware engineering:** Redis caching, preflight token-cost estimates, budget limits, and usage logging were designed around the hackathon's **$15 API budget**.

**Engineering focus:** Multimodal document ingestion, asynchronous Python, multi-agent workflow design, schema-constrained outputs, and cost controls. Generated research critiques require human verification.

## More systems and experiments

| Project | What I engineered | Explore |
| :--- | :--- | :--- |
| **AutoResearcher** | Seven-agent research/report pipeline using Google Vertex AI ADK and Gemini; Google 5-Day AI Agents capstone. | [Source](https://github.com/rayklanderman/CapstoneProject-Autoresearcher) · [Demo](https://www.youtube.com/watch?v=s5Sktg34uC0) |
| **UrbanSpark AI** | Flutter multimodal entrepreneurship assistant for Kenyan youth, with Sheng-English prompts, Supabase, and local caching. | [Portfolio](https://rayklanderman.is-a.dev/) |
| **PostShifterPro** | Live software product; implementation details and feature descriptions in its portfolio case study. | [Live](https://postshifterpro.qzz.io/) |
| **Live Interviewer** | Live interview-oriented application; engineering details available through its project documentation. | [Live](https://liveinterviewer.vercel.app/) |
| **SerenityAI** | Mental-wellness companion exploring multi-agent assistance and journaling. | [Live](https://serenityai.qzz.io/) · [Demo](https://youtu.be/hTYu1XOeRQE) |
| **Kazi Connect** | Job-matching platform connecting users with opportunities. | [Live](https://kazi-connect.vercel.app/) |
| **Codebase Genius** | AI-assisted development tooling experiment. | [Source](https://github.com/rayklanderman/jaseci-proj) |
| **Weru Digital** | Flutter-based TV, radio, and news experience. | [Source](https://github.com/rayklanderman/weru_digital) |

**Source-code visibility:** Some product repositories are intentionally private. Live products and architecture-focused case studies demonstrate the work without publishing proprietary implementations. A mobile application can also be showcased without an APK release.

## Technology and engineering practices

### Languages, frameworks, and data

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-555555?style=flat-square)
![React](https://img.shields.io/badge/React-149ECA?style=flat-square&logo=react&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

### AI, machine learning, and cloud

![OpenAI](https://img.shields.io/badge/OpenAI-API-412991?style=flat-square&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Google%20Gemini-API-4285F4?style=flat-square&logo=googlegemini&logoColor=white)
![Mistral](https://img.shields.io/badge/Mistral%20AI-API-FC6B35?style=flat-square)
![Groq](https://img.shields.io/badge/Groq-API-D95C40?style=flat-square)
![xAI](https://img.shields.io/badge/xAI-Developer-111111?style=flat-square)
![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Vertex AI](https://img.shields.io/badge/Vertex%20AI-Agent%20Development-4285F4?style=flat-square)
![Cloudflare](https://img.shields.io/badge/Cloudflare%20Workers-F38020?style=flat-square&logo=cloudflareworkers&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

**Applied ML:** LightGBM, SVD, scikit-learn, Pandas, NumPy, SciPy, Jupyter, model evaluation and feature engineering.  
**AI systems:** LLM APIs, multimodal inference, OCR, RAG, agent orchestration, structured outputs, safety policies.  
**Engineering quality:** GitHub Actions, Vitest, Flutter tests, CI/CD, database RLS, API security, consent flows, rate limiting, human-in-the-loop review.

### Developer workflow

![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat-square)
![GitHub Copilot](https://img.shields.io/badge/GitHub%20Copilot-000000?style=flat-square&logo=githubcopilot&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-Developer-D97757?style=flat-square)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

## Selected professional certifications

- **Google Cloud — Professional Cloud Architect**
- **Oracle Cloud Infrastructure 2025 — Certified AI Foundations Associate**
- **Linux Foundation — Kubernetes and Cloud Native Associate (KCNA)**
- **BCS — Foundation Certificate in Generative AI**

Credential verification and additional technical training: [Portfolio credentials](https://rayklanderman.is-a.dev/#credentials).

## Writing, demos, and contact

- **[Project demonstration playlist](https://www.youtube.com/playlist?list=PLJa0i7fpyLmA)** — walkthroughs and working applications
- **[Medium](https://medium.com/@raymondklanderman)** · **[LinkedIn](https://www.linkedin.com/in/rayklanderman/)** · **[X](https://x.com/rayklanderman)** — articles and engineering insights
- **[Portfolio & contact](https://rayklanderman.is-a.dev/#contact)** · **[Freelance services](https://devray.qzz.io)**

---

<div align="center">

**Building practical intelligence, from ideas to impact.**

</div>
