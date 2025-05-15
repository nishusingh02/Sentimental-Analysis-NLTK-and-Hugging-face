# 🧠 Sentiment Analysis on Amazon Customer Reviews

This project performs **Sentiment Analysis** on Amazon customer reviews using two popular NLP approaches:

* **NLTK's VADER (Valence Aware Dictionary and sEntiment Reasoner)**
* **Hugging Face Transformers using the RoBERTa model**

The goal is to classify each review into **Positive**, **Negative**, or **Neutral** sentiment and **compare the performance** of both methods.

---

## 🔍 Project Overview

Sentiment analysis is a fundamental technique in Natural Language Processing (NLP) that identifies and extracts subjective information from text. This project includes:

* VADER Sentiment Analysis (rule-based model for social media texts).
* RoBERTa Transformer (deep learning-based model from Hugging Face).
* Visual and comparative analysis of both models.

---

## 📦 Tech Stack

* **Python 3.8+**
* **NLTK** (for VADER)
* **Hugging Face Transformers** (RoBERTa)
* **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**
* **Torch** (PyTorch backend)

---

## 🚀 Setup & Installation

### 1. Clone the Repository

```bash
git clone https://github.com/nishusingh02/Sentimental-Analysis-NLTK-and-Hugging-face.git
cd Sentimental-Analysis-NLTK-and-Hugging-face
```

### 2. Create a Virtual Environment

```bash
python3 -m venv venv
source venv/bin/activate   # macOS/Linux
venv\Scripts\activate     # Windows
```

### 3. Install Dependencies

```bash
pip install nltk pandas numpy seaborn matplotlib torch transformers
```

### 4. Download Required NLTK Data

```python
import nltk
nltk.download('vader_lexicon')
```

### 5. Run the Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook in browser and follow the cells to execute the analysis.

---

## 🔮 Models Used

### 1. **VADER (NLTK)**

* Rule-based sentiment analyzer.
* Efficient for short, informal texts like reviews and social media.
* Outputs compound sentiment score.

### 2. **RoBERTa (Hugging Face Transformers)**

* Deep learning model pretrained on large corpora.
* Uses context-aware attention mechanisms.
* Returns logits for each sentiment class.

---

## 📊 Output & Visualization

* Pie charts and bar graphs to show sentiment distributions.
* Confusion matrix and accuracy scores to compare model effectiveness.
* Examples of sentiment misclassifications.

---

## 📊 Results Summary

* VADER is fast and interpretable but struggles with nuanced language.
* RoBERTa performs better on complex, long reviews with high accuracy.
* Final recommendation depends on use-case (speed vs. depth).

---

## 📁 Project Structure

```
Sentimental-Analysis-NLTK-and-Hugging-face/
│
├── SentimentAnalysis.ipynb     # Main analysis notebook
├── sample_reviews.csv          # Input data (if any)
├── README.md                   # Project documentation
└── requirements.txt            # Python dependencies
```

---

## 📄 License

This project is licensed under the MIT License.

---

## 🌟 Acknowledgements

* [Hugging Face Transformers](https://huggingface.co/transformers/)
* [NLTK Project](https://www.nltk.org/)
* [Amazon Review Dataset](https://nijianmo.github.io/amazon/index.html)

---

Feel free to fork, star, and contribute! 🚀
