<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=wave&color=timeGradient&text=Welcome%20to%20Joowon's%20GitHub%20👋&animation=twinkling&fontSize=35&fontAlignY=33&fontAlign=50&height=250" />
</p>

<p align="center">
  <b>English</b> | <a href="https://github.com/jwdebbie/jwdebbie/blob/main/README.ko.md">한국어</a>
</p>

<p align="center">
  I build AI, test where it breaks in the real world, and explain it so people can act on it 🌍<br/><br/>
  <b>Interested in</b> Physical AI · Robust Perception · Agentic AI<br/>
  <b>Currently</b> exploring AI product, strategy, and engineering roles
</p>

<p align="center">
  <a href="mailto:leejoowon09@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=Gmail&logoColor=white"/></a>&nbsp;
  <a href="https://velog.io/@joowoni/posts"><img src="https://img.shields.io/badge/Velog-20C997?style=flat-square&logo=Velog&logoColor=white"/></a>
  <br/>
  <sub>B.S. AI Engineering @ Sookmyung Women's University · TOEIC 945 · TOEIC Speaking AL · HSK Level 6</sub>
</p>

---

<h3 align="center">🧭 What I Do</h3>

| | What it means | Where I've done it |
|---|---|---|
| **Build** | Design and ship LLM and agent pipelines end to end | Worker-protection AI for abusive calls, multi-agent quant report service |
| **Evaluate** | Find where models fail outside the lab, and why | Knife recognition under environmental variations, deepfake detection, synthetic data quality filtering |
|  **Translate** | Turn user problems and research into clear decisions and documents | AIME user research, 4 MITA papers, lab paper presentations |

---

<h3 align="center">⭐ Featured Projects</h3>

#### 🛡️ Worker-Protection AI for Abusive Customer Calls
<sub><b>Azure Industry-Academia Project</b> · 2025 · <a href="https://github.com/team2321">GitHub</a></sub>

- **Problem** : Call-center workers need fast, grounded guidance on whether abusive speech is reportable.
- **What I did** : Designed an STT → Content Safety → RAG → LLM pipeline with **severity-based branching**: low-severity calls exit early, higher ones retrieve worker-protection guidelines and judge reportability with few-shot prompting. Caught that Content Safety auto-masked profanity (`***`) and hid the aggression, then fixed it by retuning filter thresholds and enforcing structured JSON output.
- **Impact** : Summary, response guide, report decision, and legal category for a 5-sentence abusive message in **under 5 seconds**.

#### 📗 AIME — AI Diary for Documenting Dating-Violence Evidence
<sub><b>NAVER AI RUSH 2024 · Best Model Tuning Award</b> · 2024 · <a href="https://github.com/jwdebbie/NAVER-AI-RUSH-2024">GitHub</a></sub>

- **Problem** : Victims struggle to collect evidence, and psychological barriers keep them from seeking help.
- **What I did** : Led HyperCLOVA X prompt optimization and UX design. Combined OCR and STT to turn screenshots and recordings into text records. Controlled **over-empathy and hallucinated narratives** with neutrality and source-preservation rules, and built a state-controlled dialogue that collects 7 required facts before writing the diary.
- **Impact** : **88.3%** of test users said they needed the evidence feature, and 67% found the counseling-center link useful.

#### 🔪 Knife Classification Under Environmental Variations
<sub><b>MITA 2025 · 1st Author, Oral</b> · 2025 · <a href="https://github.com/jwdebbie/Knife-Classification-Dataset">GitHub</a></sub>

- **Problem** : A pilot YOLOv8 test scored mAP@0.5 = 0.972, but on one location and one knife. A high average score says little about how a model holds up on real CCTV.
- **What I did** : Built a ~15,800-image dataset from 19 videos labeled by lighting, background, occlusion, and knife type, then trained 4 CNNs under identical settings and broke accuracy down by condition.
- **Impact** : Showed that **no single model wins everywhere**: DenseNet121 stayed stable across conditions, while EfficientNetB0 fell to **13.7% in the dark** and swung from 100% to 4.6% by background. Turned this into a deployment guide for picking a model by environment.

---

<h3 align="center">🍒 More Projects</h3>

| Project | Focus | Year | |
|---|---|---|---|
| **Multi-Agent Personalized Quant Investment Report Service** | LangGraph · Multi-Agent | 2026 | [GitHub](https://github.com/jwdebbie/quant-ai-server) |
| **Long-Tail Class Augmentation with Synthetic Images** | Synthetic Data | 2026 | [GitHub](https://github.com/jwdebbie/Longtail-Synthetic-Augmentation) |
| **CLIP Score-based Filtering of Low-Quality Synthetic Data** | Data Quality | 2026 | [GitHub](https://github.com/jwdebbie/Clip-Data-Curation) |
| **Meta-Learning-based Personalized Hiking Activity Analysis** | MAML · Personalization | 2026 | [GitHub](https://github.com/jwdebbie/agi_hiking) |
| **High-Fidelity Deepfake Detection via Boundary Artifacts** | CV · Forensics | 2025 | [GitHub](https://github.com/jwdebbie/Faceswap-Detection) |
| **AI Presentation Coaching Service "발표HAI"** · *LIKELION Ideathon, Excellence Award* | STT · Multimodal | 2025 | |

---
<h3 align="center">🎓 Education</h3>

**B.S. in Artificial Intelligence Engineering, Sookmyung Women's University** · `2023.03 – Present`
<br/>
**Chinese Major, Gyeonggi Academy of Foreign Languages** · `2018.03 – 2021.01`

---

<h3 align="center">💼 Experience</h3>

**Undergraduate Researcher, CV Lab, Korea University** · `2026.03 – 2026.07`
<br/><sub>Long-tail recognition via CLIP-filtered synthetic data and LLM-guided regeneration; VLM self-evolution research.</sub>

**Undergraduate Researcher, AGI Lab, Sookmyung Women's University** · `2025.04 – 2026.02`
<sub>Robust perception, deepfake detection, and meta-learning personalization (industry R&D with INavI Systems). 4 papers at MITA 2025, incl. 1 first-author oral.</sub>

---

<h3 align="center">🍪 Publications</h3>

1. **Joowon Lee** et al., "Knife Classification Under Environmental Variations Using CNN Models," *MITA 2025* · 1st author, Oral
2. Daun Lee, **Joowon Lee** et al., "Recent Research Trends of Gait Analysis," *MITA 2025*
3. Seong Won An, ..., **Joowon Lee** et al., "A Meta-Learning Discriminator Framework for Multi-Generator Fake Images," *MITA 2025*
4. Seong-won An, ..., **Joo-won Lee** et al., "A Survey on Deepfake Image Detection," *MITA 2025*

---

<h3 align="center">🛠️ Tech Stack</h3>
<p align="center">
  <img src="https://img.shields.io/badge/Python-3766AB?style=flat-square&logo=Python&logoColor=white"/>&nbsp;
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=PyTorch&logoColor=white"/>&nbsp;
  <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=HuggingFace&logoColor=black"/>&nbsp;
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=OpenCV&logoColor=white"/>&nbsp;
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=LangChain&logoColor=white"/>&nbsp;
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=PostgreSQL&logoColor=white"/>&nbsp;
  <br/>
  <img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=MicrosoftAzure&logoColor=white"/>&nbsp;
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=AmazonAWS&logoColor=white"/>&nbsp;
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=Docker&logoColor=white"/>&nbsp;
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=Git&logoColor=white"/>&nbsp;
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=Streamlit&logoColor=white"/>&nbsp;
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=Figma&logoColor=white"/>&nbsp;
</p>
