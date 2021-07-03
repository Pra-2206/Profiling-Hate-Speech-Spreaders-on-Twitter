# Profiling-Hate-Speech-Spreaders-on-Twitter
# Introduction
Hate speech (HS) is commonly defined as any communication that disparages a person or a group on the basis of some characteristic such as race, colour, ethnicity, gender, sexual orientation, nationality, religion, or other characteristics. Given the huge amount of user-generated contents on Twitter, the problem of detecting, and therefore possibly contrasting the HS diffusion, is becoming fundamental, for instance for fighting against misogyny and xenophobia.So the task of Profiling Hate Speech Spreaders on Twitter  was the part of  PAN@CLEF 2021 competition. The task was about to determine whether the author spreads the hate speech or not in a given twitter feed. The organisers propose the task in two languages : English and Spanish.
# Dataset
We used the data provided by organisers for this task.They provided the data in two languages: English and Spanish. The data contains user ids and their tweets. The data contains 200 users and 200 tweets of each user for each language.So We used 40,000 tweets for experimentation for each language.

# Features and Models
We used the TF-IDF and Countvectors for this purpose. Four Machine Learning classifiers (i) multinomial naive Bayes, (ii) K-Nearest Neighbors (KNN) classifier, (iii) logistic regression and (iv) linear SVM, along with three deep learning models (i) Long Short Term Memory (LSTM), Bidirec-tional Long Short term Memory (bi-LSTM) and Bidirectional Encoder Representations for Transformers(BERT)model were implemented for the identification of hate speech spreader.
# Result
The experiments withall the mentioned models on the training dataset provided by PAN (by splitting it into training andtesting datasets) revealed that the multinomial naive Bayes is the best model with an accuracy of 74%for the English dataset and 82% for the Spanish dataset. The multinomial naive Bayes model yielded
an accuracy of 66% for the English dataset and 80% for the Spanish dataset with the unknown private dataset used by the organizers for the final evaluation of the models.
 
