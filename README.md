# Sinhala-English Code-Mixed Sentiment Dataset  

This repository provides a **sentiment-annotated dataset** for Sinhala-English code-mixed text. The dataset is specifically tailored for research in **Sentiment Analysis (SA)** and related Natural Language Processing (NLP) tasks.  

---  

## Overview  

Code-mixing, a prevalent phenomenon in multilingual societies, combines elements of two or more languages. This dataset focuses on Sinhala-English code-mixed text (often referred to as Singlish), widely used in Sri Lankan social media conversations, especially on platforms like YouTube®.  

### Why This Dataset?  

Despite the prevalence of code-mixed communication in Sri Lanka, resources for Sinhala-English sentiment analysis are scarce. This dataset provides:  
- **Sentiment-labeled data** to foster research in code-mixed language processing.  
- **A baseline** for building robust machine learning models for mixed-language sentiment analysis.  

---

### Corpus Statistics  

The dataset consists of comments sourced from YouTube® and annotated manually by a group of nine annotators. Below are the key corpus statistics:  

| **Statistic**                | **Value**          |  
|------------------------------|--------------------|  
| Number of Comments           | 7,832             |  
| Number of Tokens             | 74,725            |  
| Number of Unique Tokens      | 17,111            |  
| Average Sentence Length      | 10 tokens/comment |  

### Data Distribution  

The sentiment labels in the dataset are distributed as follows:  

| Sentiment   | Number of Comments |  
|------------------|-------------------------|  
| Positive         | 4,263                 |  
| Negative         | 1,853                 |  
| Neutral          | 1,716                 |  
| **Total**        | **7,832**             |  

Note: The data is slightly biased towards **positive sentiment** because users are more likely to leave comments when they like content on YouTube®.  

---

### Machine Learning Models  
The dataset was evaluated using the following machine learning models:  
1. **Support Vector Machine (SVM)**  
2. **Logistic Regression (LR)**  
3. **Decision Tree (DT)**  
4. **Random Forest (RF)**  
5. **K-Nearest Neighbors (KNN)**  

#### Results  

The evaluation provided significant insights, with the **Random Forest (RF)** classifier achieving the **highest accuracy of 75%** on the testing set, demonstrating the strength of ensemble methods for this dataset.  

---
### Published in
Proceedings of the 4th International Conference on Advanced Research in Computing (ICARC)
**IEEE Xplore®** 
- DOI: [10.1109/ICARC61713.2024.10499746](https://ieeexplore.ieee.org/document/10499746)
- [Research Paper (PDF)](docs/Sinhala-English_Code-Mixed_Language_Dataset_with_Sentiment_Annotation.pdf)
## Citation
If you use this dataset in your research, please cite:

@inproceedings{SinhalaEnglishCodeMixed2024,
  author    = {D. K. Uthpala and S. Thirukumaran},
  title     = {Sinhala-English Code-Mixed Language Dataset with Sentiment Annotation},
  booktitle = {Proceedings of the 4th International Conference on Advanced Research in Computing (ICARC)},
  year      = {2024},
  doi       = {10.1109/ICARC61713.2024.10499746}
}

## Contributions
Contributions to improve this dataset or provide new tools for sentiment analysis are welcome.

#### Contact
D. K. Uthpala: uthpaladil95@gmail.com      
S. Thirukumaran: thirukumaran@vau.ac.lk
