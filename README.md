# 📚 Curriculum Intelligence Engine

An NLP-powered system for analyzing university curriculum documents using **Bloom Taxonomy classification**, **hybrid retrieval**, and **prerequisite extraction**.

---

## 🚀 Features

- 📖 Bloom Taxonomy Classification (Levels 1–6)
- 🔍 Hybrid Document Retrieval
- 🔗 Prerequisite Extraction
- 📊 Quantitative Evaluation
- 🧪 Robustness Testing
- ❌ Error Analysis
- 📈 Curriculum Analytics

---

## 📂 Project Structure

```
├── data/
├── results/
├── src/
├── README.md
└── requirements.txt
```

---

# ✅ Week 5 – Evaluation & Error Analysis

### Objectives
- Quantitative evaluation
- Test set evaluation
- Error analysis
- Robustness testing
- Failure case analysis

### Results

| Metric | Value |
|--------|-------|
| Bloom Accuracy | **73.3%** |
| Bloom Macro-F1 | **0.658** |
| Prerequisite Rule F1 | **0.784** |
| Failure Cases | **15** |

### Deliverables
- ✔ Evaluation metrics (`w5_metrics.json`)
- ✔ Bloom confusion matrix (`fig_w5_bloom_confusion.png`)
- ✔ Robustness analysis (`w5_robustness.csv`)
- ✔ Error cases (`w5_error_cases.csv`)

### Key Findings
- Strong Bloom classification performance with **73.3% accuracy**.
- Most prediction errors occur between adjacent Bloom levels.
- Prerequisite extraction achieves high recall with room for precision improvement.
- Robustness testing shows the system is stable for formatting changes but sensitive to some text variations.

---

# 🔄 Week 6 – Asset Engineering

**Target:** 16 October

The next phase focuses on converting the NLP pipeline into a reusable software asset.

### Planned Work
- Develop a reusable **API/module**
- Implement **structured JSON input/output**
- Add **confidence scores** for predictions
- Improve project **documentation**
- Refactor code into reusable components

### Deliverable
A fully documented, reusable NLP asset that can be integrated into external applications.

---

## 🛠 Tech Stack

- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- NLP & Information Retrieval

---

## 📌 Future Improvements

- Transformer-based Bloom Classification
- Semantic Retrieval
- Vector Database Integration
- Knowledge Graph Generation
- Interactive Curriculum Dashboard
