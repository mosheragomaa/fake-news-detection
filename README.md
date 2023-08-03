# Fake news detection
This project is an implementation of the paper "Detecting Fake News With Machine Learning" by 
Jeffrey Huang.[1]

The project aims to build a machine learning model to classify news articles as real or fake using  several natural language processing techniques and machine learning algorithms.

The primary focus is on the comparison between two feature extraction techniques (TF-IDF and BoW) and their performance on several classification algorithms, such as Multinomial Naive Bayes, Random Forests, Passive Aggressive, and an ensemble classifier for the final model.

## Requirements

The code runs on Python version 3.x .
To install the required libraries use the following command:
`  pip install -r requirements.txt ` 

| Library | Version |
| --------| ---- |
| Pandas  | 1.5.3   |
| NumPy   | 1.25.0  |
| SpaCy   | 3.5.3   |
| SciPy   | 1.10.1  |
| Seaborn | 0.12.2  |
| Matplotlib | 3.7.1 |
| WordCloud  | 1.9.1.1 |
| Scikit-learn | 1.2.2 |
| Regex |  2022.7.9 |

## Dataset

[ISOT](https://github.com/mosheragomaa/fake-news-detection/files/12255562/ISOT.zip)  dataset consists of two files, one for the real articles and the other for the fake, both in CSV format. The real file contains 21,417 news articles sourced from Reuters.com.
and the fake file contains 23,481 news articles sourced from PolitiFact.com. 
The dataset has articles about different subjects including world news and political news. 
Each row includes the article title, text, label, and publication date[2].


## Methodology

![Untitled presentation (1)](https://github.com/mosheragomaa/fake-news-detection/assets/76535465/d6955d96-7e90-4a46-969e-877e00a1e869)


## References
[1] [Jeffrey Huang 2020 J. Phys.: Conf. Ser. 1693 012158](https://iopscience.iop.org/article/10.1088/1742-6596/1693/1/012158/pdf)

[Shalini Pandey et al 2022 J. Phys.: Conf. Ser. 2161 012027](https://iopscience.iop.org/article/10.1088/1742-6596/2161/1/012027/pdf)

[ISOT dataset](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)
