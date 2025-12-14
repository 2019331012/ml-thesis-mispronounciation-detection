# Phoneme-Level Mispronunciation Detection System

This repository contains my **undergraduate thesis project**, which presents an end-to-end **machine learning–based system for phoneme-level mispronunciation detection** in non-native speech. The goal of the project is to build an interpretable and practical pronunciation assessment system that can be applied in **low-resource and real-world settings**.

## Problem Statement
Automatic pronunciation assessment systems often provide only word- or utterance-level feedback, which limits their usefulness for language learners. This project focuses on detecting **phoneme-level mispronunciations**, enabling more fine-grained and actionable feedback.

## System Overview
The system follows a modular ML pipeline:

1. **Speech–Text Alignment** using Montreal Forced Aligner (MFA) to obtain precise phoneme boundaries  
2. **Feature Extraction** using Wav2Vec2-based acoustic representations  
3. **Pronunciation Scoring** using GOP/GOPT-based methods  
4. **Inference Pipeline** integrated through a FastAPI-based backend

## Tools & Technologies
- Python  
- Wav2Vec2 (self-supervised speech representations)  
- Montreal Forced Aligner  
- GOP / GOPT scoring  
- FastAPI  
- PyTorch  
- NumPy / Pandas  

## Key Contributions
- Designed an **end-to-end phoneme-level pronunciation assessment pipeline**  
- Evaluated multiple alignment strategies and selected MFA based on accuracy and robustness  
- Implemented interpretable GOP-based scoring for mispronunciation detection  
- Structured the system to be **language-agnostic and adaptable to low-resource scenarios**

## Results
The system demonstrates reliable phoneme-level alignment and scoring, providing interpretable pronunciation feedback suitable for language learning applications.

## Repository Contents
- `Thesis.pdf` – Full thesis document  
- Source code for alignment, feature extraction, and scoring  
- Configuration and evaluation scripts  

## Notes
This work was completed as part of my **undergraduate thesis** and is not a published paper. The repository is intended to demonstrate applied machine learning and software engineering skills.
