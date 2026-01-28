# IMDB Sentiment Analysis with BERT

##  Project Overview
This project fine-tunes a **pre-trained BERT model** to classify IMDB movie reviews as **Positive** or **Negative** sentiment.

Instead of traditional machine learning approaches, we use **state-of-the-art Transformer-based NLP** via the **Hugging Face ecosystem**, which is the industry standard for modern NLP workflows.

The model is trained using GPU acceleration (Google Colab or Kaggle) and leverages **transfer learning** from a BERT model pre-trained on large-scale corpora such as Wikipedia.

---

##  Key Concepts
- Transformer architecture & bidirectional context
- Subword tokenization (WordPiece)
- Attention masks and padding
- Fine-tuning vs training from scratch
- Evaluation with Accuracy & F1-score
- Model inference with confidence scores

---

```text
imdb-bert-sentiment/
│
├── data/
│   ├── raw/
│   │   └── imdb.csv
│   └── processed/
│       ├── clean_data_&_EDA.csv
│       └── tokenized_data/
│
├── notebooks/
│   ├── data_cleaning_&_EDA.ipynb
│   ├── data_tokenization.ipynb
│   └── imdb_bert_finetuning.ipynb
│
├── models/
│   └── bert-base/       
│
├── reports/
│   ├── performance_report.md
│   └── figures/
│
├── requirements.txt
└── README.md
