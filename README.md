# Comparative OCR Error Analysis

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/leake1617/comparative-OCR-error-analysis/blob/main/OCR_Analysis.ipynb)
![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Python](https://img.shields.io/badge/python-3.8%2B-brightgreen.svg)

This repository presents a comparative framework for analyzing and evaluating **Optical Character Recognition (OCR)** error patterns across multiple systems. The project focuses on understanding recognition errors using standard evaluation metrics to support performance comparison and improvement.

## 📖 Overview
OCR systems often exhibit varying error behaviors depending on data quality, scripts (such as Ethiopic/Ge'ez), and underlying models. This project provides tools and datasets to systematically analyze OCR outputs and compare systems based on their specific error characteristics.

## ✨ Key Features
* **Multi-System Evaluation:** Comparative analysis of different OCR engines.
* **Standardized Metrics:** Calculation of **CER** (Character Error Rate) and **WER** (Word Error Rate).
* **Confusion Analysis:** Tools to identify specific character-level confusion patterns (e.g., which characters are most frequently misidentified).
* **Reproducible Pipeline:** Clean, modular code designed to run in Google Colab for easy replication of results.

## 🚀 Getting Started

### Run via Google Colab
The easiest way to explore this analysis is through Google Colab. 
1. Click the **Open in Colab** badge at the top of this README.
2. Upload your OCR output files (ground truth and hypothesis text).
3. Run the cells sequentially to generate the error reports.

### Local Installation
If you prefer to run it locally:
```bash
git clone [https://github.com/leake1617/comparative-OCR-error-analysis.git](https://github.com/leake1617/comparative-OCR-error-analysis.git)
cd comparative-OCR-error-analysis
pip install -r requirements.txt
