# Dawon Lee

**Data Science Undergraduate | AI & Machine Learning**

[English](./README.md) | [한국어]

데이터사이언스를 전공하며 머신러닝과 딥러닝을 실제 문제에 적용하는 프로젝트를 진행하고 있습니다. 현재 **자연어처리, 컴퓨터 비전, 딥러닝, 멀티모달 AI** 분야에 관심을 두고 공부하고 있습니다.

프로젝트의 결과뿐 아니라 문제 정의, 모델링 과정, 실험과 개선 과정을 기록하는 포트폴리오를 만들어가고 있습니다.

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
**MuseTalk Lip-Sync Improvement** · 2026

MuseTalk을 기반으로 음성과 얼굴 영상의 lip-sync 개선을 실험하고, 입력부터 결과 영상 생성까지 확인할 수 있는 웹 기반 inference demo를 구축한 캡스톤 프로젝트입니다.

`Python` `Deep Learning` `Computer Vision` `MuseTalk`

- MuseTalk v1.0 baseline 구축 및 inference 검증
- Lip-Centric 모델 개선 실험 및 결과 분석
- Reference image + audio 기반 End-to-End inference 연동
- Python 기반 Web Demo 개발

**Repository:** [dawon-ds/musetalk-lipsync-improvement](https://github.com/dawon-ds/musetalk-lipsync-improvement)

---

### 🗣️ PhonoTrans
**Japanese Pronunciation-based Translation** · 2025

일본어를 듣고 이해할 수 있지만 원문을 입력하기 어려운 사용자를 위해, **한글로 적은 일본어 발음에서 한국어 의미를 직접 예측**하는 번역 모델을 개발한 프로젝트입니다.

`Python` `Seq2Seq` `Attention` `NLP` `Data Augmentation`

- 약 24만 문장 규모의 일본어 발음·한국어 의미 데이터 활용
- 초기 다단계 번역 구조의 오류 전파 문제 분석
- Hangul pronunciation → Korean meaning End-to-End 구조로 재설계
- 발음 노이즈, Random Substitution, Random Drop 기반 데이터 증강 실험
- 최종 발표 모델 BLEU **0.5276**

**Repository:** [dawon-ds/phonotrans](https://github.com/dawon-ds/phonotrans)

---

### 💬 Korean Hate Speech Detection
**Multi-label NLP Classification** · 2025

한국어 온라인 텍스트의 혐오 표현을 Multi-label로 분류하고, HITL 데이터와 Lexicon 기반 Augmentation이 모델 성능과 강건성에 미치는 영향을 비교한 NLP 프로젝트입니다.

`Python` `BERT` `ELECTRA` `RoBERTa` `NLP`

- UnSmile + HateScore 데이터셋 활용
- Korean PLM 기반 Multi-label classification 비교
- Hybrid Lexicon 및 robustness-oriented augmentation 적용
- Flat / Hierarchical classification 구조 비교
- Abusive chat filtering Web Demo 구현

**Repository:** [dawon-ds/korean-hate-speech-detection](https://github.com/dawon-ds/korean-hate-speech-detection)

---

### 🏥 Patient Mortality Factor Analysis
**Clinical Data Visualization & Modeling** · 2024

심정지 환자 데이터를 분석해 환자 사망과 연관된 주요 임상 요인을 탐색하고, 시각화와 분류 모델을 통해 패턴을 분석한 프로젝트입니다.

`Python` `Data Analysis` `Visualization` `Logistic Regression`

- 2,005명 환자의 임상 데이터 통합 및 전처리
- 활력징후·검사·약물·처치 관련 변수 탐색
- 극단값 기준 Feature Engineering
- Logistic Regression 기반 사망 위험 분류
- ROC-AUC 약 **0.605** 및 주요 사망 연관 변수 분석

**Repository:** [dawon-ds/patient-mortality-analysis](https://github.com/dawon-ds/patient-mortality-analysis)

---

## Currently Learning

`Graph Neural Networks` · `Natural Language Processing` · `Retrieval-Augmented Generation` · `Deep Learning`

---

## Portfolio

각 프로젝트 Repository에 코드, 실행 방법, 모델 및 분석 과정, 실험 결과와 회고를 순차적으로 정리하고 있습니다.
