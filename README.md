<div align="center">

# Anurag Sharma

**B.Tech CSE (AI&ML) · 3rd Semester · Building LUCID: Reality?**

[![GitHub followers](https://img.shields.io/github/followers/anu-rag-007?style=flat&color=1D9E75&labelColor=0d1117)](https://github.com/anu-rag-007)
[![LeetCode](https://img.shields.io/badge/LeetCode-40%2B%20problems-FFA116?style=flat&logo=leetcode&logoColor=white)](https://leetcode.com/u/bNmEa5unUW/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat&logo=linkedin)](https://linkedin.com/in/anurag-sharma-2a8b3b371)

</div>

---

## About me

I'm a 3rd semester AI/ML student building a closed-loop
Brain-Computer Interface system that detects REM sleep
and triggers haptic stimulation for lucid dream induction.

I call the long-term vision **LUCID: Reality?** —
a dream interface where multiple people can share a
collaboratively generated world during sleep.
I call this technology **Artificial Reality**.

> *"When you are inside Artificial Reality, the question
> 'is this real?' becomes genuinely unanswerable."*

---

## Project 07 — LUCID: Reality?

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.21885881.svg)](https://doi.org/10.5281/zenodo.21885881)

Closed-loop BCI for automated lucid dream induction.
CNN-LSTM sleep stage classifier · κ=0.68 on 153 subjects · 
Working haptic trigger · **Published preprint**.

→ [Paper](https://doi.org/10.5281/zenodo.21885881)
→ [Code](https://github.com/anu-rag-007/PROJECT-07)

My primary research project. A complete BCI pipeline:
EEG signal → CNN-LSTM classifier → REM detection
→ safety interlock → haptic trigger
**Results so far (Sleep-EDF Cassette dataset):**

| Experiment | Architecture       | Accuracy | Kappa |
|------------|--------------------|----------|-------|
| 001        | SleepLSTM          | 76.85%   | —     |
| 002        | CNN Spectrograms   | 71.67%   | —     |
| 003        | CNN-LSTM Hybrid    | 80.14%   | 0.71  |
| 004        | CNN+Transformer    | 79.00%   | —     |
| 005        | LOSO Validation    | 77.17%   | 0.67  |
| 006        | Full 153 subjects   | 75.59%   | 0.68  |

**Tech stack:**
PyTorch · MNE-Python · scikit-learn · NumPy · SciPy

[![PROJECT-07](https://img.shields.io/badge/PROJECT--07-View%20Repo-534AB7?style=for-the-badge&logo=github)](https://github.com/anu-rag-007/PROJECT-07)

## Citation

If you use this work, please cite:

```bibtex
@misc{sharma2026lucid,
  author    = {Sharma, Anurag},
  title     = {Automated Sleep Stage Classification 
               for Closed-Loop Lucid Dream Induction 
               via CNN-LSTM on Single-Channel EEG},
  year      = {2026},
  publisher = {Zenodo},
  doi       = {10.5281/zenodo.21885881},
  url       = {https://doi.org/10.5281/zenodo.21885881}
}
```

---

## Skills

**Machine Learning**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)

**Deep Learning architectures I've implemented from scratch:**
- ✅ Neural networks (forward pass + backprop)
- ✅ CNNs — MNIST 98.47%, CIFAR-10
- ✅ LSTMs — sleep staging 80.14%
- ✅ Attention mechanisms
- ✅ Transformer encoder
- ✅ CNN-LSTM hybrid (BCI application)

**Signal Processing**

![MNE](https://img.shields.io/badge/MNE--Python-EEG%20Processing-blue?style=flat)

- EEG preprocessing (bandpass filter, epoch extraction)
- Sleep-EDF dataset (AASM standard staging)
- Real-time signal pipeline design

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat&logo=visualstudiocode&logoColor=white)
![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=flat&logo=kaggle&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

---

## Projects

### 🧠 PROJECT-07 — LUCID: Reality?
Closed-loop BCI for automated lucid dream induction.
CNN-LSTM sleep stage classifier · 80.14% accuracy · Working haptic trigger.
→ [github.com/anu-rag-007/PROJECT-07](https://github.com/anu-rag-007/PROJECT-07)

### 📊 Journey to the BEST
Complete ML learning journey — from Python basics to
transformers. 50 LeetCode solutions, weekly notebooks,
Kaggle projects (Titanic 78%), neural network from scratch.
→ [github.com/anu-rag-007/Journey-to-the-BEST](https://github.com/anu-rag-007/Journey-to-the-BEST)

### 🪴 Smart Irrigation System
Automatically detects soil dryness and waters the plant
— no human effort needed. It is a great way to nurture
plants keeping our resources in control and saving a hell
lot of water. Arduino . Environment . ECE
→ [github.com/anu-rag-007/smart_irrigation_system](https://github.com/anu-rag-007/smart_irrigation_system)

---

## Research interests
Brain-Computer Interfaces → the hardware of LUCID
EEG signal processing → reading the brain
Deep learning for biosignals → understanding the brain
AR / VR / XR → the delivery layer
Neural rendering (NeRF) → generating dream worlds
Generative AI → creating the content

---

## DSA

Solving the **Blind 75** list systematically.
Arrays & Hashmaps ████████████ ✅
Stack & Queue ████████████ ✅
Trees & Recursion ████████████ ✅
Sliding Window ████████████ ✅
Linked Lists ████████████ ✅
Graphs ████████████ ✅
Dynamic Programming ████████░░░░ in progress

**40+ problems solved · 7 core patterns**

---

## Currently working on

- 🔬 **Experiment 006** — Expanding Sleep-EDF to 153 subjects
- 📄 **Paper draft** — IEEE TNSRE submission preparation
- 💡 **Real-time pipeline** — Muse S integration plan
- 📚 **Week 9** of AI/ML self-study roadmap

---

## Vision

**LUCID: Reality?** is a 10-15 year research initiative
to create a shared dream interface —
a technology I call **Artificial Reality**.

Phase 1 (now): BCI classifier + lucid induction
Phase 2 (Year 2): Neural decoding + image generation
Phase 3 (Year 3): 3D world generation + navigation
Phase 4 (Year 5): Multi-user shared dream world
Phase 5 (Year 10): Full Artificial Reality platform

The dream: when multiple people can enter the same generated
world through sleep, indistinguishable from reality —
that is Artificial Reality.

---

## GitHub stats

<div align="center">

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anu-rag-007&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117&title_color=1D9E75&icon_color=534AB7&text_color=ffffff)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=anu-rag-007&layout=compact&theme=dark&hide_border=true&bg_color=0d1117&title_color=1D9E75&text_color=ffffff)

</div>

---

## Connect

- 📧 Email — sharma.anurag0706@gmail.com
- 🔗 LinkedIn — [linkedin.com/in/anurag-sharma-2a8b3b371](https://linkedin.com/in/anurag-sharma-2a8b3b371)
- 📊 Kaggle — [kaggle.com/anuragsharma07112006](https://kaggle.com/anuragsharma07112006)
- 🧪 Project 07 — [github.com/anu-rag-007/PROJECT-07](https://github.com/anu-rag-007/PROJECT-07)
- 🗜️ ORCid — [orcid.org/my-orcid?orcid=0009-0004-2479-2126](https://orcid.org/my-orcid?orcid=0009-0004-2479-2126)

---

<div align="center">

*Building the foundation of Artificial Reality.*
*One experiment at a time.*

</div>
