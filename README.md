# Bloc N° 4 : Analyse prédictive de données non-structurées par l'intelligence artificielle.

[Video explain - Bloc 4](https://share.vidyard.com/watch/EabmuYkViNyjstKvDsAPTg?)

# AT&T Spam detector
AT&T is looking for an automated way of detecting spams to protect their sms users.
## Context and goals of this study:

The objective of this project is to create a spam detector for AT&T, based on a dataset with labels "spam" or "ham" (being non spams).
We are thus dealing with prediction on non structured data being text. In this context Natural Language Processing with deep learning will be applied.

The below models have been applied :
-	A simple deep learning model with 2 successive dense layers
-	The above model tuned with dropout
-	BERT transfer learning. Helper : https://tfhub.dev/tensorflow/bert_en_uncased_L-12_H-768_A-12/4 

# Available files:
- AT&T_FINAL.ipynb: notebook containing AT&T project
- spam.csv: source dataset

Happy reading !
