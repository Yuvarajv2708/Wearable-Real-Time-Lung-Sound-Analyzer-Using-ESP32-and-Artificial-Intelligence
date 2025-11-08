# Wearable Real-Time Lung Sound Analyzer Using ESP32 and AI

A proof-of-concept system for ambulatory respiratory health monitoring using commodity hardware and machine learning.

## 🎯 Overview

This project integrates an ESP32 microcontroller with an omnidirectional microphone to create an affordable wearable device for real-time lung sound analysis. Using MFCC-based feature extraction and Random Forest classification trained on the public CoughVID v3 dataset, the system achieves 72% accuracy with sub-second latency suitable for point-of-care and telemedicine applications.

## 📊 Key Results

- **Accuracy**: 72% (test set, 528 samples)
- **Sensitivity**: 100% (abnormal detection rate)
- **Latency**: 0.82 ± 0.11 seconds
- **Battery Life**: 10+ hours continuous operation
- **Cost**: USD 50-100 (vs. USD 500-5000 commercial devices)

## 🏗️ System Architecture

