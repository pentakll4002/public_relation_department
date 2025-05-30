# 📢 Public Relation Department – Alexa Reviews Analysis
This project is designed to support the Public Relations Department in analyzing customer feedback on Amazon Alexa using machine learning and data visualization. It leverages a variety of Python libraries for data processing, visualization, and model development.

## 📂 Dataset
- File used: amazon_alexa.tsv

- Source: Public dataset containing customer reviews for Amazon Alexa

- Load command:

```python
import pandas as pd
df = pd.read_csv('amazon_alexa.tsv', sep='\t')
```

## 🛠 Libraries Used
- pandas: Data manipulation and analysis

- numpy: Numerical computing

- seaborn: Data visualization

- matplotlib: Plotting and charting

- pickle: Model serialization

- warnings: Handling warning messages

- nltk: Natural Language Processing (tokenization, stopwords, etc.)

- tensorflow: Deep learning and neural networks

- sklearn.metrics.roc_auc_score: AUC metric for classification performance

## 📊 Features
- Load and preprocess customer reviews from a TSV file

- Clean and tokenize text data using nltk

- Visualize trends and sentiment distributions with seaborn and matplotlib

- Train a deep learning model using tensorflow to classify sentiment

- Evaluate model performance using AUC score

- Save and load models with pickle

## 🚀 How to Run
1. Clone the repository

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the main script:

```bash
python main.py
```

## 📈 Output
- Cleaned and structured dataset

- Sentiment analysis results

- AUC score to evaluate model performance

- Visual insights into customer sentiment

- Saved trained model for reuse

## 📌 Notes
- Make sure you have NLTK stopwords and tokenizer resources:

```python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
```

- TensorFlow might require a compatible version of Python and CUDA if using GPU.

## 🤝 Contributions
Feel free to open issues or submit pull requests to improve the analysis or model performance!

