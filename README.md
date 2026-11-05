## Hi, I'm Shivam Bajaj

**AI / ML Engineer · LLM applications · Computer vision · Data pipelines**

Final-year Computer Engineering student. I build AI systems end to end: from raw data and pipelines, to models, to FastAPI backends running in production. I care about honest evaluation: leak-free splits, held-out tests and numbers I can reproduce.

**Open to:** ML / AI Engineer, Data Scientist and Data Engineer roles, both internships and full-time (2027 graduate). Based in Mumbai, open to remote.

[Resume](https://drive.google.com/file/d/1mbhzfE8ChJrN1mia-MXdUjeriNTGVy7M/view?usp=sharing) · [LinkedIn](https://www.linkedin.com/in/bajaj30) · [Email](mailto:shivambajaj2065@gmail.com)

---

### Experience

**Machine Learning Intern, Fostride** (Sep 2026 – present) · *smart bins with built-in waste sorting*
- Raised waste-sorting F1 from 86% to 94.5% using DINO embeddings matched in a vector database (KNN, top-3 vote).
- Cut classification time from 600 ms to under 300 ms on CPU with smaller embeddings and an XGBoost classifier, now in production.

**Software and AI Development Intern, Electrion Technologies** (Jun – Aug 2026) · *desktop PCB fabrication machine*
- Built an optical inspection pipeline that finds breaks and shorts in circuit traces (ORB matching, RANSAC homography, mask comparison): 96.3% F1, 97.8% recall.
- Built a Python tool that converts Gerber PCB files into G-code and shows the live toolpath from microcontroller signals.

---

### Featured projects

| Project | What it does | Stack |
|---|---|---|
| **[TriageIQ](https://github.com/Bajaj30/TriageIQ)** · [live](https://triageiq-mu.vercel.app) | Predicts which consumer complaints end in a payout. Pipeline over 4.8M real CFPB complaints; reviewing the riskiest 10% catches 93% of payouts. | DistilBERT, ONNX Runtime, FastAPI, PostgreSQL, Docker, NGINX, AWS EC2 |
| **[NAVIN](https://github.com/Bajaj30/NAVIN)** · [live](https://navin-black.vercel.app) | GPS-free indoor parking navigation PWA. A 1D-CNN on phone motion sensors detects walking, stairs and parking (94.1% weighted F1). | PyTorch, ONNX Runtime, FastAPI, React |
| **[PrescriptAI](https://github.com/Bajaj30/Lyproj)** | Final-year team project: reads prescriptions with a vision-language model, matches drugs against 239,541 Indian brands and flags dangerous interactions. | VLM API, FastAPI, SQLite, React |
| **[SHL Recommender](https://github.com/Bajaj30/SHL_Recomender)** · [live](https://shl-recommender-486950393746.us-central1.run.app) | RAG API that recommends SHL assessments from natural-language hiring queries, grounded in the SHL catalog. | Gemini 2.5 Flash, Vertex AI, FAISS, FastAPI, Cloud Run |
| **[kronos-range-eval](https://github.com/Bajaj30/kronos-range-eval)** | Pre-registered, reproducible test: does the Kronos time-series foundation model forecast next-day NIFTY 50 ranges better than ATR(14)? | Python, PyTorch, time-series |
| **[PCB Fault Detection](https://github.com/Bajaj30/PCB_Fault_Detection)** | Finds breaks and shorts in PCB traces by aligning a board image to its reference and comparing copper masks. | OpenCV, ORB, RANSAC |

---

### Tech stack

- **Languages:** Python, SQL, JavaScript
- **ML and vision:** PyTorch, scikit-learn, XGBoost, ONNX Runtime, Hugging Face Transformers, OpenCV, DINO embeddings, vector search
- **LLMs and GenAI:** OpenAI and Gemini APIs, RAG, LLM agents, prompt engineering, vision-language models
- **Backend and data:** FastAPI, REST APIs, PostgreSQL, SQLite, Pandas, Docker Compose, NGINX, AWS EC2, Google Cloud Run

### Highlights

- MLH CSI Hackathon 2026: Top 5 of 22 teams, built a RAG tool that answers questions about a codebase in 24 hours
- Presented NAVIN at MechTech Ideathon 2026
- Machine Learning Specialization, DeepLearning.AI
- Currently working through Andrej Karpathy's deep learning lectures: [learning log](https://github.com/Bajaj30/Karpathy_DL_Learning_log)
