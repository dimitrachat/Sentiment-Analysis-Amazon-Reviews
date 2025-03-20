# Sentiment-Analysis-Amazon-Reviews

## Overview
This project focuses on analyzing customer reviews of musical instruments on Amazon. It uses traditional Natural Language Processing (NLP) techniques like Latent Dirichlet Allocation (LDA) and Term Frequency-Inverse Document Frequency (TF-IDF), as well as Generative AI (GPT-2), to identify key topics and classify sentiments as positive, negative, or neutral.

## Introduction
Online reviews play a crucial role in shaping consumer decisions. This project aims to analyze Amazon musical instrument reviews using sentiment analysis and topic modeling to uncover customer sentiments and key themes. The project leverages both traditional NLP techniques and Generative AI to provide actionable insights for businesses.

## Data Preprocessing
The raw text data is preprocessed to ensure accurate analysis. Steps include:
- Converting text to lowercase.
- Removing punctuation and special characters.
- Tokenization and stopword removal.
- Lemmatization to normalize words.

## Topic Analysis
### Traditional Topic Analysis (LDA & TF-IDF)
Latent Dirichlet Allocation (LDA) is used to identify latent topics in the reviews. TF-IDF vectorization is applied to weigh the importance of terms in each document. The results are interpreted to uncover key themes in the reviews.

### Generative AI Topic Analysis (GPT-2)
Generative AI techniques, specifically GPT-2, are used to generate topic labels for reviews. This approach provides a more contextually rich understanding of the topics compared to traditional methods.

## Sentiment Analysis
Sentiment analysis is performed to classify reviews as positive, negative, or neutral. A lexicon-based approach using SentiWordNet is used to calculate sentiment scores. Reviews are also labeled based on user-provided 'overall' ratings.

## Data Visualization
Visualizations are created to showcase sentiment distributions and word count analysis. Key visualizations include:
- Sentiment polarity distribution plots.
- Bar charts for sentiment distribution using lexicon-based and rating-based approaches.
- Word count distribution histograms.

## Conclusion
The project provides valuable insights into customer sentiments and key topics in Amazon musical instrument reviews. Businesses can use these insights to improve products, enhance customer satisfaction, and tailor marketing strategies.

## References
- [Hugging Face Transformers](https://huggingface.co/transformers/)
- [Scikit-learn Documentation](https://scikit-learn.org/)
- [SentiWordNet](https://sentiwordnet.isti.cnr.it/)
