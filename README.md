# Anomaly Detection using ML & DL Techniques (Geographic and Lateral Movement) in UEBA

## 📌 Project Overview
This project focuses on enhancing cybersecurity measures through **User and Entity Behavior Analytics (UEBA)**. By analyzing network log data, the system detects sophisticated threats like lateral movement and geographic anomalies—indicators often missed by traditional rule-based systems.

The implementation utilizes a hybrid approach combining Machine Learning and Deep Learning architectures to robustly flag malicious or deviant user behaviors.

> **Context:** Developed during my cybersecurity internship at the **Centre for Development of Advanced Computing (C-DAC)**.

---

## 🚀 Key Achievements & Impact
* **Performance Boost:** Improved overall anomaly detection accuracy by **25%** compared to baseline legacy methods.
* **Proactive Security:** Applied user behavior profiling to identify geographic velocity anomalies (e.g., impossible travel) and internal lateral movement.
* **Big Data Experience:** Gained hands-on, practical experience in handling, preprocessing, and engineering features from complex, large-scale network log analytics.

---

## 🛠️ Tech Stack & Methodology
* **Language:** Python
* **Algorithms Implemented:**
  * **Isolation Forest (Machine Learning):** Utilized for fast, unsupervised isolation of anomalous data points in network logs.
  * **Autoencoders (Deep Learning):** Developed neural networks to reconstruct normal behavior sequences; high reconstruction errors successfully flag complex, non-linear anomalies.
* **Libraries:** `scikit-learn`, `tensorflow`/`keras` (or `pytorch`), `pandas`, `numpy`

---

## 📊 Core Workflow
1. **Data Ingestion:** Processing raw network logs and user activity streams.
2. **Feature Engineering:** Extracting behavioral metrics, contextual geographic data, and temporal vectors.
3. **Model Training:** Training models strictly on baseline "normal" behavior to ensure robust unsupervised anomaly scoring.
4. **Evaluation:** Testing against simulated lateral movement and anomalous access patterns to validate the 25% accuracy leap.

---

## 📂 File Structure
* `Last.ipynb` — Core Jupyter notebook containing data preprocessing, model architectures (Isolation Forest & Autoencoder), training loops, and evaluation metrics.
