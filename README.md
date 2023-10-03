# SentimentAnalysisIMDb_TransformerFineTune
Fine Tuning Transformer (DistilBert, but generic to other models) for MultiClass Text Classification (Sentimental Analysis over IMDb)


## 🤔 What is this?
**Description:**  The objective of this script is to fine tune DistilBERT (but generic to severall models) on the IMDb dataset to determine whether a movie review is positive or negative (label 0 "negative", 1 "positive").


## 📚 Data

We are using IMDb data from datasets library Repository.

Where each row has the following data-point:
  - label (0 negative, 1 positive)
  
  - text		 
		  


##  🚀 Quick Install


Due to the power of GPU needed i advise you to use colab with `SentimentAnalysisIMDb_TransformerFineTune.ipynb`(in classification dir)


Run


## 📖 Documentation

Please see the description in .ipynb about this project.




##  🚀 Results 

DistilBert training with 25k reviews and testing with other 25k  ajs ~93% acuraccy (with 3 Epochs)
