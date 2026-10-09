 <div align="center">

# Anurag Sharma

### AI/ML Developer · Research-Oriented Builder · B.Tech CSE (AI & ML)

**Building intelligent systems at the intersection of AI, neuroscience, and human experience.**

[![GitHub](https://img.shields.io/badge/GitHub-anu--rag--007-181717?style=flat-square\&logo=github)](https://github.com/anu-rag-007)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square\&logo=linkedin)](https://www.linkedin.com/in/anurag-sharma-2a8b3b371)
[![LeetCode](https://img.shields.io/badge/LeetCode-Practice-FFA116?style=flat-square\&logo=leetcode\&logoColor=black)](https://leetcode.com/u/bNmEa5unUW/)
[![Research](https://img.shields.io/badge/Research-LUCID-534AB7?style=flat-square)](https://github.com/anu-rag-007/PROJECT-07)

</div>

---

## About Me

I'm Anurag Sharma, a B.Tech Computer Science student specializing in Artificial Intelligence and Machine Learning.

I believe the best way to understand technology is to build it, experiment with it, measure its performance, and understand why it works.

My journey began with Python, mathematics, data analysis, and classical machine learning. It gradually expanded into neural networks implemented from scratch, computer vision, Transformers, generative AI, and EEG-based research.

Today, my work spans three interconnected areas:

* **AI Engineering:** Building practical AI applications, APIs, dashboards, and automated workflows.
* **Machine Learning Research:** Experimenting with deep learning architectures, EEG signals, multimodal representation learning, and model evaluation.
* **Neurotechnology:** Exploring how brain-computer interfaces and AI could eventually enable new forms of human-computer interaction.

My long-term research vision is **LUCID: Reality?** — an exploration of AI-assisted dream interaction and the possibility of what I call *Artificial Reality*.

> "When you are inside Artificial Reality, the question 'is this real?' becomes genuinely unanswerable."

---

## Featured Projects

### 1. LUCID: Reality? — PROJECT-07

**My primary research project.**

[![Phase 1 Paper](https://img.shields.io/badge/Phase%201-Published%20Research-534AB7?style=flat-square)](https://doi.org/10.5281/zenodo.21885881)
[![Phase 2 Paper](https://img.shields.io/badge/Phase%202-Published%20Research-0A7F5A?style=flat-square)](https://doi.org/10.5281/zenodo.23097798)
[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square\&logo=python\&logoColor=white)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square\&logo=pytorch\&logoColor=white)](https://pytorch.org/)

LUCID: Reality? is a long-term research initiative exploring the intersection of EEG, sleep-stage classification, brain-computer interfaces, and generative AI.

PROJECT-07 develops two foundational research directions.

**Phase 1 — EEG Sleep-Stage Classification and REM Detection**

A deep-learning pipeline that processes EEG signals, predicts sleep stages, identifies REM-related activity, and connects detection decisions to a haptic stimulation prototype.

```text
EEG Signal
    ↓
Signal Preprocessing
    ↓
Sleep-Stage Classification
    ↓
REM Detection
    ↓
Decision & Safety Logic
    ↓
Android Haptic Trigger
```

Key work:

* EEG preprocessing using MNE-Python.
* LSTM and CNN-LSTM sleep-stage classification.
* REM probability estimation and temporal smoothing.
* Decision logic designed to reduce inappropriate stimulation.
* Android vibration triggering through the JOIN API.
* Experimental evaluation, research documentation, and reproducibility.

**Selected documented results:**

* Baseline sleep-stage classifier: 76.85% accuracy.
* CNN-LSTM experiment: 80.14% accuracy in its documented evaluation.
* REM recall: 84% in the documented baseline evaluation.
* Expanded Sleep-EDF experiments include a separate 153-subject evaluation reporting Cohen's κ = 0.68.

Results refer to different experiments and evaluation configurations; they should not be interpreted as one combined benchmark.

📄 [Read the Phase 1 paper](https://doi.org/10.5281/zenodo.21885881)

**Phase 2 — EEG-to-CLIP Contrastive Alignment**

The next research direction investigates whether EEG representations can be aligned with visual representations learned by CLIP.

Key work:

* Exploration of the THINGS-EEG dataset.
* An attention-based EEG encoder using 17-channel inputs.
* Alignment of EEG representations with 512-dimensional CLIP embeddings.
* Experiments comparing image and text targets, training temperatures, and channel configurations.
* Evaluation through retrieval metrics and research figures.

Selected documented result: image-target alignment achieved a Top-5 retrieval rate of 4.5%, approximately 1.8 times the stated chance baseline.

📄 [Read the Phase 2 paper](https://doi.org/10.5281/zenodo.23097798)

**Technology stack:** Python, PyTorch, MNE-Python, NumPy, SciPy, scikit-learn, EEG signal processing, LSTMs, CNNs, attention mechanisms, and contrastive learning.

🔗 **Repository:** [PROJECT-07](https://github.com/anu-rag-007/PROJECT-07)

---

### 2. AcciSense — Autonomous Emergency Response & Escalation

An emergency-response system designed to reduce delays in coordinating traffic accident response.

AcciSense combines an incident-management backend, a frontend dashboard, database-backed incident records, and automated notification workflows.

**Core workflow:**

```text
Accident Report / Image
          ↓
Incident Processing
          ↓
Severity & Priority Assessment
          ↓
Incident Record Creation
          ↓
Automated Responder Notifications
          ↓
Acknowledgement Monitoring
          ↓
Escalation if Unacknowledged
          ↓
Incident Tracking & Audit
```

Key implementation work:

* FastAPI backend and REST API integration.
* Frontend incident dashboard.
* Supabase-backed incident records and lifecycle tracking.
* n8n workflow automation.
* Telegram acknowledgement and escalation handling.
* Email notifications and integration with additional notification channels.
* Incident severity, priority, status, and location handling.
* Testing, debugging, and Git-based project management.

The system is designed around state-aware escalation: an incident should not remain unattended simply because the initial notification was not acknowledged.

AI-based severity analysis is an evolving part of the project; prototype capabilities should be distinguished from independently validated model performance.

🔗 **Repository:** [AcciSense](https://github.com/anu-rag-007/AcciSense)

**Technology stack:** Python, FastAPI, JavaScript, Supabase, n8n, REST APIs, Telegram integration, and Git.

---

### 3. CinU — Identity Verification & Blockchain Integrity

CinU explores a verification workflow that combines face-based matching, online information discovery, and blockchain-oriented integrity verification.

The broader objective is to connect identity-related evidence with cryptographic fingerprints so that recorded information can be checked for subsequent changes.

Areas of development:

* Face analysis using InsightFace.
* Python-based processing pipelines.
* Web and social-platform information discovery.
* Cryptographic hashing and record verification.
* Polygon Amoy blockchain integration.

The project explores the distinction between finding matching information and verifying the integrity of a recorded artifact.

🔗 **Repository:** [CinU](https://github.com/anu-rag-007/CinU)

---

### 4. Journey-to-the-BEST — My AI/ML Learning Journey

This repository documents my progression from programming and mathematical foundations to modern deep learning and research-oriented AI.

Rather than collecting only tutorials, I use it to record implementations, experiments, evaluation results, and lessons learned.

**Learning progression:**

```text
Python & Data Handling
        ↓
NumPy, Mathematics & Statistics
        ↓
Classical Machine Learning
        ↓
Neural Networks from Scratch
        ↓
PyTorch & Computer Vision
        ↓
Transfer Learning & Object Detection
        ↓
LSTMs, Attention & Transformers
        ↓
LLMs & Generative AI
        ↓
EEG & Multimodal Learning
        ↓
Research-Oriented AI Systems
```

Selected milestones:

* Neural networks implemented with NumPy and PyTorch.
* MNIST test accuracy of 97.88% with the documented NumPy implementation.
* MNIST test accuracy of 98.47% with the documented PyTorch implementation.
* CNN architecture and CIFAR-10 experiments.
* Transfer learning, fine-tuning, Grad-CAM, and object detection.
* LSTMs, attention mechanisms, Transformer encoders, and LLM APIs.
* EEG preprocessing, CLIP embedding alignment, and research-oriented experiments.

🔗 **Repository:** [Journey-to-the-BEST](https://github.com/anu-rag-007/Journey-to-the-BEST)

---

### 5. Smart Irrigation System

An embedded-systems project designed to detect soil dryness and automate plant watering, helping reduce unnecessary water usage and manual intervention.

🔗 [View repository](https://github.com/anu-rag-007/smart_irrigation_system)

### 6. Qwiky

A separate software project in my development portfolio.

🔗 [View repository](https://github.com/anu-rag-007/Qwiky)

---

## Technical Skills

### Programming Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square\&logo=python\&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square\&logo=cplusplus\&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square\&logo=mysql\&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square\&logo=javascript\&logoColor=black)

### Machine Learning & Deep Learning

![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square\&logo=numpy\&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square\&logo=pandas\&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square\&logo=scikitlearn\&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square\&logo=pytorch\&logoColor=white)

* Neural networks, forward propagation, and backpropagation.
* CNNs, LSTMs, attention mechanisms, and Transformers.
* Classical ML, model evaluation, and experimentation.
* Transfer learning and computer vision.
* Generative AI, CLIP embeddings, and multimodal learning.

### AI Research & Neurotechnology

* EEG preprocessing and signal analysis.
* Sleep-stage classification and REM detection.
* Brain-computer interface concepts.
* EEG-to-CLIP representation alignment.
* Experimental design, evaluation, and research documentation.

### Backend & Application Development

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square\&logo=fastapi\&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square\&logo=supabase\&logoColor=black)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square\&logo=git\&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square\&logo=github\&logoColor=white)

* REST API development and integration.
* Database-backed application development.
* Workflow automation with n8n.
* Frontend integration and incident dashboards.
* Testing, debugging, and version control.

---

## My Learning Journey

My learning process is organized around building progressively more complex systems.

| Stage               | Focus                                    | Outcome                                           |
| ------------------- | ---------------------------------------- | ------------------------------------------------- |
| Foundations         | Python, NumPy, statistics, probability   | Stronger programming and mathematical foundations |
| Classical ML        | Regression, classification, pipelines    | Understanding data-driven modeling                |
| Deep Learning       | Neural networks, CNNs, PyTorch           | Implementing and evaluating neural architectures  |
| Modern AI           | Attention, Transformers, LLMs            | Exploring contemporary AI systems                 |
| Applied Engineering | APIs, databases, automation, dashboards  | Building integrated software applications         |
| Research            | EEG, sleep staging, multimodal alignment | Developing and evaluating research hypotheses     |
| Long-term Vision    | BCI, dream imagery, Artificial Reality   | Exploring new forms of human-computer interaction |

For the detailed week-by-week record, experiments, and notebooks, visit [Journey-to-the-BEST](https://github.com/anu-rag-007/Journey-to-the-BEST).

---

## Research Interests

My current and long-term interests include:

* **Brain-Computer Interfaces:** Connecting neural signals with computational systems.
* **EEG Signal Processing:** Extracting useful representations from brain activity.
* **Deep Learning for Biosignals:** Studying temporal patterns in physiological data.
* **Multimodal AI:** Aligning information across different data modalities.
* **Generative AI:** Exploring models that create images and other representations.
* **Neural Rendering:** Investigating NeRF and 3D scene generation.
* **Human-AI Interaction:** Designing systems that connect AI capabilities with real-world experiences.
* **Neurotechnology:** Exploring research directions at the intersection of AI and human cognition.

---

## LUCID: Reality? — The Long-Term Vision

The long-term goal behind LUCID: Reality? is to investigate whether brain-computer interfaces, sleep-stage detection, neural decoding, and generative models could eventually contribute to dream interaction.

I refer to this broader idea as **Artificial Reality**.

The research vision is organized into several conceptual stages:

1. **Sleep-stage understanding:** Develop and evaluate EEG-based sleep classifiers.
2. **Closed-loop interaction:** Investigate REM detection and controlled haptic stimulation.
3. **Neural representation learning:** Explore relationships between EEG signals and visual representations.
4. **Dream imagery research:** Investigate whether neural representations can support image-related reconstruction.
5. **Immersive environments:** Explore the possibility of translating visual representations into navigable 3D environments.
6. **Shared experiences:** Consider the much longer-term possibility of multi-user generated dream environments.

These stages are a research vision, not claims of completed capabilities. The work is experimental, and every future step depends on scientific validation, technical feasibility, and appropriate safety considerations.

---

## Development Philosophy

I believe meaningful progress comes from understanding both successful and unsuccessful experiments.

My approach is:

**Learn → Implement → Experiment → Evaluate → Document → Improve**

I try to understand the mathematics behind an architecture instead of treating a framework as a black box. I also value reproducibility, honest evaluation, clear documentation, and distinguishing demonstrated results from future ambitions.

A project does not need to solve every problem to be valuable. It should help answer a question, develop a skill, or establish a foundation for the next experiment.

> A failed experiment is still progress if I understand why it failed.

---

## GitHub Activity

<div align="center">

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anu-rag-007\&show_icons=true\&theme=github_dark\&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=anu-rag-007\&layout=compact\&theme=github_dark\&hide_border=true)

![GitHub Streak](https://streak-stats.demolab.com?user=anu-rag-007\&theme=github-dark-blue\&hide_border=true)

</div>

---

## Connect With Me

* **GitHub:** [anu-rag-007](https://github.com/anu-rag-007)
* **LinkedIn:** [Anurag Sharma](https://www.linkedin.com/in/anurag-sharma-2a8b3b371)
* **LeetCode:** [My profile](https://leetcode.com/u/bNmEa5unUW/)
* **Kaggle:** [Anurag Sharma](https://www.kaggle.com/anuragsharma07112006)
* **Research — Phase 1:** [Automated Sleep Stage Classification](https://doi.org/10.5281/zenodo.21885881)
* **Research — Phase 2:** [EEG-to-CLIP Contrastive Alignment](https://doi.org/10.5281/zenodo.23097798)

---

<div align="center">

### Building the foundation of Artificial Reality.

*One experiment at a time.*

</div>
