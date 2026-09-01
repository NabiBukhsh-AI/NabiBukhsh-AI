<h1 align="center">Nabi Bukhsh</h1>

<p align="center">
  <strong>Senior AI Engineer</strong> · Karachi, Pakistan 🇵🇰<br>
  The model does the judgement. The arithmetic is deterministic. Every number has a source.
</p>

<p align="center">
  <a href="https://github.com/NabiBukhsh-AI">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&duration=3500&pause=900&color=22D3EE&center=true&vCenter=true&width=640&lines=Production+LLM+systems+you+can+audit;Fine-Tuning+%E2%80%A2+Agentic+RAG+%E2%80%A2+Evals;Deterministic+cores.+Cited+outputs." alt="Production LLM systems you can audit: fine-tuning, agentic RAG, evals" />
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/nabibukhshjawed/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:nabibuksh.baloch01@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/NabiBukhsh-AI?tab=repositories"><img src="https://img.shields.io/badge/All%20Repositories-181717?style=for-the-badge&logo=github&logoColor=white" alt="All repositories" /></a>
</p>

---

### 🧠 About

Five years across full-stack engineering and AI, the last stretch spent entirely on production LLM systems: fine-tuning, retrieval, agent orchestration, and the evaluation harnesses that keep all three honest.

There is one idea running through most of what I build. A language model is very good at reading, extracting and judging, and it is the wrong tool for anything that has to be exactly right every time. So I put the model where judgement belongs, keep the arithmetic in deterministic and unit-tested code, and make every output traceable to the document or URL it came from. Systems built that way can be audited, reproduced, and defended in a room full of people who do not trust AI.

- 🔭 At **Tracker AI**, I own the LLM stack end to end for a clinical decision-support product: supervised fine-tuning, retrieval architecture, evaluation, inference cost, and deployment.
- 🧩 Designing **behavioral evaluation frameworks**: regression suites, response consistency checks, and reasoning-quality scoring that run in CI rather than in someone's head.
- 🎙️ Deep background in **voice-first AI** (streaming ASR, real-time TTS, interruption handling) and high-accuracy **document OCR** with structured extraction.
- 👥 Have led and mentored engineering teams of 6+.
- 📈 *On the side:* systematic trading research in FX and metals, because backtesting is just evals with a P&L attached.

---

### 🚀 Selected Work

#### [plansight](https://github.com/NabiBukhsh-AI/plansight) · construction document intelligence
Point it at a permit set or an RFI package and get back validated building quantities, cited answers, and a grounded scope of work. A drawing set is not one kind of document, so ingestion is not one kind of pipeline. Quantity questions are treated as extraction rather than retrieval, and search is hybrid because construction queries are full of exact tokens that embeddings blur.

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Hybrid%20Search-22D3EE?style=flat-square&logoColor=black" />
  <img src="https://img.shields.io/badge/PDF%20Extraction-4B0082?style=flat-square&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/MIT-green?style=flat-square" />
</p>

#### [valuation-engine](https://github.com/NabiBukhsh-AI/valuation-engine) · private company valuation from filings
Upload an income statement and a balance sheet, name the industry, get a valuation across price/earnings, EV/EBITDA with an EBIT fallback, and price/sales, each showing the benchmark it used and the reliability checks it passed or failed. The model transcribes statements into structured line items and performs no arithmetic, so the same inputs always produce the same valuation and every figure traces to a formula.

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Financial%20Modelling-22D3EE?style=flat-square&logoColor=black" />
  <img src="https://img.shields.io/badge/Document%20Extraction-4B0082?style=flat-square&logoColor=white" />
</p>

#### [conversational-rag-engine](https://github.com/NabiBukhsh-AI/conversational-rag-engine) · one codebase, any number of bots
Each bot is a YAML profile naming a vector index and a persona. No forking, no per-client branches, no duplicated prompt strings. Pluggable Pinecone, Qdrant and Chroma backends, cost and latency accounting, and an evaluation suite that can gate CI on retrieval quality.

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/Pinecone-000000?style=flat-square&logo=pinecone&logoColor=white" />
  <img src="https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white" />
  <img src="https://img.shields.io/badge/Chroma-FF6B35?style=flat-square&logoColor=white" />
  <img src="https://img.shields.io/badge/MIT-green?style=flat-square" />
</p>

#### [Holdfast](https://github.com/NabiBukhsh-AI/Holdfast) · constraint integrity under context compaction
Compactors preserve the task and quietly drop the constraints. COMPINT is the offline suite that measures that loss across long-context environments and compactor configurations. SC-GUARD is the fix: a session-scoped constraint registry kept outside the compression path and re-injected at every compaction event, hardened into a deployable sidecar.

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Evaluation-22D3EE?style=flat-square&logoColor=black" />
  <img src="https://img.shields.io/badge/AI%20Safety-22D3EE?style=flat-square&logoColor=black" />
  <img src="https://img.shields.io/badge/Reproducible%20Research-4B0082?style=flat-square&logoColor=white" />
  <img src="https://img.shields.io/badge/MIT-green?style=flat-square" />
</p>

#### [passive-skill-distillation](https://github.com/NabiBukhsh-AI/passive-skill-distillation) · paper to production
Turns agent trajectory logs into validated, versioned natural-language skills appended to a non-reasoning model's system prompt. No gradient step exists anywhere in the critical path, which is what makes it cheap enough to run continuously and which relocates the risk to prompt supply-chain security. Implements arXiv:2608.07885.

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Agents-22D3EE?style=flat-square&logoColor=black" />
  <img src="https://img.shields.io/badge/Prompt%20Security-FF6B35?style=flat-square&logoColor=white" />
  <img src="https://img.shields.io/badge/Reproducible%20Research-4B0082?style=flat-square&logoColor=white" />
</p>

**Also here:** [market-sizing-engine](https://github.com/NabiBukhsh-AI/market-sizing-engine) (cited TAM/SAM/SOM with deterministic arithmetic) · [hardpoint](https://github.com/NabiBukhsh-AI/hardpoint) (the contracts and ingestion layer above, extracted into a library, pre-alpha) · [VideoGenerator](https://github.com/NabiBukhsh-AI/VideoGenerator) (text to narrated short-form video, offline mode needs no API keys) · [mini-project-board](https://github.com/NabiBukhsh-AI/mini-project-board) (full-stack Kanban, Node and React)

<sub>Work that is not public: the LLM stack at Tracker AI, an AI intake platform for U.S. immigration practitioners (multilingual voice intake, OCR, cross-form consistency checks), a retrieval-backed project charter auditor, and a set of MQL5 trading systems with a prop-firm compliance engine. Happy to talk through any of it.</sub>

---

### ⚙️ Tech Stack

**Generative AI & LLM Frameworks**

<p>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain" />
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langgraph&logoColor=22D3EE" alt="LangGraph" />
  <img src="https://img.shields.io/badge/LangSmith-1C3C3C?style=for-the-badge&logoColor=white" alt="LangSmith" />
  <img src="https://img.shields.io/badge/LlamaIndex-4B0082?style=for-the-badge&logoColor=white" alt="LlamaIndex" />
  <img src="https://img.shields.io/badge/CrewAI-FF6B35?style=for-the-badge&logoColor=white" alt="CrewAI" />
  <img src="https://img.shields.io/badge/Haystack-03AF9D?style=for-the-badge&logoColor=white" alt="Haystack" />
  <img src="https://img.shields.io/badge/Pydantic%20AI-E92063?style=for-the-badge&logo=pydantic&logoColor=white" alt="Pydantic AI" />
  <img src="https://img.shields.io/badge/MCP-22D3EE?style=for-the-badge&logoColor=black" alt="MCP" />
</p>

**Providers**

<p>
  <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" alt="OpenAI" />
  <img src="https://img.shields.io/badge/Anthropic-D4A27F?style=for-the-badge&logoColor=white" alt="Anthropic" />
  <img src="https://img.shields.io/badge/Google%20AI-8E75B2?style=for-the-badge&logo=google&logoColor=white" alt="Google AI" />
  <img src="https://img.shields.io/badge/Meta%20AI-0866FF?style=for-the-badge&logo=meta&logoColor=white" alt="Meta AI" />
  <img src="https://img.shields.io/badge/Mistral%20AI-FA520F?style=for-the-badge&logoColor=white" alt="Mistral AI" />
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face" />
  <img src="https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logoColor=white" alt="Groq" />
  <img src="https://img.shields.io/badge/OpenRouter-6566F1?style=for-the-badge&logoColor=white" alt="OpenRouter" />
</p>

**Fine-Tuning & Training**

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow" />
  <img src="https://img.shields.io/badge/Transformers-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Transformers" />
  <img src="https://img.shields.io/badge/Unsloth-00B894?style=for-the-badge&logoColor=white" alt="Unsloth" />
  <img src="https://img.shields.io/badge/PEFT%20%2F%20LoRA-7B61FF?style=for-the-badge&logoColor=white" alt="PEFT and LoRA" />
  <img src="https://img.shields.io/badge/TRL-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="TRL" />
</p>

**Inference & Local LLMs**

<p>
  <img src="https://img.shields.io/badge/vLLM-30A14E?style=for-the-badge&logoColor=white" alt="vLLM" />
  <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white" alt="Ollama" />
  <img src="https://img.shields.io/badge/llama.cpp-000000?style=for-the-badge&logoColor=white" alt="llama.cpp" />
  <img src="https://img.shields.io/badge/Modal-7B61FF?style=for-the-badge&logoColor=white" alt="Modal" />
</p>

**Specializations**

<p>
  <img src="https://img.shields.io/badge/RAG-0D1117?style=for-the-badge&labelColor=22D3EE&color=0D1117" alt="RAG" />
  <img src="https://img.shields.io/badge/Agentic%20RAG-0D1117?style=for-the-badge&labelColor=22D3EE&color=0D1117" alt="Agentic RAG" />
  <img src="https://img.shields.io/badge/Supervised%20Fine--Tuning-0D1117?style=for-the-badge&labelColor=22D3EE&color=0D1117" alt="Supervised fine-tuning" />
  <img src="https://img.shields.io/badge/Multi--Agent%20Systems-0D1117?style=for-the-badge&labelColor=22D3EE&color=0D1117" alt="Multi-agent systems" />
  <img src="https://img.shields.io/badge/Function%20Calling-0D1117?style=for-the-badge&labelColor=22D3EE&color=0D1117" alt="Function calling" />
  <img src="https://img.shields.io/badge/Evals%20%26%20Observability-0D1117?style=for-the-badge&labelColor=22D3EE&color=0D1117" alt="Evals and observability" />
  <img src="https://img.shields.io/badge/Deterministic%20Cores-0D1117?style=for-the-badge&labelColor=22D3EE&color=0D1117" alt="Deterministic cores" />
</p>

**Voice & Multimodal**

<p>
  <img src="https://img.shields.io/badge/Deepgram-13EF93?style=for-the-badge&logoColor=black" alt="Deepgram" />
  <img src="https://img.shields.io/badge/ElevenLabs-000000?style=for-the-badge&logoColor=white" alt="ElevenLabs" />
  <img src="https://img.shields.io/badge/Streaming%20ASR-0D1117?style=for-the-badge&labelColor=22D3EE&color=0D1117" alt="Streaming ASR" />
  <img src="https://img.shields.io/badge/Document%20OCR-0D1117?style=for-the-badge&labelColor=22D3EE&color=0D1117" alt="Document OCR" />
  <img src="https://img.shields.io/badge/FFmpeg-007808?style=for-the-badge&logo=ffmpeg&logoColor=white" alt="FFmpeg" />
</p>

**Backend & APIs**

<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" alt="Flask" />
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" alt="Django" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express.js" />
</p>

**Databases & Vectors**

<p>
  <img src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase" />
  <img src="https://img.shields.io/badge/Pinecone-000000?style=for-the-badge&logo=pinecone&logoColor=white" alt="Pinecone" />
  <img src="https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge&logo=qdrant&logoColor=white" alt="Qdrant" />
  <img src="https://img.shields.io/badge/Chroma-FF6B35?style=for-the-badge&logoColor=white" alt="Chroma" />
  <img src="https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logoColor=white" alt="FAISS" />
</p>

**Cloud & DevOps**

<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" alt="Google Cloud" />
  <img src="https://img.shields.io/badge/DigitalOcean-0080FF?style=for-the-badge&logo=digitalocean&logoColor=white" alt="DigitalOcean" />
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions" />
</p>

<details>
<summary><b>More tools</b> (frontend, mobile, security, networking)</summary>
<br>

<p>
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter" />
  <img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" alt="Dart" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React" />
</p>

<p>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/Nmap-214478?style=for-the-badge&logoColor=white" alt="Nmap" />
  <img src="https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white" alt="Wireshark" />
  <img src="https://img.shields.io/badge/Kali%20Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white" alt="Kali Linux" />
</p>

</details>

---

### 📊 GitHub Stats

<p align="center">
  <img height="170" src="https://github-readme-stats-blond-two-56.vercel.app/api?username=NabiBukhsh-AI&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=22D3EE&icon_color=22D3EE&text_color=C9D1D9&include_all_commits=true&count_private=true" alt="GitHub stats for NabiBukhsh-AI" />
  <img height="170" src="https://streak-stats.demolab.com/?user=NabiBukhsh-AI&theme=tokyonight&hide_border=true&background=0D1117&stroke=22D3EE&ring=22D3EE&fire=22D3EE&currStreakLabel=22D3EE" alt="Contribution streak for NabiBukhsh-AI" />
</p>

<p align="center">
  <img src="https://github-readme-stats-blond-two-56.vercel.app/api/top-langs/?username=NabiBukhsh-AI&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=22D3EE&text_color=C9D1D9&langs_count=8&exclude_repo=github-readme-stats,iloveAgents,fidy-ai" alt="Most used languages" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=NabiBukhsh-AI&theme=tokyo-night&hide_border=true&bg_color=0D1117&color=22D3EE&line=22D3EE&point=FFFFFF&area=true&area_color=22D3EE" alt="Contribution activity graph" />
</p>

---

### 🌐 Open To

Senior AI Engineer and LLM engineering roles, remote or on-site.

<p align="center">
  <a href="https://www.linkedin.com/in/nabibukhshjawed/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://github.com/NabiBukhsh-AI"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="mailto:nabibuksh.baloch01@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

<p align="center">
  <em>"The model is one component. The system is the product."</em>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=22D3EE&height=80&section=footer&reversal=true" alt="" />
</p>
