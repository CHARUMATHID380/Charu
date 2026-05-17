# Machine Learning Techniques for Phishing Attack Identification  
*A Comprehensive Approach of Evaluating Classifiers on Real-World URLs*

## 📄 Overview
Phishing websites are a fast-growing cyber threat, often bypassing traditional blacklist and rule-based security systems.  
This project presents a **machine learning-based detection framework** designed to identify malicious URLs using lexical features, domain metadata, and behavioral signals.  

The study evaluates multiple classifiers on a large dataset of ~737,000 URLs and demonstrates that **ensemble methods, especially Random Forest, achieve superior accuracy (96%)** and resilience against adversarial evasion.

---

## 👩‍💻 Authors
- Prof. Emilin Shyni C – HOD (AI & ML), EPCET  
- Charumathi D – Student (AI & ML), EPCET  
- D Varsha – Student (AI & ML), EPCET  
- Deeksha S Shetty – Student (AI & ML), EPCET  
- Lakshitha Loganathan – Student (AI & ML), EPCET  

---

## 🛠️ Methodology
1. **Dataset Integration**  
   - Malicious URL Dataset (651,191 URLs)  
   - ISCX-URL2016 (165,366 URLs)  
   - Additional phishing repositories  

2. **Preprocessing & Feature Engineering**  
   - Lexical features (URL length, entropy, subdomains, HTTPS usage)  
   - Domain-based features (age, DNS records, traffic ranking)  
   - SMOTE oversampling to balance phishing vs. benign classes  

3. **Model Training & Evaluation**  
   - Classifiers: Logistic Regression, SVM, Naïve Bayes, KNN, Decision Trees, Random Forest, Gradient Boosting, Extra Trees  
   - Ensemble Learning: Stacking & Soft Voting  

---

## 📊 Results
- **Random Forest** achieved the highest performance:  
  - Accuracy: **95%**  
  - Precision: **96%**  
  - Recall: **95%**  
  - F1-Score: **0.96**  

- Ensemble Classifier (Soft Voting) provided robust predictions with F1-Score: **0.92**.  

---

## 🔐 Key Contributions
- Demonstrated the effectiveness of **tree-based ensemble models** for phishing detection.  
- Showed that **feature engineering + SMOTE balancing** significantly improves generalization.  
- Provided a scalable framework for **real-time phishing URL detection**.  

---

## 📌 Citation
If you use this work, please cite:  
*Charumathi D, Varsha D, Deeksha S Shetty, Lakshitha Loganathan, Prof. Emilin Shyni C. "Machine Learning Techniques for Phishing Attack Identification: A Comprehensive Approach of Evaluating Classifiers on Real-World URLs." EPCET, 2026.*

---

## 🚀 Future Work
- Incorporating **deep learning architectures** (Transformers, CNNs, LSTMs) for dynamic feature extraction.  
- Enhancing **adversarial robustness** with perturbation-resilient training.  
- Deploying **cloud-native microservices** for scalable, real-time phishing detection.  

---

## 📂 Repository Contents
- `paper.pdf` – Full journal paper  
- `README.md` – Summary of the work  
- `notebooks/` – Jupyter notebooks for preprocessing, training, and evaluation  
- `datasets/` – Sample phishing and benign URL datasets  
- `results/` – Performance metrics and confusion matrices  

---

## 🛡️ License
This repository is for academic and research purposes. Please check journal copyright policies before redistributing the full paper.
