#### Authors:
- Abdallah Mohammed
- Emad Abdalghaffar
- Lauren Safwat
- Yasser Ashraf
<br>
#### 2022 _ Information Technology Institute (ITI) _ AI-Pro Program
<br><br>
______________________________________________

### NLP__Toxic_Comments_Classification
<br><br>


#### Dataset
Wikipedia comments, labeled by human raters for toxic behavior.
The types of toxicity are: toxic, severe_toxic, obscene, threat, insult and/or identity_hate.
The dataset could be found here:
https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge
<br>
#### Data Preprocessing
 - Eliminating: stop words, URLs, E-mails, Hashtags, mentions, special characters, HTML tags  and whitespaces.
 - Convert the entire text to lower case
 - Applying lemmatization
<br>
#### Models
6 models have been investigated in this classification project:
- FFNN Model with BoW (TF-IDF) Text Representation
- RNN
- LSTM
- Bidirectional LSTM
- GRU
- Bidirectional GRU
<br><br>
