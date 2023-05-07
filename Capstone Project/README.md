# Tweet Sentiment Extraction - Capstone Project ®

### Motivation of this Project

Everyone talks about Elon Musk and his `Twitter` Saga. And voila, we landed at how sentiments are influenced, by words - right, well if we have those words annoatated, can we build a solution to classify a tweet as `Positive/Neutral/Negative`?
We are into the era of **`Generative AI`** where NLP has seen some breakthrough techniques like **`Transformers, Bi-directional LSTM, LargeLM models`**.

So,our problem statemt is: **`Tweet Sentiment Extraction`**.  
Blog Link: https://medium.com/@mishra5001/twitter-sentiment-extraction-spacy-ner-3ddd323c6b2e

### Project Overview
In this particular project, we intend to extract the parts of words or phrases that reflects the sentiment.
<img width="978" alt="image" src="https://user-images.githubusercontent.com/22134737/235300542-562e7352-e7a7-4c08-b3f3-19868f5f0a0e.png">

### Libraries used:
- pandas
- stats
- numpy
- seaborn
- matplotlib
- spacy
    - spacy.ner -> creating blank `ner` pipeline
    - spacy.Examples -> split the examples in batches
    - spacy.util.minibatch and spacy.util.compounding
- warnings

### Folder structure:
```
- Capstone Project
    - data
        ---------------- the 3 data files
    - models
        - model_neg
        - model_neg_redifined
        - model_neu
        - model_neu_redifined
        - model_pos
        - model_pos_redifined
    - src
        - Custom NER - Spacy.ipynb
        - Spacy components working.ipynb
        - Tweet Sentiments Extraction.ipynb
    - visualizations
        ---------------- respective graphs

```

### Inferences 
1. People tend to explain their reasoning behind a Neutral review.
2. Quite a few stopwords and punctuations removed. This resulted in increased Jaccard Score, measuring the capability of oure power of predicting correct texts.
3. No major missings rows or data transformation required apart form extracting entities logically given that sentences are in sequence.

For more refer notebook: https://github.com/mishra-atul5001/udacity-DS-nano-degree/blob/main/Capstone%20Project/src/Tweet%20Sentiments%20Extraction.ipynb
### Acknowledgements/References:
- My github repository for `Tweet Clustering`, which motivated me to build smarter solution: https://github.com/mishra-atul5001/Data-Science-and-ML-insights-Projects/blob/master/Tweet%20Clustering.ipynb
- Spacy NER breakdown sample: https://www.kaggle.com/code/rohitsingh9990/ner-training-using-spacy-ensemble/notebook
- Large thanks to: https://www.kaggle.com/code/rohitsingh9990/ner-inference-using-spacy-lb-0-628?scriptVersionId=32085239 for providing implementation aspect
- ChatGPT
