#### Authors:
- Abdallah Mohammed (https://github.com/abdallah388687)
- Emad Abdalghaffar
- Lauren Safwat (https://github.com/lauren-safwat)
- Yasser Ashraf (https://github.com/YasserAshraf12)

#### 2022 _ Information Technology Institute (ITI) _ AI-Pro Program
______________________________________________

### NLP__Toxic_Comments_Classification

#### Dataset
Wikipedia comments, labeled by human raters for toxic behavior.
<br>
The types of toxicity are: toxic, severe_toxic, obscene, threat, insult and/or identity_hate.
<br>
The dataset could be found here:
<br>
https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge
<br>
#### Data Preprocessing Pipeline
 - Eliminating: stop words, URLs, e-mails, hashtags, mentions, special characters, HTML tags  and whitespaces.
 - Convert the entire texts to lower case
 - Applying lemmatization

#### Models
6 models have been investigated in this classification project:
- FFNN Model with BoW (TF-IDF) Text Representation
- RNN
- LSTM
- Bidirectional LSTM
- GRU
- Bidirectional GRU
<br><br>
