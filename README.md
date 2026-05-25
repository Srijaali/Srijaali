<div align="center">

<!-- ANIMATED NEURAL NETWORK BANNER -->
<svg width="860" height="280" viewBox="0 0 860 280" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <style>
      @keyframes pulse0  { 0%,100%{opacity:.12;r:2.5} 50%{opacity:.85;r:4.5} }
      @keyframes pulse1  { 0%,100%{opacity:.08;r:2}   50%{opacity:.7;r:4}   }
      @keyframes pulse2  { 0%,100%{opacity:.15;r:3}   50%{opacity:.9;r:5}   }
      @keyframes pulse3  { 0%,100%{opacity:.1;r:2.5}  50%{opacity:.6;r:4}   }
      @keyframes pulse4  { 0%,100%{opacity:.2;r:3.5}  50%{opacity:1;r:5.5}  }
      @keyframes edge0   { 0%,100%{opacity:.04} 50%{opacity:.22} }
      @keyframes edge1   { 0%,100%{opacity:.02} 50%{opacity:.18} }
      @keyframes edge2   { 0%,100%{opacity:.06} 50%{opacity:.28} }
      @keyframes edge3   { 0%,100%{opacity:.03} 50%{opacity:.15} }
      @keyframes fadein  { from{opacity:0;transform:translateY(8px)} to{opacity:1;transform:translateY(0)} }
      .n0{animation:pulse0 2.8s ease-in-out infinite}
      .n1{animation:pulse1 3.4s ease-in-out infinite}
      .n2{animation:pulse2 2.2s ease-in-out infinite}
      .n3{animation:pulse3 3.8s ease-in-out infinite}
      .n4{animation:pulse4 2.6s ease-in-out infinite}
      .n5{animation:pulse0 3.1s ease-in-out infinite .6s}
      .n6{animation:pulse2 2.9s ease-in-out infinite .3s}
      .n7{animation:pulse1 3.6s ease-in-out infinite .9s}
      .n8{animation:pulse4 2.4s ease-in-out infinite .4s}
      .n9{animation:pulse3 3.2s ease-in-out infinite .7s}
      .na{animation:pulse0 2.7s ease-in-out infinite 1.1s}
      .nb{animation:pulse2 3.5s ease-in-out infinite .2s}
      .nc{animation:pulse1 2.3s ease-in-out infinite .8s}
      .nd{animation:pulse4 3.0s ease-in-out infinite .5s}
      .ne{animation:pulse3 2.8s ease-in-out infinite 1.3s}
      .nf{animation:pulse0 3.3s ease-in-out infinite .1s}
      .ng{animation:pulse2 2.6s ease-in-out infinite 1.0s}
      .nh{animation:pulse1 3.7s ease-in-out infinite .4s}
      .ni{animation:pulse4 2.5s ease-in-out infinite 0.6s}
      .nj{animation:pulse3 3.1s ease-in-out infinite 1.2s}
      .e0{animation:edge0 2.8s ease-in-out infinite}
      .e1{animation:edge1 3.5s ease-in-out infinite .4s}
      .e2{animation:edge2 2.3s ease-in-out infinite .8s}
      .e3{animation:edge3 3.0s ease-in-out infinite .2s}
      .e4{animation:edge0 3.8s ease-in-out infinite 1.0s}
      .e5{animation:edge1 2.6s ease-in-out infinite .5s}
      .e6{animation:edge2 3.2s ease-in-out infinite .9s}
      .e7{animation:edge3 2.4s ease-in-out infinite 1.1s}
      .e8{animation:edge0 3.6s ease-in-out infinite .3s}
      .e9{animation:edge1 2.9s ease-in-out infinite .7s}
      .ea{animation:edge2 3.4s ease-in-out infinite 0s}
      .eb{animation:edge3 2.7s ease-in-out infinite 1.4s}
      .ec{animation:edge0 3.1s ease-in-out infinite .6s}
      .ed{animation:edge2 2.5s ease-in-out infinite 1.3s}
      .ee{animation:edge1 3.9s ease-in-out infinite .2s}
      .ef{animation:edge3 2.2s ease-in-out infinite .8s}
      .eg{animation:edge0 3.3s ease-in-out infinite 1.2s}
      .eh{animation:edge2 2.8s ease-in-out infinite .4s}
      .hero{animation:fadein 1.2s ease-out both}
      .sub{animation:fadein 1.4s ease-out .3s both}
    </style>
    <!-- glow filter -->
    <filter id="glow">
      <feGaussianBlur stdDeviation="2.5" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>
  <rect width="860" height="280" fill="#0a0a0a"/>

  <!-- EDGES (layer 0→1) -->
  <g stroke="#c9847a" stroke-width="0.7" fill="none">
    <line class="e0" x1="68" y1="52"  x2="172" y2="42"/>
    <line class="e1" x1="68" y1="52"  x2="172" y2="98"/>
    <line class="e2" x1="68" y1="52"  x2="172" y2="160"/>
    <line class="e3" x1="68" y1="115" x2="172" y2="42"/>
    <line class="e4" x1="68" y1="115" x2="172" y2="98"/>
    <line class="e5" x1="68" y1="115" x2="172" y2="160"/>
    <line class="e6" x1="68" y1="115" x2="172" y2="220"/>
    <line class="e7" x1="68" y1="180" x2="172" y2="98"/>
    <line class="e8" x1="68" y1="180" x2="172" y2="160"/>
    <line class="e9" x1="68" y1="180" x2="172" y2="220"/>
    <line class="ea" x1="68" y1="245" x2="172" y2="160"/>
    <line class="eb" x1="68" y1="245" x2="172" y2="220"/>
  </g>

  <!-- EDGES (layer 1→2) -->
  <g stroke="#c9847a" stroke-width="0.7" fill="none">
    <line class="ec" x1="172" y1="42"  x2="288" y2="70"/>
    <line class="e0" x1="172" y1="42"  x2="288" y2="140"/>
    <line class="ed" x1="172" y1="98"  x2="288" y2="70"/>
    <line class="ee" x1="172" y1="98"  x2="288" y2="140"/>
    <line class="e1" x1="172" y1="98"  x2="288" y2="210"/>
    <line class="ef" x1="172" y1="160" x2="288" y2="70"/>
    <line class="e2" x1="172" y1="160" x2="288" y2="140"/>
    <line class="eg" x1="172" y1="160" x2="288" y2="210"/>
    <line class="e3" x1="172" y1="220" x2="288" y2="140"/>
    <line class="eh" x1="172" y1="220" x2="288" y2="210"/>
  </g>

  <!-- EDGES (layer 2→3) -->
  <g stroke="#c9847a" stroke-width="0.7" fill="none">
    <line class="e4" x1="288" y1="70"  x2="572" y2="42"/>
    <line class="ea" x1="288" y1="70"  x2="572" y2="98"/>
    <line class="e5" x1="288" y1="70"  x2="572" y2="160"/>
    <line class="eb" x1="288" y1="140" x2="572" y2="42"/>
    <line class="e6" x1="288" y1="140" x2="572" y2="98"/>
    <line class="ec" x1="288" y1="140" x2="572" y2="160"/>
    <line class="e7" x1="288" y1="140" x2="572" y2="220"/>
    <line class="ed" x1="288" y1="210" x2="572" y2="98"/>
    <line class="e8" x1="288" y1="210" x2="572" y2="160"/>
    <line class="ee" x1="288" y1="210" x2="572" y2="220"/>
  </g>

  <!-- EDGES (layer 3→4) -->
  <g stroke="#c9847a" stroke-width="0.7" fill="none">
    <line class="ef" x1="572" y1="42"  x2="688" y2="55"/>
    <line class="e9" x1="572" y1="42"  x2="688" y2="120"/>
    <line class="eg" x1="572" y1="98"  x2="688" y2="55"/>
    <line class="ea" x1="572" y1="98"  x2="688" y2="120"/>
    <line class="e0" x1="572" y1="98"  x2="688" y2="185"/>
    <line class="eh" x1="572" y1="160" x2="688" y2="55"/>
    <line class="eb" x1="572" y1="160" x2="688" y2="120"/>
    <line class="e1" x1="572" y1="160" x2="688" y2="185"/>
    <line class="ec" x1="572" y1="220" x2="688" y2="120"/>
    <line class="e2" x1="572" y1="220" x2="688" y2="185"/>
    <line class="ed" x1="572" y1="220" x2="688" y2="245"/>
    <line class="ef" x1="572" y1="160" x2="688" y2="245"/>
  </g>

  <!-- EDGES (layer 4→5/output) -->
  <g stroke="#c9847a" stroke-width="0.7" fill="none">
    <line class="e3" x1="688" y1="55"  x2="800" y2="82"/>
    <line class="eg" x1="688" y1="55"  x2="800" y2="140"/>
    <line class="e4" x1="688" y1="120" x2="800" y2="82"/>
    <line class="eh" x1="688" y1="120" x2="800" y2="140"/>
    <line class="e5" x1="688" y1="120" x2="800" y2="200"/>
    <line class="ea" x1="688" y1="185" x2="800" y2="140"/>
    <line class="e6" x1="688" y1="185" x2="800" y2="200"/>
    <line class="eb" x1="688" y1="245" x2="800" y2="140"/>
    <line class="e7" x1="688" y1="245" x2="800" y2="200"/>
  </g>

  <!-- NODES layer 0 (input) -->
  <g fill="#c9847a" filter="url(#glow)">
    <circle class="n0" cx="68" cy="52"  r="3"/>
    <circle class="n1" cx="68" cy="115" r="2.5"/>
    <circle class="n2" cx="68" cy="180" r="3"/>
    <circle class="n3" cx="68" cy="245" r="2"/>
  </g>

  <!-- NODES layer 1 -->
  <g fill="#c9847a" filter="url(#glow)">
    <circle class="n4" cx="172" cy="42"  r="3"/>
    <circle class="n5" cx="172" cy="98"  r="2.5"/>
    <circle class="n6" cx="172" cy="160" r="3.5"/>
    <circle class="n7" cx="172" cy="220" r="2"/>
  </g>

  <!-- NODES layer 2 (hidden, denser) -->
  <g fill="#c9847a" filter="url(#glow)">
    <circle class="n8" cx="288" cy="70"  r="3.5"/>
    <circle class="n9" cx="288" cy="140" r="4"/>
    <circle class="na" cx="288" cy="210" r="2.5"/>
  </g>

  <!-- NODES layer 3 (hidden) -->
  <g fill="#c9847a" filter="url(#glow)">
    <circle class="nb" cx="572" cy="42"  r="3"/>
    <circle class="nc" cx="572" cy="98"  r="2.5"/>
    <circle class="nd" cx="572" cy="160" r="3.5"/>
    <circle class="ne" cx="572" cy="220" r="2"/>
  </g>

  <!-- NODES layer 4 -->
  <g fill="#c9847a" filter="url(#glow)">
    <circle class="nf" cx="688" cy="55"  r="3"/>
    <circle class="ng" cx="688" cy="120" r="3.5"/>
    <circle class="nh" cx="688" cy="185" r="2.5"/>
    <circle class="ni" cx="688" cy="245" r="2"/>
  </g>

  <!-- NODES layer 5 (output) -->
  <g fill="#c9847a" filter="url(#glow)">
    <circle class="nj" cx="800" cy="82"  r="3"/>
    <circle class="n0" cx="800" cy="140" r="4"/>
    <circle class="n4" cx="800" cy="200" r="2.5"/>
  </g>

  <!-- LAYER LABELS -->
  <g font-family="monospace" font-size="9" fill="#3a1a1f" letter-spacing="1">
    <text x="68"  y="272" text-anchor="middle">input</text>
    <text x="172" y="272" text-anchor="middle">layer 1</text>
    <text x="288" y="272" text-anchor="middle">layer 2</text>
    <text x="572" y="272" text-anchor="middle">layer 3</text>
    <text x="688" y="272" text-anchor="middle">layer 4</text>
    <text x="800" y="272" text-anchor="middle">output</text>
  </g>

  <!-- HERO TEXT — centered, with solid background rect for readability -->
  <rect x="230" y="95" width="400" height="95" rx="4" fill="#0a0a0a" opacity="0.78"/>

  <text class="hero" x="430" y="148"
    font-family="Georgia, serif" font-size="42" font-weight="400"
    fill="#f8f4f0" text-anchor="middle" dominant-baseline="middle"
    letter-spacing="-0.5">hey, i'm rija</text>

  <text class="sub" x="430" y="178"
    font-family="monospace" font-size="11" font-weight="300"
    fill="#c9847a" text-anchor="middle" letter-spacing="3">
    ai engineer · data scientist · nlp researcher
  </text>
</svg>

</div>

---

## 🪐 About me

I build AI systems at the intersection of **real-world impact** and research — from map-free navigation for the visually impaired to explainable mental health reasoning engines. Currently wrapping up my final year in **Artificial Intelligence** at FAST-NUCES.

Outside of AI, I co-founded **RUI** — a minimalist fashion brand. I think good design, whether in models or clothes, comes down to the same thing: knowing what to leave out.

```
🎓  4th year AI student @ FAST-NUCES
🔍  Interests: ML · NLP · Knowledge Systems · Data Science
📬  Open to internships and research collaborations
👗  Co-founder @ RUI (minimalist fashion)
```

---

## ⚙️ Tech stack

**Languages**

![Python](https://img.shields.io/badge/Python-3572A5?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-f34b7d?style=flat-square&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-f1e05a?style=flat-square&logo=javascript&logoColor=black)
![HTML/CSS](https://img.shields.io/badge/HTML%2FCSS-e34c26?style=flat-square&logo=html5&logoColor=white)

**AI / ML**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

`RAG` &nbsp; `Prompt Engineering` &nbsp; `Semantic Search` &nbsp; `SPARQL / OWL` &nbsp; `Embeddings` &nbsp; `YOLO` &nbsp; `LangGraph` &nbsp; `pgVector`

**Infra & tools**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## 🏆 Featured projects

<table>
<tr>
<td width="50%" valign="top">

### 🦯 Vision-to-Voice
**Navigation for the Visually Impaired** &nbsp;`Feb 2026 – Apr 2026`

Map-free navigation using real-time scene understanding. Integrated DINOv3 embeddings, YOLOE detection, and JEPA-based world modeling. Explainable voice guidance via SmoothGrad & AttnLRP.

`PyTorch` `DINOv3` `YOLOE` `EasyOCR` `NetworkX`

[![View](https://img.shields.io/badge/View_Project-c9847a?style=flat-square)](https://github.com/Srijaali/Vision-to-Voice)

</td>
<td width="50%" valign="top">

### 👗 LAYR — Fashion E-commerce ML
**End-to-end ML Pipeline** &nbsp;`Aug – Dec 2025`

80M+ record ML pipeline (5.2GB). Hybrid recommendation engine, Sentence-BERT sentiment analysis, Prophet/ARIMA demand forecasting, RFM customer segmentation.

`Sentence-BERT` `Prophet` `FastAPI` `PostgreSQL` `MLflow`

[![View](https://img.shields.io/badge/View_Project-c9847a?style=flat-square)](https://github.com/Srijaali/ml-based_Fashion-Ecommerce)

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 🧠 Companion — Mental Health KRR
**Ontology-Driven Reasoning** &nbsp;`Team Lead · Oct – Nov 2025`

Knowledge representation for explainable mental health risk awareness. OWL, RDF, SWRL, and SPARQL for causal reasoning over emotions.

`OWL` `RDF` `SWRL` `SPARQL` `FastAPI` `React`

[![View](https://img.shields.io/badge/View_Project-c9847a?style=flat-square)](https://github.com/Srijaali)

</td>
<td width="50%" valign="top">

### 🪞 LifeMirror — AI Perception Engine
**Multi-Agent Appearance Analysis** &nbsp;`Mar 2025 – Ongoing`

Multi-agent AI with YOLO vision models, LangGraph orchestration, pgVector semantic search, MinIO storage, Celery async processing.

`FastAPI` `LangChain` `YOLO` `pgVector` `Redis` `MinIO`

[![View](https://img.shields.io/badge/View_Project-c9847a?style=flat-square)](https://github.com/Srijaali)

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 📊 Data Analytics Portfolio
**Business Intelligence & EDA**

Exploratory data analysis, statistical modeling, data visualization, business intelligence, and data storytelling projects.

`Pandas` `NumPy` `Matplotlib` `Seaborn` `PowerBI` `Excel`

[![View](https://img.shields.io/badge/View_Project-c9847a?style=flat-square)](https://github.com/Srijaali)

</td>
<td width="50%" valign="top">

### ⚡ Prodigy — AI Productivity Tool
**Full-Stack Platform** &nbsp;`Team Lead · Feb – Jun 2024`

GPT-4 note summarization, Pomodoro workflows, calendar sync, and focus analytics. Led a cross-functional team end to end.

`React` `TypeScript` `Tailwind CSS` `Firebase` `OpenAI GPT-4`

[![View](https://img.shields.io/badge/View_Project-c9847a?style=flat-square)](https://github.com/Srijaali)

</td>
</tr>
</table>

---

## 💼 Experience

**Project Management Intern — AI Systems** &nbsp;·&nbsp; SysLab.ai &nbsp;`Nov 2025 – Feb 2026`
> Coordinated AI-based assessment and proctoring platforms. Bridge between technical and non-technical teams across planning, QA, and release cycles.

**Co-Founder — RUI** &nbsp;`Aug 2025 – Present`
> Minimalist fashion brand built around soft silhouettes and quiet confidence. Led brand strategy, concept development, and product direction.

---

## 📊 GitHub stats

<div align="center">

<img height="155" src="https://github-readme-stats.vercel.app/api?username=Srijaali&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" />
<img height="155" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Srijaali&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" />

[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com?user=Srijaali&theme=tokyonight&hide_border=true)](https://git.io/streak-stats)

</div>

---

## 📄 Resume

<div align="center">

[![View Resume](https://img.shields.io/badge/View_Resume-c9847a?style=for-the-badge&logo=readme&logoColor=white)](YOUR_RESUME_LINK)
&nbsp;
[![Download PDF](https://img.shields.io/badge/Download_PDF-1a0d0e?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](YOUR_PDF_LINK)

</div>

---

## 🤝 Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/syeda-rija-ali)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:YOUR_EMAIL)
[![GitHub](https://img.shields.io/badge/GitHub-171515?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Srijaali)

&nbsp;

**Open to collaborating on:**

`ML Systems` &nbsp; `NLP Research` &nbsp; `AI Agents` &nbsp; `Knowledge Graphs` &nbsp; `Open Source`

&nbsp;

![Profile Views](https://komarev.com/ghpvc/?username=Srijaali&color=c9847a&style=flat-square&label=profile+views)

</div>

---

<div align="center">

*"Good design — whether in models or clothes — is knowing what to leave out."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=7a3535,c9847a&height=80&section=footer" />

</div>
