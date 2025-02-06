# Amazon-Kindle-Review-classification-NLP-

The aim of the project was to find whether the reviews given by people were positive or negative. 

--> About the dataset

1)There were 12000 rows in the data. Two columns were there. One was the message column and the other was the output column. 

2)There were 5 reviews. I modified it such that such that reviews less than 3 are negative else it is positive.

3)The datset was not imabalance.

-> Approach

1)Preprocess and cleaned the text.
   
2)I used three different methods for this. TFIDF,BOW, Word2vec after preprocessing the text(cleaning, removing stopwords, and applying stemming/ lemmatization).

3)The best model among th three was Word2vec which gave me around 70% accuracy.

4)Made a webapp using streamlit

![image](https://github.com/user-attachments/assets/671d39be-c446-4b4c-a1c8-852cbc952142)

