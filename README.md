<div align="center">

<img src="./assets/header.svg" alt="Vaibhav Arya — AI/ML Engineer" width="100%"/>

<img src="./assets/typing.svg" alt="Building LLM products used by 100K+ learners · Fine-tuning open-weight models on multi-GPU clusters · Shipping RAG, agents & voice AI to production · Self-hosting inference with vLLM at 150 tok/s" width="720"/>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-vaibhav--arya-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/vaibhav-arya717853202)
[![Gmail](https://img.shields.io/badge/Gmail-aryav210%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:aryav210@gmail.com)
[![Live Demo](https://img.shields.io/badge/Live_Demo-interview.codevik.xyz-14B8A6?style=for-the-badge&logo=googlechrome&logoColor=white)](https://interview.codevik.xyz)

<img src="https://komarev.com/ghpvc/?username=VaibhavNikkuV&style=for-the-badge&color=14b8a6&label=PROFILE+VIEWS" alt="Profile views"/>

</div>

<br/>

## 👨‍💻 About Me

<img align="right" src="./assets/about.svg" width="330" alt="Neural network and GPU cluster illustration"/>

```python
class VaibhavArya:
    role      = "AI/ML Engineer"
    focus     = ["Generative AI", "LLM Fine-Tuning", "RAG", "Agentic Systems"]
    company   = "Leading UPSC EdTech platform · New Delhi"
    education = "B.Tech AI · Galgotias College of Engineering & Technology"

    builds    = ["RAG course assistants", "Voice-native multi-agent interviewers",
                 "Self-hosted LLM serving on multi-GPU clusters"]
    cares     = ["Latency & cost per token", "Eval-driven quality",
                 "Owning the stack end-to-end"]
    location  = "New Delhi, India 🇮🇳"
```

- 🤖 **LLM Applications** — production RAG (hybrid BM25 + semantic), LangGraph / LangChain agents, MCP servers, tool calling, structured outputs
- 🧬 **Fine-Tuning** — QLoRA / LoRA with Unsloth, Axolotl & HF TRL; PyTorch DDP across **4× NVIDIA RTX A5000**
- ⚡ **Inference & Serving** — vLLM + GPUStack, quantization, KV caching, streaming, chunked map-reduce over 100K-token inputs
- 🎙️ **Voice AI** — LiveKit, Whisper STT, ElevenLabs TTS, sub-second STT → LLM → TTS loops
- 📈 **Track record** — promoted twice in 18 months (Intern → Analyst → Engineer); sole owner of the in-house LLM stack & GPU infra
- 🎓 Certified: **AWS** — Planning a Generative AI Project · Building a Generative AI-Ready Organisation · Introduction to Generative AI

<br clear="right"/>

---

## 📊 Impact at a Glance

<img src="./assets/impact.svg" alt="100K+ learners · 2,000+ candidates · ~4× training speedup · 150 tok/s · 70% cost reduction · <10 min evaluation" width="100%"/>

---

## 💼 Experience

<table>
<tr>
<td width="50%" valign="top">

### 🚀 AI-ML Engineer
**Leading UPSC EdTech Platform** · Apr 2026 – Present

- Scaled training across **4× RTX A5000** with PyTorch DDP + torchrun; tuned NCCL, batch size & grad accumulation for **~4× faster** training with crash-safe checkpointing
- Built an LLM **question-upload pipeline** (images, tables, complex formatting) that replaced a manual uploader workflow — **5 hours → 15 minutes** per batch incl. human review
- **Long-context inference:** chunked map-reduce summarization of 100K-token transcripts beyond single-GPU memory, with token-budgeted prompting & streaming
- Refactored legacy AI pipelines to cut failure rates; workflow automations running at up to **95% accuracy**

</td>
<td width="50%" valign="top">

### 🧠 AI & Automation Analyst
**Leading UPSC EdTech Platform** · Jun 2025 – Mar 2026

- Shipped the **RAG course assistant** end-to-end for **100K+ users** — timestamped video retrieval (PostgreSQL + Weaviate), hybrid search, RAG quizzes, web-search fallback
- Built a **6-agent voice interview simulator** (LiveKit, WebSockets, Perplexity + RAG tools) — **2,000+ candidates**, sub-second latency, **70% lower cost**
- **Automated Mains answer evaluation** (Gemini + Perplexity Search) for handwritten sheets — hours → **<10 min**, 70% cheaper
- **20-step agentic content pipeline:** S3 audio → transcription → generation → DB-sync → deploy, zero manual steps
- Self-hosted Whisper large-v3 & gpt-oss on **vLLM + GPUStack** at up to **150 tok/s**
- LangSmith tracing + custom evals: **~20% fewer hallucinations**, **~25% better** response quality

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### 🌱 Generative AI Intern
**Leading UPSC EdTech Platform** · Feb 2025 – May 2025

- Built custom **MCP tool servers** (FastAPI, WebSocket) giving LLMs real-time access to internal data & tools &nbsp;·&nbsp; Co-built the first **timestamp-aware video Q&A chatbot** with guardrails and LangSmith monitoring — the foundation for the 100K-user assistant &nbsp;·&nbsp; **Whisper STT + custom-scoring** pipeline to transcribe and grade daily sales/support calls &nbsp;·&nbsp; Enterprise **RAG tuning** (embedding, chunking, hybrid-search experiments) and automation with n8n & Dify

</td>
</tr>
</table>

---

## 🛠️ Featured Systems

<table>
<tr>
<td width="50%" valign="top">

### 🎙️ Voice-Native UPSC Interview Simulator
`LiveKit` `WebSockets` `Perplexity API` `RAG` `Multi-provider LLM routing`

- 6 cooperating agents with distinct personas & dynamic prompting
- Tool access to live web search + RAG; streaming STT → LLM → TTS loop
- Prototyped on Vapi and LiveKit, then taken to production

**⚡ Sub-second latency · 70% lower cost/session · 2,000+ candidates**

</td>
<td width="50%" valign="top">

### 🧬 Multi-GPU LLM Fine-Tuning Platform
`Unsloth` `QLoRA` `Axolotl` `PyTorch DDP` `HF TRL` `vLLM` `4× RTX A5000`

- Replaced slow, costly third-party APIs for 100K-token bilingual lecture summaries
- Owned dataset curation → QLoRA fine-tune of Gemma-4 E2B → DDP scaling → OOM debugging → checkpointing
- vLLM serving with chunked map-reduce inference

**⚡ ~4× faster training · structured HTML summaries at 8K ctx · zero per-token API spend**

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 💬 Production RAG Course Assistant
`FastAPI` `PostgreSQL` `Weaviate` `BM25 + Semantic` `LangSmith`

- Timestamped video retrieval over chunked transcripts
- RAG-generated UPSC quizzes + web-search fallback for current affairs
- LLM tracing & evaluation with LangSmith and custom checks

**⚡ 100K+ users · ~20% fewer hallucinations · ~25% better response quality**

</td>
<td width="50%" valign="top">

### 🖥️ Self-Hosted LLM Serving Platform
`vLLM` `GPUStack` `Docker` `Nginx` `RTX A5000`

- Whisper large-v3 (faster-whisper), gpt-oss and other open-weight models
- Quantization, KV caching and streaming generation
- A private, low-cost inference endpoint for every internal AI workflow

**⚡ Up to 150 tok/s · Dockerized services scaled for enterprise load**

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### 🎯 Practice Mock Interviews — AI Voice Interviewer &nbsp;·&nbsp; [🔗 Live Demo](https://interview.codevik.xyz) &nbsp;<sub>personal project</sub>
`LiveKit` `FastAPI` `Next.js 15` `OpenAI` `Gemini` `Groq Whisper` `Docker Compose` `LaTeX`

- An AI interviewer reads the candidate's parsed resume and target JD, then runs a live, low-latency STT → LLM → TTS interview
- 4-stage **"Full Prep"** pipeline (parse → JD skill analysis → LaTeX resume build → Q&A generation) auto-produces a role-optimized resume PDF and ~10 Q&As per project
- Async FastAPI with semaphore-bounded concurrency, per-session work dirs, LiveKit room/token dispatch, server-side Next.js upload proxying, pluggable STT & resume-parsing providers, one-command Docker Compose deploy with TeX Live baked in

</td>
</tr>
</table>

---

## 🧰 Tech Stack

<details open>
<summary><b>🤖 AI & LLM Engineering</b></summary>
<br/>

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langgraph&logoColor=white)
![LlamaIndex](https://img.shields.io/badge/LlamaIndex-0E7490?style=for-the-badge)
![RAG](https://img.shields.io/badge/RAG_%C2%B7_Hybrid_Search_%C2%B7_Reranking-14B8A6?style=for-the-badge)
![MCP](https://img.shields.io/badge/MCP_Servers-0B1120?style=for-the-badge&logo=modelcontextprotocol&logoColor=white)
![Agents](https://img.shields.io/badge/Multi--Agent_Orchestration-0E7490?style=for-the-badge)
![Prompting](https://img.shields.io/badge/Prompt_Engineering-0EA5E9?style=for-the-badge&logo=openai&logoColor=white)
![Structured](https://img.shields.io/badge/Structured_Outputs_%C2%B7_Tool_Calling-0B1120?style=for-the-badge&logo=json&logoColor=white)

</details>

<details open>
<summary><b>🧬 Training & Fine-Tuning</b></summary>
<br/>

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![HF](https://img.shields.io/badge/Hugging_Face_TRL_%C2%B7_Transformers-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![PEFT](https://img.shields.io/badge/QLoRA_%C2%B7_LoRA_%C2%B7_PEFT-14B8A6?style=for-the-badge)
![Unsloth](https://img.shields.io/badge/Unsloth-0E7490?style=for-the-badge)
![Axolotl](https://img.shields.io/badge/Axolotl-0B1120?style=for-the-badge)
![DDP](https://img.shields.io/badge/PyTorch_DDP_%C2%B7_torchrun_%C2%B7_NCCL-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![Precision](https://img.shields.io/badge/Mixed_Precision_%C2%B7_Grad_Accumulation_%C2%B7_Loss_Masking-0EA5E9?style=for-the-badge)

</details>

<details open>
<summary><b>⚡ Inference & Serving</b></summary>
<br/>

![vLLM](https://img.shields.io/badge/vLLM-0B1120?style=for-the-badge)
![GPUStack](https://img.shields.io/badge/GPUStack-0E7490?style=for-the-badge)
![Quant](https://img.shields.io/badge/4%2F8--bit_Quantization-14B8A6?style=for-the-badge)
![KV](https://img.shields.io/badge/KV_Caching_%C2%B7_Flash_Attention-0EA5E9?style=for-the-badge)
![Streaming](https://img.shields.io/badge/Streaming_%C2%B7_Chunked_Map--Reduce-0B1120?style=for-the-badge)
![NVIDIA](https://img.shields.io/badge/NVIDIA_RTX_A5000_Cluster-76B900?style=for-the-badge&logo=nvidia&logoColor=white)

</details>

<details open>
<summary><b>🧠 Models & APIs</b></summary>
<br/>

![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic-191919?style=for-the-badge&logo=anthropic&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge)
![Perplexity](https://img.shields.io/badge/Perplexity-1FB8CD?style=for-the-badge&logo=perplexity&logoColor=white)
![Gemma](https://img.shields.io/badge/Gemma-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Llama](https://img.shields.io/badge/Llama-0467DF?style=for-the-badge&logo=meta&logoColor=white)
![Mistral](https://img.shields.io/badge/Mistral-FA520F?style=for-the-badge&logo=mistralai&logoColor=white)
![DeepSeek](https://img.shields.io/badge/DeepSeek-4D6BFE?style=for-the-badge)
![gpt-oss](https://img.shields.io/badge/gpt--oss-0B1120?style=for-the-badge&logo=openai&logoColor=white)
![Whisper](https://img.shields.io/badge/Whisper-14B8A6?style=for-the-badge&logo=openai&logoColor=white)

</details>

<details open>
<summary><b>🗄️ Data & Vector Stores</b></summary>
<br/>

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Weaviate](https://img.shields.io/badge/Weaviate-14B8A6?style=for-the-badge)
![ChromaDB](https://img.shields.io/badge/ChromaDB-0E7490?style=for-the-badge)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logo=meta&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white)

</details>

<details open>
<summary><b>☁️ Infra & DevOps</b></summary>
<br/>

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker_%C2%B7_Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS_EC2_%C2%B7_S3_%C2%B7_Lambda-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![DigitalOcean](https://img.shields.io/badge/DigitalOcean-0080FF?style=for-the-badge&logo=digitalocean&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI%2FCD-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</details>

<details>
<summary><b>🎙️ Voice, Automation & Observability</b></summary>
<br/>

![LiveKit](https://img.shields.io/badge/LiveKit-0B1120?style=for-the-badge)
![ElevenLabs](https://img.shields.io/badge/ElevenLabs_TTS-000000?style=for-the-badge&logo=elevenlabs&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-0E7490?style=for-the-badge)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![Dify](https://img.shields.io/badge/Dify-14B8A6?style=for-the-badge)
![LangSmith](https://img.shields.io/badge/LangSmith-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Evals](https://img.shields.io/badge/LLM--as--Judge_%C2%B7_Guardrails_%C2%B7_Cost_Tracking-0EA5E9?style=for-the-badge)

</details>

<details>
<summary><b>💻 Languages</b></summary>
<br/>

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)

</details>

---

## 📂 Featured Repositories

| Repository | About |
|---|---|
| [**MCP-samples**](https://github.com/VaibhavNikkuV/MCP-samples) | Sample Model Context Protocol servers and tool integrations for LLMs |
| [**Llama3RAGchatbot**](https://github.com/VaibhavNikkuV/Llama3RAGchatbot) | Retrieval-augmented chatbot built on Llama 3 |
| [**Resume_modifier**](https://github.com/VaibhavNikkuV/Resume_modifier) | A tool for modifying and managing resumes |
| [**Natural-Language-Processing**](https://github.com/VaibhavNikkuV/Natural-Language-Processing) | NLP experiments and notebooks |
| [**Banglore_House_Prediction**](https://github.com/VaibhavNikkuV/Banglore_House_Prediction) | End-to-end ML regression project on Bengaluru housing data |
| [**Projects**](https://github.com/VaibhavNikkuV/Projects) | Collection of ML / DL project notebooks |

---

## 📊 GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=VaibhavNikkuV&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=14b8a6&icon_color=0ea5e9&text_color=c9d1d9&count_private=true&include_all_commits=true" height="165" alt="GitHub stats"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=VaibhavNikkuV&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=14b8a6&text_color=c9d1d9&langs_count=8" height="165" alt="Top languages"/>

<br/><br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=VaibhavNikkuV&theme=tokyonight&hide_border=true&background=0d1117&ring=14b8a6&fire=0ea5e9&currStreakLabel=14b8a6" alt="GitHub streak"/>

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=VaibhavNikkuV&theme=react-dark&hide_border=true&bg_color=0d1117&color=c9d1d9&line=14b8a6&point=22d3ee&area=true&area_color=14b8a6" width="100%" alt="Contribution graph"/>

<br/><br/>

<img src="https://github-profile-trophy.vercel.app/?username=VaibhavNikkuV&theme=algolia&no-frame=true&no-bg=true&margin-w=8&column=7" alt="GitHub trophies"/>

</div>

---

## 🎓 Education & Certifications

**B.Tech, Artificial Intelligence** — Galgotias College of Engineering & Technology, Greater Noida · 2021 – 2025

![AWS](https://img.shields.io/badge/AWS-Planning_a_Generative_AI_Project-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-Building_a_Generative_AI--Ready_Organisation-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-Introduction_to_Generative_AI-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)

---

## 🤝 Let's Connect

<div align="center">

<a href="https://linkedin.com/in/vaibhav-arya717853202"><img src="https://img.shields.io/badge/💼_LinkedIn-Connect-0A66C2?style=for-the-badge" alt="LinkedIn"/></a>
<a href="mailto:aryav210@gmail.com"><img src="https://img.shields.io/badge/📧_Email-Say_Hello-EA4335?style=for-the-badge" alt="Email"/></a>
<a href="https://interview.codevik.xyz"><img src="https://img.shields.io/badge/🎯_Live_Demo-Try_the_AI_Interviewer-14B8A6?style=for-the-badge" alt="Live Demo"/></a>

<br/><br/>

*Open to collaborations on LLM fine-tuning, RAG & agentic systems, and running open-weight models in production.*

<br/>

<img src="./assets/footer.svg" alt="" width="100%"/>

</div>
