<h1 align="center">Hi there! 👋 I'm Danilo Yui Honda</h1>

<p align="center">
  <a href="https://github.com/DaniloHonda">
    <img src="https://readme-typing-svg.herokuapp.com?size=22&duration=3500&color=F7B93E&center=true&vCenter=true&width=620&lines=Data+Analyst+%40+XP+Inc.;BI+%26+Custom+Power+BI+Visuals+Engineer;GenAI+%26+Multi-Agent+Systems+Builder;Computer+Vision+%26+Medical+AI+Research;CS+Senior+%40+Mackenzie+(Dec+2026)" />
  </a>
</p>

<p align="center">
  Data Analyst focused on turning complex operational data into executive decisions, scalable <b>Databricks/PySpark</b> pipelines, custom <b>Power BI (TypeScript)</b> visuals, and <b>Generative AI / Multi-Agent</b> workflows.
</p>

---

## 💡 About Me

- **Data Analytics Intern** in People Analytics at **XP Inc.** (B2C Recruitment & Corporate HR), working as a Junior Data Analyst: executive dashboards in Power BI (PBIP + GitHub), SQL/PySpark pipelines on Databricks and LLM-based solutions.
- Built a proprietary library of **16 custom Power BI visuals in TypeScript** on top of the Power BI API — check out the **[Live Interactive Demo](https://danilohonda.github.io/visuais-powerbi-demo/)**.
- Architecting **Multi-Agent orchestration workflows (OMP, Hermes, MCP)** and LLM pipelines (including ranking **40,000+ resumes** to fill 70 roles in 15 days).
- Senior Computer Science student at **Universidade Presbiteriana Mackenzie** (graduating Dec 2026). My thesis compares a specialized deep learning model against multimodal LLMs for **diabetic retinopathy detection** — see the **[results page](https://danilohonda.github.io/cpdiabeticretinopathy-demo/)**.
- Fluent in **English (EF SET C2)**, native in **Portuguese**, intermediate in **Spanish**.

---

## 🚀 Tech Stack

### 📊 Data Analytics, BI & Big Data
<p align="center">
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
  <img src="https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white"/>
  <img src="https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white"/>
</p>

### 🤖 AI, Machine Learning & Agents
<p align="center">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/LLMs_%26_GenAI-412991?style=for-the-badge&logo=openai&logoColor=white"/>
  <img src="https://img.shields.io/badge/Multi--Agent_Systems-0F2744?style=for-the-badge&logo=dependabot&logoColor=white"/>
  <img src="https://img.shields.io/badge/Model_Context_Protocol-1A5276?style=for-the-badge&logo=anthropic&logoColor=white"/>
</p>

### 💻 Languages & Software Engineering
<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white"/>
  <img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white"/>
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white"/>
  <img src="https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white"/>
</p>

### 🛠️ Databases, DevOps & Tools
<p align="center">
  <img src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white"/>
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux_(WSL)-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  <img src="https://img.shields.io/badge/Azure_DevOps-0078D7?style=for-the-badge&logo=azuredevops&logoColor=white"/>
</p>

---

## 🌟 Featured Projects

### 👁️ Beyond the Human Eye — Diabetic Retinopathy Detection (Senior Thesis)

> Can a general-purpose LLM be trusted to read medical images? I compared a **specialized ConvNeXt-Small** against **Gemini 3 Flash, Gemini 3.5 Flash and Gemma 4** on the same **5,270 held-out fundus images** (EyePACS, split by patient to avoid leakage) for the 5-stage severity scale.

| Model | QWK | Accuracy |
|---|:---:|:---:|
| **ConvNeXt-Small (in-house)** | **0.83** | **0.83** |
| Gemini 3 Flash (zero-shot) | 0.45 | 0.74 |
| Gemini 3.5 Flash (zero-shot) | 0.43 | 0.76 |
| Gemma 4 26B (zero-shot) | 0.28 | 0.73 |

- **Key finding:** the LLMs reach ~74% accuracy mostly by answering "healthy" — 73.7% of the test set is healthy. Their recall on *mild* DR is ≤ 0.01, i.e. almost every early-stage case is missed. The specialized model keeps recall between 0.47 and 0.60 on every disease stage (0.59 on severe DR).
- **What made the difference:** ordinal regression (Smooth L1) instead of plain classification, Ben Graham preprocessing, a class-balanced sampler, validation-tuned thresholds (OptimizedRounder, optimizing QWK) and 4× test-time augmentation. Grad-CAM was used to inspect what the network looks at.
- **Stack:** Python, PyTorch, timm, Grad-CAM, Google Gemini API.
- 🔗 **[Interactive results page](https://danilohonda.github.io/cpdiabeticretinopathy-demo/)** · Code in a private repository · Co-authored with Luis Darre, advised by Prof. Anderson Borba (Mackenzie, 2026).
- ⚠️ Academic research. Not a medical device and not a substitute for professional evaluation.

### 🧩 Other projects

- **[Custom Power BI Visuals Library (Live Demo)](https://danilohonda.github.io/visuais-powerbi-demo/)** — Interactive browser showcase of 16 custom Power BI visuals built with TypeScript and the Power BI API (SLA tables with median/P90, conversion funnels, heatmaps, smart slicers, and CSV-exportable tables). The real visual code runs in the page against a fake Power BI host.
- **[Dento (`Private Repo`)](https://danilohonda.github.io/dento-deepdive/)** — Personal multi-agent orchestration system built with OMP, Hermes, and Python, integrated with a persistent Second Brain for long-term memory across finance, scheduling, and investments. Deep dive linked.
- **[Personal Portfolio](https://danilohonda.github.io/portifolio/)** — Vue 3 + Vite + TresJS site with a 3D particle galaxy, deployed with GitHub Pages ([source](https://github.com/DaniloHonda/portifolio)).
- **[NutriHub AI API](https://github.com/devBrait/nutrihub-ai-api)** — Microservices platform (.NET, C#, React, TypeScript, PostgreSQL) using AI to estimate calories/macros from meal photos and generate personalized diets.

---

## 📫 Connect with Me

<p align="center">
  <a href="https://www.linkedin.com/in/danilohonda">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="https://danilohonda.github.io/visuais-powerbi-demo/">
    <img src="https://img.shields.io/badge/Power_BI_Visuals_Demo-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
  </a>
  <a href="https://danilohonda.github.io/portifolio/">
    <img src="https://img.shields.io/badge/Portfolio-0F2744?style=for-the-badge&logo=vuedotjs&logoColor=white"/>
  </a>
  <a href="https://danilohonda.github.io/cpdiabeticretinopathy-demo/">
    <img src="https://img.shields.io/badge/Thesis_Results-2E7D32?style=for-the-badge&logo=pytorch&logoColor=white"/>
  </a>
  <a href="mailto:hondadanilo6@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
</p>

---

## 📊 GitHub Stats

<p align="center">
  <a href="https://github.com/DaniloHonda">
    <img height="180em" src="https://github-readme-stats.vercel.app/api?username=DaniloHonda&show_icons=true&theme=dark&hide_border=true&count_private=true"/>
    <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=DaniloHonda&layout=compact&langs_count=6&theme=dark&hide_border=true"/>
  </a>
</p>
