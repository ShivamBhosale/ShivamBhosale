<!-- ============================== BANNER ============================== -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0A66C2,50:6C3CE9,100:E97627&height=220&section=header&text=Shivam%20Bhosale&fontSize=58&fontColor=ffffff&fontAlignY=38&desc=Data%20Analyst%20%C2%B7%20AI%20Engineer&descSize=22&descAlignY=60&animation=fadeIn" alt="Shivam Bhosale banner"/>
</p>

<p align="center">
  <a href="https://github.com/ShivamBhosale">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3200&pause=900&color=0A66C2&center=true&vCenter=true&width=720&lines=Turning+raw+data+into+decisions.;Turning+decisions+into+systems.;SQL+%7C+Python+%7C+Power+BI+%7C+LLM+agents.;Good+decisions+start+with+clean+data." alt="Typing animation"/>
  </a>
</p>

<p align="center">
  <a href="https://www.shivambhosale.me"><img src="https://img.shields.io/badge/Portfolio-shivambhosale.me-0A66C2?style=for-the-badge&logo=google-chrome&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/shivambhosale"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:shivambhosale909@gmail.com"><img src="https://img.shields.io/badge/Email-Say%20Hi-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>

<p align="center">
  📍 Toronto, Canada &nbsp;·&nbsp; 🟢 <b>Open to new opportunities</b> &nbsp;·&nbsp; 🏠 Hybrid / Remote
</p>

---

## 👋 The Brief

I build across the full analytics stack: **SQL and Python pipelines**, **Power BI dashboards**, **LLM agents**, **financial screeners**, and **locally run AI systems**.

Right now I'm a Data Analyst at **MJR Capital**, shipping ML models to production. Side hours go to agentic AI, reliability-first LLM pipelines, and a few too many side projects.



```mermaid
%%{init: {"theme":"dark","themeVariables":{"fontFamily":"monospace","edgeLabelBackground":"#161b22","lineColor":"#8b949e"}}}%%
flowchart LR
    ME(["🧑‍💻 SHIVAM BHOSALE<br/>raw data → decisions → systems"])

    subgraph DATA["📊 DATA AND ANALYTICS"]
        direction LR
        D1["SQL + Python ETL<br/>on AWS"] --> D2["Power BI + DAX<br/>dashboards"] --> D3["Automated reporting<br/>-40% time"]
    end

    subgraph ML["🧠 MACHINE LEARNING"]
        direction LR
        ML1["Scikit-learn<br/>classify, regress, anomaly"] --> ML2["🌾 Agri-Optima<br/>CNN, 95% accuracy"] --> ML3["Monitoring<br/>precision, recall, AUC, RMSE"]
    end

    subgraph AI["🤖 LLMS AND AGENTS"]
        direction LR
        A1["🦡 Honey Badger<br/>6-stage validation, local"] ~~~ A2["📄 Ask-Your-PDF<br/>RAG + FAISS"] ~~~ A3["🏦 Bloomberg Replica<br/>Claude daily brief"]
    end

    subgraph MKT["📈 FINANCIAL MARKETS"]
        direction LR
        F1["Stonks.ca<br/>TSX screener CLI"] ~~~ F2["P/E anomalies, volume spikes<br/>52-week breakouts"]
    end

    subgraph DEC["🧭 DECISION ENGINEERING"]
        direction LR
        DE1["Lodestar<br/>AHP + TOPSIS"] ~~~ DE2["Monte Carlo<br/>10k+ trials"]
    end

    subgraph SYS["🔐 LOCAL-FIRST SYSTEMS"]
        direction LR
        S1["🔥 Flint<br/>encrypted clipboard sync"] ~~~ S2["mDNS + QR pairing<br/>AES-256"] ~~~ S3["no cloud, no accounts<br/>no telemetry"]
    end

    subgraph LAI["🏠 LOCAL-FIRST AI"]
        direction LR
        L1["🇫🇷 FrenchFlow<br/>offline tutor, Mistral via Ollama"] ~~~ L2["✉️ EmailGenie<br/>strict JSON, validate + retry"]
    end

    ME --> D1
    ME --> ML1
    ME --> A1
    ME --> F1
    ME --> DE1
    ME --> S1
    ME --> L1

    ML1 -.->|"live KPIs"| D2
    A3 -.->|"Yahoo Finance data"| F1
    A1 -.->|"shared Ollama stack"| L1

    classDef hub fill:#6C3CE9,color:#fff,stroke:#fff,stroke-width:2px
    classDef data fill:#0A66C2,color:#fff,stroke:none
    classDef ml fill:#9B3FD1,color:#fff,stroke:none
    classDef ai fill:#D9534F,color:#fff,stroke:none
    classDef mkt fill:#2E9E5B,color:#fff,stroke:none
    classDef dec fill:#E97627,color:#fff,stroke:none
    classDef sys fill:#455A64,color:#fff,stroke:none
    classDef lai fill:#00897B,color:#fff,stroke:none

    class ME hub
    class D1,D2,D3 data
    class ML1,ML2,ML3 ml
    class A1,A2,A3 ai
    class F1,F2 mkt
    class DE1,DE2 dec
    class S1,S2,S3 sys
    class L1,L2 lai

    style DATA fill:#0d1117,stroke:#0A66C2,stroke-width:2px,color:#e6edf3
    style ML fill:#0d1117,stroke:#9B3FD1,stroke-width:2px,color:#e6edf3
    style AI fill:#0d1117,stroke:#D9534F,stroke-width:2px,color:#e6edf3
    style MKT fill:#0d1117,stroke:#2E9E5B,stroke-width:2px,color:#e6edf3
    style DEC fill:#0d1117,stroke:#E97627,stroke-width:2px,color:#e6edf3
    style SYS fill:#0d1117,stroke:#455A64,stroke-width:2px,color:#e6edf3
    style LAI fill:#0d1117,stroke:#00897B,stroke-width:2px,color:#e6edf3
```

<sub>Seven territories, one habit: ship the thing. Solid lines are workflows, dotted lines are where one lane feeds another.</sub>

---

## 🚀 Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🧭 <a href="https://github.com/ShivamBhosale">Lodestar</a></h3>
      <sub><b>DECISION ENGINEERING</b></sub><br/><br/>
      Stacks <b>AHP + TOPSIS + Monte Carlo</b> (10k+ simulations) to weight, rank, and stress-test life and work decisions. The data person's antidote to gut feel.<br/><br/>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
      <img src="https://img.shields.io/badge/AHP-6C3CE9?style=flat-square"/>
      <img src="https://img.shields.io/badge/TOPSIS-9B3FD1?style=flat-square"/>
      <img src="https://img.shields.io/badge/Monte%20Carlo-E97627?style=flat-square"/>
    </td>
    <td width="50%" valign="top">
      <h3>🔥 <a href="https://github.com/ShivamBhosale/flint">Flint</a></h3>
      <sub><b>CROSS-DEVICE CLIPBOARD</b></sub><br/><br/>
      Clipboard sync across <b>Mac, Android, and Chrome</b> over your local network. Devices find each other via mDNS and pair by QR. <b>AES-256 end-to-end encrypted. No cloud, no accounts, no telemetry.</b><br/><br/>
      <img src="https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white"/>
      <img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white"/>
      <img src="https://img.shields.io/badge/Chrome%20MV3-4285F4?style=flat-square&logo=googlechrome&logoColor=white"/>
      <img src="https://img.shields.io/badge/AES--GCM-232F3E?style=flat-square"/>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>📈 <a href="https://github.com/ShivamBhosale/Stonks.ca">Stonks.ca</a></h3>
      <sub><b>TSX STOCK SCREENER CLI</b></sub><br/><br/>
      Real-time scanner for Canadian equities and ETFs. Flags <b>P/E anomalies, volume spikes, 52-week breakouts</b>, and momentum, with plain-English signals and a CSV trade log. No API key needed.<br/><br/>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
      <img src="https://img.shields.io/badge/yfinance-7B1FA2?style=flat-square"/>
      <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white"/>
      <img src="https://img.shields.io/badge/Rich-000000?style=flat-square"/>
    </td>
    <td width="50%" valign="top">
      <h3>🦡 <a href="https://github.com/ShivamBhosale/Honey-Badger---AI-Assistant">Honey Badger AI</a></h3>
      <sub><b>RELIABILITY-FIRST GENAI</b></sub><br/><br/>
      Every response is <b>generated → critiqued → revised → rule-evaluated → confidence-scored → guardrailed</b> before you see it. Fully local via Ollama, no API key.<br/><br/>
      <img src="https://img.shields.io/badge/Ollama-000000?style=flat-square"/>
      <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white"/>
      <img src="https://img.shields.io/badge/LLM-6C3CE9?style=flat-square"/>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🏦 <a href="https://github.com/ShivamBhosale">Bloomberg Replica</a></h3>
      <sub><b>LLM MARKET INTEL</b></sub><br/><br/>
      Claude reads equities, FX, and macro from free APIs and writes an <b>institutional-style daily brief</b>. Built for retail users, at zero subscription cost.<br/><br/>
      <img src="https://img.shields.io/badge/Claude%20API-D97757?style=flat-square"/>
      <img src="https://img.shields.io/badge/Yahoo%20Finance-6001D2?style=flat-square&logo=yahoo&logoColor=white"/>
      <img src="https://img.shields.io/badge/ECB%20FX-003399?style=flat-square"/>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
    </td>
    <td width="50%" valign="top">
      <h3>🌾 <a href="https://github.com/ShivamBhosale/Agri-Optima">Agri-Optima</a></h3>
      <sub><b>DEEP LEARNING FOR AGRICULTURE</b></sub><br/><br/>
      Django + CNN platform for farmers: <b>crop yield prediction</b>, leaf disease detection, soil analysis, and a live news feed. Built with Agriculture &amp; Agri-Food Canada. <b>35k images, 95% accuracy, +15% over baseline.</b><br/><br/>
      <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white"/>
      <img src="https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white"/>
      <img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white"/>
      <img src="https://img.shields.io/badge/CNN-9B3FD1?style=flat-square"/>
    </td>
  </tr>
  <tr>
    <td colspan="2" valign="top">
      <h3>📄 <a href="https://github.com/ShivamBhosale/Ask-you-pdf">Ask-Your-PDF</a></h3>
      <sub><b>RAG DOCUMENT Q&amp;A</b></sub><br/><br/>
      Ask any PDF questions in plain English. Chunks the document, builds FAISS embeddings, and forces the LLM to answer <b>strictly from retrieved context</b>.<br/><br/>
      <img src="https://img.shields.io/badge/RAG-6C3CE9?style=flat-square"/>
      <img src="https://img.shields.io/badge/FAISS-0467DF?style=flat-square"/>
      <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square"/>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
    </td>
  </tr>
</table>

### 🧪 More Builds

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🌬️ <a href="https://github.com/ShivamBhosale/BreatheBeat">BreatheBeat</a> &nbsp;<a href="https://breathebeat.netlify.app/"><img src="https://img.shields.io/badge/LIVE%20DEMO-2E9E5B?style=flat-square"/></a></h3>
      <sub><b>MEDITATION AND BREATHING GUIDE</b></sub><br/><br/>
      Stopwatch and timer with three guided breathing rhythms (4-7-8, box breathing, 4-2-4), day streaks, lo-fi audio, and a warm "Soft Clay" design. <b>Zero build step, pure HTML, CSS, and JS.</b><br/><br/>
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>
      <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white"/>
      <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white"/>
    </td>
    <td width="50%" valign="top">
      <h3>🇫🇷 <a href="https://github.com/ShivamBhosale/FrenchFlow">FrenchFlow</a></h3>
      <sub><b>OFFLINE FRENCH TUTOR</b></sub><br/><br/>
      Flashcards with spaced repetition, AI grammar drills, a conversation tutor with inline corrections, and a translation checker. <b>Runs fully offline on Ollama + Mistral. No API keys, no subscriptions.</b><br/><br/>
      <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black"/>
      <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
      <img src="https://img.shields.io/badge/Ollama-000000?style=flat-square"/>
      <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>✉️ <a href="https://github.com/ShivamBhosale/EmailGenie">EmailGenie</a></h3>
      <sub><b>RELIABLE STRUCTURED LLM OUTPUT</b></sub><br/><br/>
      LLMs break format rules, so this one doesn't get the chance. A local model must return <b>strict JSON</b>, with self-healing extraction, schema validation, and automatic retries.<br/><br/>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
      <img src="https://img.shields.io/badge/Ollama-000000?style=flat-square"/>
      <img src="https://img.shields.io/badge/Qwen%202.5-6C3CE9?style=flat-square"/>
      <img src="https://img.shields.io/badge/JSON%20Schema-9B3FD1?style=flat-square"/>
    </td>
    <td width="50%" valign="top">
      <h3>🦫 <a href="https://github.com/ShivamBhosale/Capy">Capy</a></h3>
      <sub><b>DESKTOP COMPANION</b></sub><br/><br/>
      A 3D capybara that lives on your screen, tracks your cursor, hunches over to type along with you, and <b>celebrates when Claude Code finishes a task</b>. Controllable via hotkeys or a local HTTP endpoint.<br/><br/>
      <img src="https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white"/>
      <img src="https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white"/>
      <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td colspan="2" valign="top">
      <h3>📡 <a href="https://github.com/ShivamBhosale/nexus-signal">Nexus Signal</a></h3>
      <sub><b>AI-SUMMARIZED TECH AND SCIENCE NEWS</b></sub><br/><br/>
      Pulls articles from NewsData.io and RSS feeds (Ars Technica, MIT Tech Review, IEEE Spectrum, Nature), summarizes them with <b>Gemini 2.5 Flash</b>, and refreshes every 30 minutes. Built with a <b>freemium model</b>: 5 free articles per session, unlimited with a license key.<br/><br/>
      <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black"/>
      <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white"/>
      <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
      <img src="https://img.shields.io/badge/Gemini-4285F4?style=flat-square&logo=googlegemini&logoColor=white"/>
      <img src="https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white"/>
    </td>
  </tr>
</table>

---

## 🛠️ Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,r,cpp,postgres,mysql,mongodb,aws,azure,gcp,docker,tensorflow,pytorch,sklearn,fastapi,flask,django&perline=8" alt="Skill icons"/>
</p>

<table>
  <tr>
    <td><b>📊 Analytics and SQL</b></td>
    <td>Pandas · NumPy · PySpark · R · advanced SQL (CTEs, window functions) · EDA · feature engineering</td>
  </tr>
  <tr>
    <td><b>🧠 ML and Deep Learning</b></td>
    <td>Scikit-learn · TensorFlow · PyTorch · Keras · CNNs · anomaly detection · hyperparameter tuning · precision / recall / AUC / RMSE</td>
  </tr>
  <tr>
    <td><b>🤖 LLMs and Agentic AI</b></td>
    <td>Claude API · OpenAI · Gemini · RAG · FAISS · LangChain · LangGraph · CrewAI · MCP · A2A · Ollama</td>
  </tr>
  <tr>
    <td><b>📈 BI and Reporting</b></td>
    <td>Power BI · DAX · Tableau · Power Automate · Excel</td>
  </tr>
  <tr>
    <td><b>🗄️ Databases</b></td>
    <td>PostgreSQL · SQL Server · MySQL · MongoDB · query optimization · schema design</td>
  </tr>
  <tr>
    <td><b>☁️ Cloud, MLOps and App Dev</b></td>
    <td>AWS (S3, EC2) · Azure · GCP · Docker · CI/CD · FastAPI · Flask · Django · Streamlit · REST APIs</td>
  </tr>
</table>

---

## 🔭 Currently Exploring

`Multi-agent orchestration` &nbsp; `Long-context RAG + eval harnesses` &nbsp; `dbt and the modern data stack` &nbsp; `Decision engineering (AHP, TOPSIS)` &nbsp; `LLM-as-judge`

---

## 📬 Get in Touch

**Hiring an analyst who thinks like an engineer? Let's talk.**

<p align="center">
  <a href="mailto:shivambhosale909@gmail.com"><img src="https://img.shields.io/badge/Email-shivambhosale909%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/shivambhosale"><img src="https://img.shields.io/badge/LinkedIn-%2Fin%2Fshivambhosale-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://www.shivambhosale.me"><img src="https://img.shields.io/badge/Portfolio-shivambhosale.me-6C3CE9?style=for-the-badge&logo=google-chrome&logoColor=white"/></a>
</p>

<p align="center"><i>"Good decisions start with clean data."</i></p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E97627,50:6C3CE9,100:0A66C2&height=110&section=footer" alt="footer"/>
</p>
