<div align="center">

# Raymond Klanderman · DevRay

**Software & AI Engineer | Agentic AI & MCP | Applied Machine Learning | Cloud & Automation**

I design, build, and deploy practical software—from AI agent integrations and machine learning tools to full-stack applications, APIs, mobile products, and cloud services.

[![Portfolio](https://img.shields.io/badge/Portfolio-Explore-25364A?style=flat-square&logo=googlechrome&logoColor=white)](https://rayklanderman.is-a.dev/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-25364A?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rayklanderman/)
[![Project Demos](https://img.shields.io/badge/YouTube-Project_Demos-25364A?style=flat-square&logo=youtube&logoColor=white)](https://www.youtube.com/playlist?list=PLJa0i7fpyLmA)
[![Contact](https://img.shields.io/badge/Email-Get_in_Touch-25364A?style=flat-square&logo=gmail&logoColor=white)](mailto:info@devray.qzz.io)

</div>

---

## About

I'm a **software and AI engineer** working across **agentic systems, Model Context Protocol (MCP), applied ML, multimodal AI, full-stack development, and cloud infrastructure**. I build solutions for real problems in healthcare, education, accessibility, civic technology, and business analytics.

My work spans **problem definition, architecture, implementation, integration, testing, deployment, and improvement**. I also design **task-aware, multi-model AI systems**, using specialized providers, fallback paths, and practical guardrails to balance capability, reliability, and cost. I focus on reproducibility, dependable systems, measurable outcomes, and clear limitations—not just working demos.

## Featured engineering work

### [DevRay DataLab MCP](https://github.com/rayklanderman/devray-datalab-mcp) · Open-source developer tooling

`Python` `MCP` `FastMCP` `scikit-learn` `AutoML` `Testing`

Built and published a **local-first Model Context Protocol server** that enables AI assistants to work with datasets and ML pipelines through structured tools.

- **27 MCP tools** for dataset inspection, data quality, preparation, training, evaluation, experiment workflows, and prediction.
- **ML engineering:** leakage-aware cross-validation, protected holdouts, model comparison, tuning, and reproducible workflows.
- **Developer experience:** asynchronous training jobs, optional Excel/Parquet formats, model export, and PyPI distribution; tested with MCP-compatible coding clients.

[Source code](https://github.com/rayklanderman/devray-datalab-mcp) · [PyPI](https://pypi.org/project/devray-datalab-mcp/) · [Glama](https://glama.ai/mcp/servers/rayklanderman/devray-datalab-mcp)

### [Sauti Mtaani Nairobi](https://github.com/RealDevRay/Sauti-Mtaani-Nairobi) · Open-source civic platform

`Next.js` `TypeScript` `Supabase` `PostgreSQL` `RLS` `AI workflows`

Built a **bilingual resident-engagement platform** with consent-led registration, ward-aware polling across Nairobi's **17 constituencies**, live aggregate results, and protected staff review and reporting workflows.

- **Voting and access controls:** server-authoritative validation, database uniqueness constraints, Supabase row-level security, staff allowlisting, and role-based API checks.
- **Reliability and AI cost controls:** PostgreSQL RPCs for atomic per-lane rate limits and daily AI budget reservations, `Retry-After` handling, and automated tests.
- **Operational delivery:** English/Kiswahili interface, optional human-reviewed AI workflows, documented security boundaries, and CI checks.

[Source code (MIT)](https://github.com/RealDevRay/Sauti-Mtaani-Nairobi) · [Live platform](https://www.sautimtaani.site/) · [Phase 3: atomic rate limits & AI budget holds](https://github.com/RealDevRay/Sauti-Mtaani-Nairobi/commit/fec57ad0d9fa084f1d1f6894b80b3fa43d077efa) · [Security documentation](https://github.com/RealDevRay/Sauti-Mtaani-Nairobi/blob/main/SECURITY.md)

*Participation is voluntary; results reflect a self-selected online sample, not a representative opinion poll.*

## AI applications & software products

### [AI Health Chat](https://aihealthchat.qzz.io/) · Multimodal AI health-information platform

`Next.js / PWA` `Agentic workflows` `Multi-model routing` `MoE-inspired orchestration` `Voice & vision` `Cloudflare Workers AI`

Built a **multilingual, multimodal health-information application** that brings together conversational assistance, image understanding, voice interaction, and structured health reports. Instead of sending every request through a single general-purpose model, the application uses an **application-level Mixture-of-Experts (MoE)-inspired design**: specialized AI providers are selected for different tasks, with routing and fallback paths that account for capability, availability, and free-tier constraints. This describes **system-level model orchestration**, not a claim that the underlying models implement a single neural-network MoE.

- **Specialized AI workflows:** Groq-backed conversational assistance, Mistral-based image analysis, and Cloudflare Workers AI for report generation and supporting AI workflows. Provider routing and fallbacks are designed to maintain service when a preferred endpoint is unavailable; optional OpenRouter backup is part of the WhatsApp architecture.
- **Multimodal experience:** text chat, voice input, camera/image uploads, read-aloud responses, structured reports, and multilingual interaction in **English, Kiswahili, Dutch, French, and Spanish**.
- **Application engineering:** separate conversation histories, configurable response modes, interruption controls, image-upload flows, provider error handling, and a responsive PWA interface.
- **Cross-channel expansion:** WhatsApp chat and image-assisted workflows are **in development**, with Cloudflare Workers AI as a planned primary provider for that channel and human-readable follow-up flows.

**Public beta; a health-information tool, not a medical diagnostic service.** The earlier **AI Health Assistant won first place** at the PLP Class of 2024 graduate hackathon.

[Live application](https://aihealthchat.qzz.io/) · [Architecture & case study](https://rayklanderman.is-a.dev/projects/ai-health-chat)

### [Luminae](https://github.com/RealDevRay/luminae) · Multi-agent research analysis

`Python` `FastAPI` `Next.js` `Mistral OCR` `Multi-agent orchestration` `Redis`

Built a **five-agent research analysis and critique platform** that turns uploaded documents into structured, reviewable research outputs. Its pipeline combines document extraction and figure interpretation with specialist agents rather than treating an entire research paper as a single prompt.

- **Five specialized agents:** Methodology Critic, Dataset Auditor, Experiment Designer, Synthesis Agent, and Grant Generator assess research methods, surface limitations, suggest follow-up work, and create structured outlines.
- **Engineering architecture:** Mistral OCR and vision-enabled document interpretation feed a **FastAPI/Python** backend; independent analysis stages run concurrently with `asyncio.gather`, while downstream agents build on earlier results.
- **Operational controls:** schema-guided structured output, Redis/Upstash-backed caching and budget safeguards, preflight cost estimation, and usage visibility in a **Next.js** dashboard.

Designed as a **research decision-support tool** for the Mistral Worldwide Hackathon, not a replacement for peer review or independent source verification.

[Source code](https://github.com/RealDevRay/luminae) · [Live application](https://luminae.qzz.io/) · [Demo](https://youtu.be/ODygWunOA6Y)

### [EyeSense](https://github.com/RealDevRay/eyesense) · Accessible AI visual assistance

`Flutter` `Dart` `Computer vision` `OCR` `Speech interaction` `Accessibility`

Developed a **Flutter-based Android prototype for blind and low-vision users** focused on a simple interaction: trigger the camera, capture the immediate surroundings, and hear a useful description. The project explores how multimodal AI can serve an accessibility need through a low-friction mobile interface.

- **Accessible interaction:** voice-oriented controls and a volume-button-triggered snapshot flow designed to reduce reliance on complex on-screen navigation.
- **Hybrid perception:** on-device/offline OCR for text-related tasks alongside consent-based cloud vision for scene description.
- **Practical mobile engineering:** camera integration, speech output, cloud API integration, and user-centered handling of sensitive visual input.

This is a **prototype**, not a substitute for a mobility aid or professional assistive service.

[Source code](https://github.com/RealDevRay/eyesense) · [Case study](https://rayklanderman.is-a.dev/projects/eyesense)

### [TutaLearn](https://tutalearn.qzz.io/) · AI-supported Kenyan learning platform

`Full-stack development` `AI tutoring` `Education` `Assessments` `Progress tracking`

Built **TutaLearn** around Kenya's **Competency-Based Curriculum (CBC)**, with learning support spanning **Grades 1–12**. It combines topic-based practice with AI assistance so learners can move between structured educational content and interactive explanations.

- **Learning workflows:** topic quizzes, assessments and exam-style practice, with progress tracking across learning activities.
- **AI assistance:** contextual explanations and tutoring to support practice and understanding rather than replacing the underlying learning material.
- **Product engineering:** learner-facing flows, curriculum organization, and access models designed around practical affordability and usability.

[Live application](https://tutalearn.qzz.io/) · [Case study](https://rayklanderman.is-a.dev/projects/tutalearn)

### [AutoResearcher](https://github.com/rayklanderman/CapstoneProject-Autoresearcher) · Seven-agent research and report pipeline

`Python` `Vertex AI ADK` `Gemini` `Tavily` `Matplotlib` `LaTeX`

Developed a **seven-agent research pipeline** using Google's **Agent Development Kit (ADK)** and Gemini models to coordinate source gathering, verification, chart creation, structured writing, and document compilation.

- **Role-based orchestration:** a Supervisor coordinates Researcher, FactChecker, Visualizer, Writer, Formatter, and Compiler stages, with shared workflow state.
- **Tool-enabled research:** Tavily supplies source retrieval, Python/Matplotlib generates visualizations, and Pandoc/LaTeX assembles a formatted report.
- **End-to-end deliverable:** transforms a research prompt into a multi-section, citation-oriented PDF workflow; generated claims and citations still require human verification.

[Source code](https://github.com/rayklanderman/CapstoneProject-Autoresearcher) · [Video demo](https://www.youtube.com/watch?v=s5Sktg34uC0)

**Other projects:** [PostShifter Pro](https://postshifterpro.qzz.io/) · [Live Interviewer](https://liveinterviewer.vercel.app/) · [Kazi Connect](https://kazi-connect.vercel.app/) · [SerenityAI](https://serenityai.qzz.io/) · [Codebase Genius](https://github.com/rayklanderman/jaseci-proj) · [Weru Digital](https://github.com/rayklanderman/weru_digital)

Some products have private source code; where available, I share live applications, demonstrations, and technical case studies.

## Selected machine learning & research

### [Profit-Targeted Churn Retention](https://github.com/rayklanderman/profit-targeted-churn-retention)

`Python` `pandas` `LightGBM` `XGBoost` `scikit-learn` `Decision analytics`

Built a churn-prediction and profit-based targeting workflow using **100,000 telecom customer records** and **113 engineered features** derived from 98 source fields. The selected model achieved **0.698 holdout ROC-AUC** on 20,000 records, against a **0.678 baseline**. A value-aware strategy projected **$49,526 monthly net profit per 100,000 customers** and **74% campaign ROI** under explicit assumptions—**not realized returns**. The analysis includes sensitivity testing and a proposed randomized pilot.

[Code & analysis](https://github.com/rayklanderman/profit-targeted-churn-retention) · [Technical article](https://www.linkedin.com/pulse/from-churn-prediction-profit-building-machine-100000-klanderman-irche/)

### [Movie Recommendation Project](https://github.com/rayklanderman/mrp-2026)

`Python` `SVD` `LightGBM` `Recommender systems`

Developed a hybrid recommendation pipeline over approximately **10 million ratings**, combining collaborative filtering and gradient boosting. Improved **public-leaderboard RMSE from 1.21 to 0.82** through feature engineering and experimentation—a **competition result, not a production metric**.

[Code](https://github.com/rayklanderman/mrp-2026) · [Case study](https://rayklanderman.is-a.dev/projects/movie-recommendation)

### [Probability for AI — Stanford portfolio](https://pai.stanford.edu/pai1/portfolio/vkT4Pq7wygeZK6dn3nSriEKgOXG3)

`Probability` `Statistical inference` `Transformers` `Model interpretability`

Completed **six hands-on portfolio projects** within the ongoing Probability for AI programme, spanning Bayesian reasoning, image classification, generative sampling, and inference. In a **GPT-2 knowledge-editing exercise**, modified **1,536 of ~124.4M parameters**, shifting a target completion to **~99% probability** and passing **4/4 reported held-out checks**. These are exercise results, not a general reliability claim.

[Stanford portfolio](https://pai.stanford.edu/pai1/portfolio/vkT4Pq7wygeZK6dn3nSriEKgOXG3) · [Rewrite GPT-2](https://pai.stanford.edu/pai1/portfolio/vkT4Pq7wygeZK6dn3nSriEKgOXG3/rewrite-gpt2)

## Automation & infrastructure

**Self-hosted n8n — DevRay automation environment**

I maintain a **self-hosted n8n environment** for workflow automation and service integrations. It is an operational environment, **not a public demo**; production configuration and credentials are not shared.

My engineering work also includes APIs, cloud/serverless services, databases, Git-based workflows, CI/CD, and application security.

## Technical stack

**Software & application development**

![Python](https://img.shields.io/badge/Python-25364A?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-25364A?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-25364A?style=flat-square&logo=javascript&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-25364A?style=flat-square&logo=flutter&logoColor=white)
![React](https://img.shields.io/badge/React-25364A?style=flat-square&logo=react&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-25364A?style=flat-square&logo=nextdotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-25364A?style=flat-square&logo=fastapi&logoColor=white)

**Machine learning & AI systems**

![scikit-learn](https://img.shields.io/badge/scikit--learn-25364A?style=flat-square&logo=scikitlearn&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-25364A?style=flat-square)
![XGBoost](https://img.shields.io/badge/XGBoost-25364A?style=flat-square)
![OpenAI](https://img.shields.io/badge/OpenAI-25364A?style=flat-square&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-25364A?style=flat-square&logo=googlegemini&logoColor=white)
![Mistral](https://img.shields.io/badge/Mistral-25364A?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-25364A?style=flat-square)

**Cloud, automation & delivery**

![Google Cloud](https://img.shields.io/badge/Google_Cloud-25364A?style=flat-square&logo=googlecloud&logoColor=white)
![Oracle Cloud](https://img.shields.io/badge/Oracle_Cloud-25364A?style=flat-square&logo=oracle&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-Self--hosted-25364A?style=flat-square&logo=n8n&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-25364A?style=flat-square&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-25364A?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-25364A?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-25364A?style=flat-square&logo=githubactions&logoColor=white)

- **Languages & frameworks:** Python, TypeScript, JavaScript, Dart, SQL; React, Next.js, Node.js/Express, FastAPI, Flutter, REST APIs.
- **ML & analytics:** pandas, NumPy, SciPy, scikit-learn, LightGBM, XGBoost, SVD, Jupyter, feature engineering, model evaluation, Power BI, Tableau.
- **AI engineering:** MCP, LLM APIs, multimodal inference, **MoE-inspired task-aware model routing and provider fallbacks**, OCR, retrieval-augmented generation, agent orchestration, structured outputs, evaluation; OpenAI, Gemini, Mistral, Groq, and xAI integrations.
- **Cloud & operations:** Google Cloud / Vertex AI, Oracle Cloud, Cloudflare Workers, n8n, Supabase, PostgreSQL, MySQL, Firebase, Redis, Docker, CI/CD, testing, API security, row-level security, and accessibility-aware design.

## Professional background & continued learning

I build and deliver software independently, combining engineering with experience working alongside institutional teams and stakeholders. During a **2025 contract with the Pan-African Parliament**, I designed and developed a **Flutter/Dart application for Android and iOS** integrating parliamentary information and event livestreaming, alongside media and digital-content work. My broader experience includes **digital media strategy and technical delivery for the Office of the Nairobi Woman Representative**, with cross-functional coordination, public-facing communication, and real-world operational requirements informing how I build software.

- **BSc Computer Science**, University of the People — in progress.
- **Diploma in ICT**, Management University of Africa — Distinction.
- **Stanford Probability for AI** and **GCI World 2026** — learning programmes with completed project work.
- Additional technical development through **ALX**, **WorldQuant University**, and **Power Learn Project**.

**Selected certifications:** Google Cloud Professional Cloud Architect · Oracle Cloud Infrastructure AI Foundations Associate · Linux Foundation KCNA · BCS Foundation Certificate in Generative AI. [Credentials](https://rayklanderman.is-a.dev/#credentials)

---

**Two GitHub accounts, one body of work:** [@rayklanderman](https://github.com/rayklanderman) is my primary professional profile; [@RealDevRay](https://github.com/RealDevRay) hosts additional projects including EyeSense, Luminae, and Sauti Mtaani Nairobi.

**More:** [Portfolio](https://rayklanderman.is-a.dev/) · [LinkedIn](https://www.linkedin.com/in/rayklanderman/) · [Project demos](https://www.youtube.com/playlist?list=PLJa0i7fpyLmA) · [Technical writing](https://medium.com/@raymondklanderman) · [Email](mailto:info@devray.qzz.io)

