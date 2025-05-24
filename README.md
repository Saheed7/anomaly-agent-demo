# anomaly-agent-demo
Anomaly Agent: LLM-Powered Anomaly Detection for IoT/IIoT
## Overview
This repository implements **Anomaly Agent**, an autonomous framework for explainable anomaly detection in IoT/IIoT networks. It combines lightweight ML models, SHAP explanations, and edge optimizations for real-time threat detection.

## Features
- Preprocessing with 8-bit quantization and SHAP-based feature selection.
- Multi-model inference (SVM, Random Forest, Naïve Bayes).
- SHAP-driven explanations for transparency.
- Gradio demo for interactive testing.

## Installation
```bash
git clone https://github.com/saheed7/Anomaly-Agent.git
cd Anomaly-Agent
pip install -r requirements.txt

Usage
1.	Google Colab: Open Anomaly_Agent_Demo.ipynb and run all cells.
2.	Local Execution:
python demo.py  # Custom script for CLI inference

Datasets
•	Edge-IIoTset: https://ieee-dataport.org/documents/edge-iiotset-new-comprehensive-realistic-cyber-security-dataset-iot-and-iiot-applications 
•	CIC-IoT2023: https://www.unb.ca/cic/datasets/iotdataset-2023.html
License
MIT License. See LICENSE for details.
