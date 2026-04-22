# 💊 DoseWise — Smart Drug Recommendation System

A machine learning-based web application that recommends suitable drugs for patients based on their **age** and **dosage requirements**. Built as a B.Tech Final Year Project to assist healthcare professionals in making faster, data-driven medication decisions.

---

## 🚀 Project Overview

This system takes patient-specific parameters — primarily **age** and **dosage** — and uses a trained machine learning model to recommend the most appropriate drugs. The project combines a Python-based ML backend with a clean web interface for ease of use.

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|------------|
| Data Analysis & ML | Python, Jupyter Notebook |
| Frontend | HTML, CSS, SCSS |
| Core Libraries | Pandas, NumPy, Scikit-learn |

---

## 📁 Project Structure

```
DoseWise/
│
├── Drug Recommendation/
│   ├── drug_recommendation.ipynb   # Core ML model and analysis
│   ├── index.html                  # Web interface
│   ├── styles/                     # SCSS and CSS styling
│   └── dataset/                    # Input data used for training
```

---

## ⚙️ How It Works

1. **Input** — User provides patient age and dosage requirement
2. **Processing** — The ML model analyzes the parameters against the trained dataset
3. **Recommendation** — System outputs a list of suitable drugs ranked by relevance
4. **Display** — Results are shown through a clean web interface

---

## 📊 Features

- 🔍 Age-based drug filtering
- 💉 Dosage-aware recommendations
- 🧠 Machine learning model trained on structured medical data
- 🌐 Simple and intuitive web interface
- 📓 Full data exploration and model training available in Jupyter Notebook

---

## 🧪 How to Run

### Prerequisites
```bash
pip install pandas numpy scikit-learn jupyter
```

### Steps
```bash
# 1. Clone the repository
git clone https://github.com/Shivasai03/DRUG-RECOMMENDATION-SYSTEM-BASED-ON-AGE-AND-DOSAGE.git

# 2. Navigate to the project folder (DoseWise)
cd DRUG-RECOMMENDATION-SYSTEM-BASED-ON-AGE-AND-DOSAGE/Drug\ Recommendation

# 3. Open the Jupyter Notebook
jupyter notebook drug_recommendation.ipynb

# 4. To view the web interface, open index.html in your browser
```

---

## 📌 Use Case

This system is designed to:
- Support healthcare professionals in quickly identifying appropriate medications
- Reduce manual lookup time for dosage-specific drug selection
- Demonstrate how ML can be applied to real-world healthcare problems

---

## 👨‍💻 Author

**Shiva Sai**
Master of Business Analytics | Ontario Tech University
🔗 [GitHub Profile](https://github.com/Shivasai03)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

> ⚠️ **Disclaimer:** This system is intended for academic and research purposes only. It should not be used as a substitute for professional medical advice.
