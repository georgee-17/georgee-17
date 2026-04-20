# George Emmanuel

**MSc Data Sciences & Business Analytics · CentraleSupélec / ESSEC · Paris**

I am a data scientist and analyst with a background that spans early-stage startups,
agri-tech commercial roles, and academic research in deep learning. I started my career
in sales and key account management across Dubai and India, where I developed a sharp
instinct for operational problems and customer needs. That foundation led me toward data:
first building reporting systems and ETL pipelines at Nila Cares, then deepening my
technical skills through an MSc at CentraleSupélec and ESSEC, where I am currently
completing a deep learning research project with SLB on well-log formation classification.

I work across the full data stack: from pipeline architecture and SQL modelling to
computer vision, LLM-powered applications, and analytics dashboards. I am most energized
by problems where data engineering and real-world impact meet directly.

Currently seeking internship opportunities in data engineering, solutions engineering,
and analytics. Based in Paris. Open to hybrid and remote roles.

---

## Tech Stack

**Languages:** Python · SQL · R  
**Data & Analytics:** Pandas · NumPy · PostgreSQL · Metabase · NocoDB  
**Machine Learning:** PyTorch · Scikit-learn · YOLO · ResNet18  
**AI / LLM:** OpenAI API · RAG pipelines · Claude API · DistilBERT (LoRA fine-tuning)  
**Infrastructure:** ETL pipelines · Docker (learning) · GCP · Git  
**Viz & BI:** Metabase · Power BI · Matplotlib  

---

## Corporate Research Project — Well-Log Formation Classification · SLB (Schlumberger)

*MSc Capstone · CentraleSupélec / ESSEC in partnership with SLB · 2025 – 2026*

A deep learning research project tackling automated geological formation classification
from well-log data, in collaboration with SLB's data science team. The project addresses
a core challenge in subsurface analytics: classifying formations across the North Sea
(Hordaland, Rogaland, Shetland, Viking, Vestland) and Colorado datasets reliably and
at scale, reducing dependence on manual expert labeling.

**Supervised Segmentation Pipeline**
- Adapted YOLO11n with Focal Loss for well-log image segmentation, treating formation
  boundaries as a dense prediction problem across multi-channel log inputs.
- Trained and evaluated across North Sea and Colorado geological datasets, optimizing
  for class imbalance using Focal Loss to handle rare formation types.
- Built explainability layer using Guided Grad-CAM to surface which log features
  drive formation predictions, enabling geologist review and trust calibration.

**Hybrid Time-Series Architectures**
- Designed and benchmarked LSTM-FCN-2dCNN and LSTM-XCM hybrid architectures
  for sequential well-log classification, combining temporal modelling with
  convolutional feature extraction.
- Evaluated architectures across cross-well generalization tasks to assess
  robustness to geological variability between datasets.

**VLM-Based One-Shot Transfer Pipeline**
- Developed a vision-language model pipeline enabling one-shot transfer of formation
  classifications to new wells with minimal labeled data.
- Designed prompt logic and few-shot inference strategies to leverage VLM spatial
  reasoning for geology-specific pattern recognition.

**Infrastructure**
- Deployed training workloads on a GCP VM (N1, Tesla T4, 120 GB SSD) to accelerate
  deep learning experiments.
- Managed experiment tracking, versioning, and collaborative development via Git
  across a team of five researchers.

**Team:** Enora Barbier · Yann Djouka · Alessandro Ivashkevich · Faidon Kotsakis  
**SLB Contacts:** Shwetha Salimath · Sylvain Wlodarczyk

---

## Selected Projects

| Project | Description | Stack |
|--------|-------------|-------|
| [Greenwash Detector](https://github.com/georgee-17/Greenwash-detector) | RAG pipeline to detect corporate greenwashing at scale, built at the Ekimetrics AI Sustainability Hackathon | Python · OpenAI API · TypeScript |
| [Game State Reconstruction](https://github.com/georgee-17/GameStateReconstruction_FootballBroadcasts) | Computer vision pipeline for reconstructing football game state from broadcast footage | YOLO · ResNet18 · Jupyter |
| [CESAR Real Estate CLI](https://github.com/camille-desurmont/cesar-v1) | LLM-powered natural language CLI for Paris property search with undervaluation flagging | Python · Claude API · SQL |
| [Metabase Maps](https://github.com/georgee-17/metabase-maps) | Custom geospatial dashboards built in Metabase for operational analytics | Metabase · GeoJSON |
| [Recommendation System](https://github.com/georgee-17/eleven-Hackathon-RecommendationSystem) | Collaborative filtering recommendation engine built at a hackathon | Python |
| [MLOps](https://github.com/georgee-17/MLOps) | MLOps coursework covering model deployment and pipeline management | HTML · Python |

---

## Experience

**Data Analyst Intern · Nila Cares** — Migrated data architecture from Airtable to NocoDB,
built Python ETL pipelines, and engineered Metabase dashboards used for city expansion decisions.

**Key Account Manager · Waycool Foods** — Grew agri-export revenue by 350% to $500k/month,
built Excel-based live margin tracking system.

**Sales Development Associate · FarmUnboxed** — Data-driven sales forecasting that reduced
stockouts by 30%.

---

## Education

🎓 MSc Data Sciences & Business Analytics — CentraleSupélec / ESSEC *(2024 – 2026)*  
🎓 BA Economics, First Class Honours — University of Manchester *(2016 – 2019)*  

---

## Get in touch

📧 george.emmanuel@essec.edu  
💼 [LinkedIn](https://www.linkedin.com/in/george-emmanuel-92076813b/)
