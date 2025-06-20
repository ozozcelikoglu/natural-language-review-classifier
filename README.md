# Natural Language Review Classifier

This repository contains a coursework project developed for the Applied Natural Language Processing (ANLP) module. It implements review classification using simple wordlist-based and probabilistic (Naive Bayes) models. The project includes exploratory analysis, classifier design, performance evaluation, and experimental comparison.

---

## 📌 Project Overview

The objective of this assignment is to:
- Identify key content words from review data,
- Build wordlist and Naive Bayes classifiers,
- Evaluate performance using accuracy, precision, recall, and F1 score,
- Compare the models through experimentation,
- Discuss results, draw insights, and explain limitations.

The notebook follows a research-style approach with markdown discussions, Python implementations, and visualized results.

---

## 📂 Files

- `ANLPassignment2024-1.ipynb`: The complete Jupyter Notebook with all code, visualizations, and markdown responses.
- `ANLPmarkingguidelines.pdf`: Marking guide provided for the coursework.
- Additional data and outputs are assumed to be embedded or referenced in the notebook.

---

## 🛠️ Technologies & Methods

| Technology | Purpose |
|------------|---------|
| Python (3.x) | Main programming language |
| Jupyter Notebook | Interactive code and report platform |
| NLTK | Naive Bayes implementation and text preprocessing |
| Scikit-learn | Metric calculations and performance analysis |
| Matplotlib / Seaborn | Graphs and visualizations (where used) |

### Key Methods Used:
- Tokenization and stopword filtering
- Manual and frequency-based wordlist creation
- Rule-based classification (wordlist matching)
- Naive Bayes classification
- Performance metrics: Accuracy, Precision, Recall, F1 Score
- Experimental design (changing wordlist size)
- Comparative analysis of classifiers

---

## 📊 Example Outputs

- Top 10 content words for positive and negative reviews
- Wordlist-based binary classification
- Precision, recall and F1 score comparison
- Performance variation with different wordlist lengths

---

## 📚 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/natural-language-review-classifier.git
   ```
2. Open the Jupyter notebook:
   ```bash
   jupyter notebook ANLPassignment2024-1.ipynb
   ```
3. Ensure required libraries are installed:
   ```bash
   pip install nltk scikit-learn matplotlib
   ```
4. Run the notebook sequentially to see results.

---

## ✅ Report Constraints

- Report is under 2000 words (excluding code and graphs).
- All discussions are in markdown cells.
- No external files or images are used unless embedded.
- The notebook uses the user’s own candidate number.

---

## 📌 Note

This coursework contributes 30% to the ANLP module. All code is written independently and aligns with the marking criteria defined in the provided PDF.