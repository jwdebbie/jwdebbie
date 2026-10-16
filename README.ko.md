<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=wave&color=timeGradient&text=%EC%95%88%EB%85%95%ED%95%98%EC%84%B8%EC%9A%94%2C%20%EC%A3%BC%EC%9B%90%EC%9E%85%EB%8B%88%EB%8B%A4%20%F0%9F%91%8B&animation=twinkling&fontSize=35&fontAlignY=33&fontAlign=50&height=250" />
</p>

<p align="center">
  <a href="https://github.com/jwdebbie">English</a> | <b>한국어</b>
</p>

<p align="center">
  AI를 직접 만들고, <b>실제 환경에서 어디서 무너지는지</b> 검증하고, 그 결과를 누구나 판단할 수 있게 전달합니다 🌍<br/><br/>
  <b>관심 분야</b> Physical AI · Vision-Language Model · Robust Perception · Agentic AI<br/>
  <b>현재</b> AI 프로덕트 · 전략 · 엔지니어링 직무 탐색 중
</p>

<p align="center">
  <a href="mailto:leejoowon09@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=Gmail&logoColor=white"/></a>&nbsp;
  <a href="https://velog.io/@joowoni/posts"><img src="https://img.shields.io/badge/Velog-20C997?style=flat-square&logo=Velog&logoColor=white"/></a>
  <br/>
  <sub>숙명여자대학교 인공지능공학 학사 · TOEIC 945 · TOEIC Speaking AL · HSK 6급</sub>
</p>

---

<h3 align="center">🧭 이런 일을 합니다</h3>

| | 의미 | 근거 |
|---|---|---|
| **Build** | LLM·에이전트 파이프라인을 처음부터 끝까지 설계하고 구현 | 고객 폭언 대응 AI, 멀티 에이전트 퀀트 리포트 서비스 |
| **Evaluate** | 모델이 실험실 밖에서 어디서, 왜 실패하는지 검증 | 환경 변화 속 칼 인식, 딥페이크 탐지, 합성 데이터 품질 필터링 |
| **Translate** | 사용자 문제와 연구 내용을 명확한 판단과 문서로 정리 | AIME 사용자 조사, MITA 논문 4편, 연구실 논문 발표 |

---

<h3 align="center">⭐ 대표 프로젝트</h3>

#### 🛡️ 고객 폭언 대응 및 신고 판단을 돕는 근로자 보호 AI 서비스
<sub><b>Azure 산학협력 프로젝트</b> · 2025 · <a href="https://github.com/team2321">GitHub</a></sub>

- **문제** : 상담 근로자는 고객의 폭언이 신고 가능한 수준인지 빠르고 근거 있게 판단하기 어렵습니다.
- **한 일** : STT → Content Safety → RAG → LLM으로 이어지는 파이프라인을 **위험도(severity) 기반 분기**로 설계했습니다. 위험도가 낮으면 바로 종결하고, 일정 수준 이상이면 근로자 보호 가이드를 검색해 few-shot으로 신고 가능 여부를 판단합니다. 개발 중 Content Safety가 욕설을 `***`로 자동 마스킹해 공격성이 가려지는 문제를 발견했고, 필터 임계치 재설정과 JSON 구조화 출력으로 해결했습니다.
- **결과** : 5문장 분량의 폭언도 **5초 이내에** 상황 요약, 대응 요령, 신고 판단, 법률 분류까지 완료합니다.

#### 📗 교제폭력 피해 증거 기록을 위한 AI 다이어리 서비스 "AIME"
<sub><b>네이버 AI RUSH 2024 · Best Model Tuning Award</b> · 2024 · <a href="https://github.com/jwdebbie/NAVER-AI-RUSH-2024">GitHub</a></sub>

- **문제** : 피해자는 증거를 모으기 어렵고, 심리적 부담 때문에 도움을 요청하기도 쉽지 않습니다.
- **한 일** : HyperCLOVA X 프롬프트 최적화와 UX 설계를 주도했습니다. OCR과 STT로 캡처본과 녹음 파일을 텍스트 기록으로 바꾸고, 중립성 가이드와 원문 보존 원칙으로 **과잉 공감과 없는 서사를 지어내는 환각**을 제어했습니다. 필수 질문 7가지를 모두 거쳐야 일기를 작성하도록 대화 흐름도 설계했습니다.
- **결과** : 사용자 테스트에서 **88.3%** 가 증거 정리 기능이 필요하다고 답했고, 67%가 상담기관 연계 기능이 유용하다고 평가했습니다.

#### 🔪 환경 변화에 강건한 CCTV 칼 인식 연구
<sub><b>MITA 2025 · 제1저자, 구두 발표</b> · 2025 · <a href="https://github.com/jwdebbie/Knife-Classification-Dataset">GitHub</a></sub>

- **문제** : 파일럿 실험에서 YOLOv8이 mAP@0.5 = 0.972를 기록했지만, 장소도 칼도 하나뿐이었습니다. 평균 점수가 높다고 실제 CCTV 환경에서도 믿을 수 있는지는 알 수 없었습니다.
- **한 일** : 조명, 배경, 가림, 칼 종류를 라벨링한 영상 19개로 약 15,800장의 데이터셋을 만들고, CNN 모델 4개를 같은 조건에서 학습해 환경별로 성능을 나눠 비교했습니다.
- **결과** : **모든 환경에서 가장 좋은 모델은 없다**는 것을 확인했습니다. DenseNet121은 조건과 상관없이 고르게 버텼지만, EfficientNetB0은 **어두운 장면에서 13.7%** 까지 떨어지고 배경에 따라 100%에서 4.6%까지 흔들렸습니다. 이를 바탕으로 배치 환경별 모델 선택 가이드를 정리했습니다.

---

<h3 align="center">🍒 그 외 프로젝트</h3>

| 프로젝트 | 분야 | 연도 | |
|---|---|---|---|
| **멀티 에이전트 기반 맞춤형 퀀트 투자 리포트 서비스** | LangGraph · Multi-Agent | 2026 | [GitHub](https://github.com/jwdebbie/quant-ai-server) |
| **합성 이미지를 활용한 데이터 부족 클래스 보강 실험** | Synthetic Data | 2026 | [GitHub](https://github.com/jwdebbie/Longtail-Synthetic-Augmentation) |
| **CLIP Score 기반 저품질 합성 데이터 필터링 연구** | Data Quality | 2026 | [GitHub](https://github.com/jwdebbie/Clip-Data-Curation) |
| **메타러닝 기반 개인별 등산 활동 패턴 분석 연구** | MAML · Personalization | 2026 | [GitHub](https://github.com/jwdebbie/agi_hiking) |
| **합성 경계 흔적을 활용한 고품질 딥페이크 탐지 연구** | CV · Forensics | 2025 | [GitHub](https://github.com/jwdebbie/Faceswap-Detection) |
| **발표 분석 및 피드백 제공 AI 코칭 서비스 "발표HAI"** · *멋쟁이사자처럼 아이디어톤 우수상* | STT · Multimodal | 2025 | |

---

<h3 align="center">💼 연구 경력</h3>

**학부연구생, 고려대학교 CV Lab** · `2026.03 – 2026.07`
<br/><sub>VLM 연구팀에서 멀티 에이전트 자기진화와 Document VQA 연구(MACT, Vision-Zero)를 조사하고 연구실 논문 발표를 맡았습니다.</sub>

**학부연구생, 숙명여자대학교 AGI Lab** · `2025.04 – 2026.02`
<br/><sub>강건한 인식, 딥페이크 탐지, 메타러닝 개인화 연구를 수행했고 MITA 2025 논문 4편에 참여했습니다.</sub>

---

<h3 align="center">🍪 논문 실적</h3>

1. **Joowon Lee** et al., "Knife Classification Under Environmental Variations Using CNN Models," *MITA 2025* · 제1저자, 구두 발표
2. Daun Lee, **Joowon Lee** et al., "Recent Research Trends of Gait Analysis," *MITA 2025*
3. Seong Won An, ..., **Joowon Lee** et al., "A Meta-Learning Discriminator Framework for Multi-Generator Fake Images," *MITA 2025*
4. Seong-won An, ..., **Joo-won Lee** et al., "A Survey on Deepfake Image Detection," *MITA 2025*

---

<h3 align="center">🛠️ 기술 스택</h3>
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
