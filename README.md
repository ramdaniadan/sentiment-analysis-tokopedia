# Tokopedia Reviews Sentiment Analysis

Welcome to the **Tokopedia Reviews Sentiment Analysis** project! 🎉 This repository contains a complete pipeline for preprocessing, analyzing, and extracting insights from customer reviews of Tokopedia. The primary goal is to understand customer sentiment and identify key trends from their feedback.

---

## 📖 **Project Overview**

This project focuses on analyzing Tokopedia's customer reviews by applying the following steps:

1. **Data Loading**: Loading the dataset into a pandas DataFrame for further analysis.
2. **Preprocessing**:
   - Removing empty rows.
   - Case folding (converting text to lowercase).
   - Cleansing (removing special characters, URLs, mentions, etc.).
   - Tokenization (splitting text into words).
   - Spell normalization (standardizing spelling variations).
   - Filtering (removing stopwords).
3. **Frequency and TF-IDF Analysis**: Calculating term frequency and weighting words based on importance.
4. **Sentiment Analysis**: Using a lexicon-based approach to compute sentiment scores for reviews.

---

## 📂 **Directory Structure**

```plaintext
📁 Tokopedia-Sentiment-Analysis
├── 📂 Datasets
│   ├── reviews-tokopedia-juni.csv
│   ├── normalisasi.xlsx
│   ├── stopword_indonesia.txt
│   └── modified_full_lexicon_indo.csv
├── 📂 Results
│   ├── hasil case folding.csv
│   ├── hasil cleansing.csv
│   ├── hasil data sentimen.csv
│   ├── hasil filtering.csv
│   ├── hasil preprocessing.csv
│   ├── hasil remove number.csv
│   ├── hasil remove punctuation.csv
│   ├── hasil remove single char.csv
│   ├── hasil sentimen dengan label.csv
│   ├── hasil sentimen negatif.csv
│   ├── hasil sentimen positif.csv
│   ├── hasil sentimen tanpa label.csv
│   ├── hasil spell normalization.csv
│   ├── hasil tokenizing.csv
│   └── hasil.csv
└── README.md
```

---

## 🚀 Getting Started

1. Clone the Repository
   ```plaintext
   git clone https://github.com/your-username/Tokopedia-Sentiment-Analysis.git
   ```
2. Install Dependencies
   Make sure you have Python installed. Then, install the required libraries:
   ```plaintext
   pip install pandas
   pip install numpy
   pip install matplotlib
   pip install seaborn
   pip install nltk
   pip install scikit-learn
   pip install Sastrawi
   ```
3. Run the Jupyter Notebook
   Navigate to the Notebooks folder and launch:
   ```plaintext
   1. 01-crawling-datasets-tokopedia.ipnb
   2. 02-sentiment-analisis-tokped.ipynb
   ```

---

## 🛠️ Features

- Preprocessing Pipeline: Handles noisy data with comprehensive cleaning steps.
- Visualization: Provides distribution charts of customer ratings and term frequency.
- TF-IDF Analysis: Highlights the most important terms across reviews.
- Sentiment Analysis: Computes sentiment scores based on an Indonesian lexicon.

---

## 📘 Technologies Used

1. **Python**: Data manipulation and analysis
2. **Pandas**: DataFrame operations
3. **Matplotlib & Seaborn**: Data visualization
4. **NLTK**: Natural language processing
5. **Scikit-learn**: Vectorization and TF-IDF
6. **Sastrawi**: Stemming in Bahasa Indonesia

---

## 🙏 Acknowledgments

- **Tokopedia**: For providing the reviews dataset.
- **NLTK and Sastrawi**: For the amazing NLP tools.
- **The Community**: For their valuable feedback and contributions.

---

📬 Contact

Have questions or feedback? Feel free to reach out:
- **Email**: ramdaniadan1212@gmail.com
- **GitHub**: [https://github.com/ramdaniadan](https://github.com/ramdaniadan/)

---

Thank you for visiting this repository! 🌟 If you find it useful, please give it a star and share it with others. 🙌
