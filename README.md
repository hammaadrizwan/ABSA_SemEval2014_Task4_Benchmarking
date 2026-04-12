# 🌱 Energy-Efficient NLP Benchmarking

## 📌 Overview

This repository presents a systematic evaluation of computational efficiency in Natural Language Processing (NLP), focusing on sentiment analysis tasks. The study benchmarks multiple models across standard datasets while jointly analyzing performance and resource consumption.

---

## 🎯 Scope of the Study

The experimental setup is defined as follows:

* **Models:**
  Five models representing different points on the computational efficiency spectrum.

* **Datasets:**
  Two benchmark domains from **SemEval-2014**:

  * Restaurant Reviews
  * Laptop Reviews

* **Statistical Robustness:**
  Each experiment is repeated with **three random seeds** to ensure reliability and reproducibility.

* **Evaluation Metrics:**
  The study measures five key metrics:

  * **Accuracy**
  * **Macro-F1 Score**
  * **Training Energy Consumption (kWh)**
  * **Inference Latency (ms/sample)**
  * **Peak Memory Usage (MB)**

---

## ⚙️ Reproducibility

To ensure full transparency and reproducibility, this repository provides:

* ✅ Complete source code
* ✅ Pretrained model checkpoints
* ✅ Experiment configurations
* ✅ Energy tracking logs using CodeCarbon

---

## 📊 Energy Measurement

Energy consumption is tracked using **CodeCarbon**, capturing:

* CPU/GPU power usage
* Carbon emissions (CO₂eq)
* Region-aware energy estimates

---

## 📈 Key Contributions

* First benchmarking study involving multiple ABSA systems evaluated on energy emission during training, overall model accuracy, and inference latency.
* This paper supports the findings mentioned in this paper (insert DOI here)

---

## 📜 License

This project is released under the MIT License.

---
