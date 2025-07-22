# 🧾 SamvidhanAI – AI-Based Legal Contract Generator

**SamvidhanAI** is an NLP-based automation tool for generating legal contracts using rule-based text extraction and dynamic templating. It aims to reduce the manual workload, legal costs, and inconsistencies in legal document drafting.

---

## 🚩 Problem Statement

Legal contract drafting is traditionally:
- ⌛ Time-consuming
- 💸 Costly for startups and small businesses
- 🧠 Prone to human error
- 📈 Difficult to scale

---

## 🎯 Objective

To automate contract creation using NLP techniques by:
- Extracting key legal entities using rule-based Named Entity Recognition (NER)
- Dynamically inserting those entities into pre-defined legal templates

---

## 🔍 Real-World Use Cases

- Startups: Quick NDAs, employment & partnership contracts
- HR Departments: Bulk employee agreement generation
- Real Estate: Automated lease agreement creation
- E-commerce & SaaS: Scalable subscription terms

---

## 🧠 NLP Workflow

1. **Data Collection**  
   - Dataset: CaseHOLD (legal decisions & MCQs)

2. **Text Preprocessing**  
   - Tokenization, stop-word removal, punctuation stripping

3. **Named Entity Recognition (NER)**  
   - Libraries: `spaCy`, `NLTK`, `Regex`  
   - Extracts: `PARTIES`, `DATES`, `PAYMENT TERMS`, `DURATION`, `JURISDICTION`

4. **Template Generation**  
   - Tool: `Jinja2`  
   - Pre-designed legal templates dynamically filled with extracted entities

---

## ⚙️ Technologies Used

| Category          | Tool/Library        |
|------------------|---------------------|
| Language          | Python              |
| NLP               | spaCy, NLTK, Regex  |
| Template Engine   | Jinja2              |
| Dataset           | CaseHOLD            |
| Others            | Pandas, Re          |

---

## 🧪 Evaluation Metrics

- 📈 Precision/Recall for NER accuracy
- ⚡ Contract generation time
- 📊 Feedback from legal professionals

---

## 📌 Novelty

- ✅ Rule-based, interpretable NLP (no black-box LLMs)
- ✅ Lightweight and cost-efficient
- ✅ Domain-specific template customization

---

