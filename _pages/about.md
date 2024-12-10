---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

Welcome! I am Tony, a final-year Systems and Electronics Engineering student at Universidad de los Andes and a researcher at the Center of Research and Formation in Artificial Intelligence (CinfonIA). Currently, I am a research intern at Cornell University and recently started to collaborate on research with a professor from the University of Illinois Chicago (UIC). My experience centers on NLP and GenAI, with a strong focus on developing reasoning capabilities for multimodal agents (image/video) to address complex real-world tasks and understand inherent semantics. My ongoing research and recent publications support this passion.

# 📄 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">LChange 2024</div><img src='images/projects/SSD.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Semantic Shift Detection for 19th Century Spanish](https://aclanthology.org/2024.lchange-1.4.pdf)

**Tony Montes**, Laura Manrique-Gómez, Rubén Manrique

[**Code**](https://github.com/historicalink/SSD-Old-Spanish) 
- Implemented a pipeline for detection of semantic shifts (changes in meaning) between two datasets in the same language, employing contextual word embeddings with BERT (fine-tuned on the historical dataset) and KMeans clustering.
- Tested the solution with the LSCDiscovery Binary Change Detection task, among different BERT-like models and clustering algorithms, and checked it's performance over 250 historic words.
- Compiled the biggest 19th-century Spanish dataset with ~180M tokens, within 3 different sources: Project Gutenberg, The British Library Books, and LatamXIX.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NLP4DH 2024</div><img src='images/projects/LLM-OCR.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[19th Century Latin American Spanish Newspaper Corpus with LLM OCR Correction](https://aclanthology.org/2024.nlp4dh-1.13.pdf)

Laura Manrique-Gómez, **Tony Montes**, Arturo Rodríguez-Herrera, Rubén Manrique

[**Dataset**](https://huggingface.co/datasets/Flaglab/latam-xix)
- Developed a semi-automated methodology for correction of OCR errors and detection of surface forms in historical datasets, employing LLMs and a diff algorithm.
- Applied the methodology to LatamXIX, a 19th-century Latin American Spanish newspaper corpus developed by _Laura Manrique-Gómez_, achieving the expected results checked by experts.
</div>
</div>

# 📖 Education
- *2020.01 - 2024.12*, Universidad de los Andes, BS, Systems and Computing Engineering
- *2020.08 - 2024.12*, Universidad de los Andes, BS, Electronics Engineering

# 🏢 Research Experience

- *Research Intern*, Cornell University
  * Researcher at the ECE department,advised by Prof. [Zhiru Zhang](https://www.csl.cornell.edu/~zhiruz/), employing language models for 3D-asset and image compression and controlled diffusion models for decompression with semantics and canny edge maps

- *External Researcher*, University of Illinois Chicago
  * Researcher advised by Prof. [Moontae Lee](https://moontae.people.uic.edu/), working on an agent Web-RAG-based solution for code assistance on completion, fixing and solving tasks

- *Research Assistant*, Universidad de los Andes
  * Researcher at the Center of Research and Formation in Artificial Intelligence (CinfonIA) in the Historical Ink project, led by Prof. [Rubén Manrique](https://academia.uniandes.edu.co/AcademyCv/rf.manrique)

- *BS Student*, Universidad de los Andes
  * Systems and Computing Engineering thesis: "_Semantic Shift Detection for 19th Century Spanish_", advised by Prof. [Rubén Manrique](https://academia.uniandes.edu.co/AcademyCv/rf.manrique)
  * Electronics Engineering thesis: "_Zero-Shot Video Question Answering via Agent with Open-Vocabulary Grounding Validation_", advised by Prof. [Fernando Lozano](https://academia.uniandes.edu.co/AcademyCv/flozano)
