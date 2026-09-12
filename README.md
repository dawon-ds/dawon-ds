# Dawon Lee

**Data Science Undergraduate | AI & Machine Learning**

[English] | [한국어](./README_KR.md)

I am a Data Science undergraduate interested in applying machine learning and deep learning to real-world problems. My current interests include **Natural Language Processing, Computer Vision, Deep Learning, and Multimodal AI**.

I am building this GitHub portfolio to document my projects, experiments, and learning process as I prepare for further study in data science and artificial intelligence.

---

## Technical Skills

**Programming**  
`Python`

**Data Analysis**  
`Pandas` `NumPy` `Matplotlib`

**Machine Learning / Deep Learning**  
`scikit-learn` `TensorFlow` `Keras` `PyTorch`

**Areas of Interest**  
`Natural Language Processing` `Computer Vision` `Deep Learning` `Multimodal AI` `Graph Neural Networks`

---

## Selected Projects

### 🎙️ Audio-Driven Talking-Head Generation
**MuseTalk-based Talking-Head Generation** · 2026

A MuseTalk-based project for audio-driven talking-head generation, combining lip-centric latent refinement, audio-visual synchronization supervision, training/inference workflows, and a web demo.

`Python` `PyTorch` `Computer Vision` `MuseTalk` `Whisper`

- Built and validated MuseTalk training and normal/realtime inference workflows
- Implemented an ADLip Generator with Spatial Cross-Attention, Temporal Attention, and residual latent updates
- Integrated SyncNet / SyncLT-based synchronization supervision
- Connected reference media and audio to an end-to-end generation pipeline and Gradio demo

**Repository:** [dawon-ds/audio-driven-talking-head-generation](https://github.com/dawon-ds/audio-driven-talking-head-generation)

---

### 🗣️ PhonoTrans
**Japanese Pronunciation-based Translation** · 2025

A Japanese translation system that allows users unfamiliar with Japanese to enter what they hear phonetically in Hangul and receive the corresponding Korean meaning.

`Python` `PyTorch` `Seq2Seq` `Attention` `NLP`

- Built a dataset of approximately **245K** Japanese pronunciation–Korean meaning pairs
- Analyzed error propagation in an initial multi-stage translation pipeline
- Redesigned the system as an end-to-end Hangul pronunciation → Korean meaning model
- Experimented with pronunciation noise, random substitution, and random drop augmentation
- Final presentation model reported **BLEU 0.5276**

**Repository:** [dawon-ds/phonotrans](https://github.com/dawon-ds/phonotrans)

---

### 💬 Korean Hate Speech Detection
**Multi-label NLP Classification** · 2025

A Korean NLP project for multi-label hate-speech classification, examining PLM selection, HITL data, robustness-oriented augmentation, and flat vs. hierarchical modeling.

`Python` `PyTorch` `BERT` `ELECTRA` `RoBERTa`

- Used the UnSmile and HateScore datasets
- Compared Korean pretrained language models for hate-speech classification
- Constructed a hybrid lexicon and robustness-oriented text augmentation pipeline
- Compared flat and hierarchical coarse/fine prediction structures
- Recorded best final **Coarse Macro F1 0.7415** and **Fine Macro F1 0.7292** with Hierarchical + Augmentation

**Repository:** [dawon-ds/korean-hate-speech-detection](https://github.com/dawon-ds/korean-hate-speech-detection)

---

### 🏥 Patient Mortality Factor Analysis
**Clinical Data Visualization & Modeling** · 2024

A clinical data analysis project exploring factors associated with mortality among cardiac-arrest patients through exploratory analysis, feature engineering, visualization, and classification modeling.

`Python` `Data Analysis` `Visualization` `Logistic Regression`

- Integrated and preprocessed clinical data from **2,005 patients**
- Explored vital signs, laboratory tests, medications, and treatment-related variables
- Engineered threshold-based features for mortality-factor analysis
- Applied logistic regression to mortality classification
- Achieved an ROC-AUC of approximately **0.605** and interpreted major mortality-associated factors

**Repository:** [dawon-ds/patient-mortality-analysis](https://github.com/dawon-ds/patient-mortality-analysis)

---

## Currently Learning

`Graph Neural Networks` · `Natural Language Processing` · `Retrieval-Augmented Generation` · `Deep Learning`

---

## Portfolio

Each project repository documents the problem, methodology, implementation, experiments, results, and limitations where source materials are available.
