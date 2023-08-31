# Music-Recommendation-System
Music-Recommendation-System In this project, we analyzed sequential patterns of songs userwise. We took **One Hot, Word2Vec** and **Bert** word embeddings and used as an input representation of words. Finally, we made **Horizontal CNN** and **Vertical CNN** and concatenated them to get our final results.
+	Developed a music recommendation system using **next basket prediction** technique.
+	The system uses machine learning and **Convolutional Neural Networks (CNN)** techniques to suggest music to users based on their preferences and past behaviour.
+	Includes CNN applied over basket and target with the help of different Embeddings.
+	Achieved remarkable accuracy of 74.68% on 20k samples of data.

# Overview
+	In contrast to standard predictive models, recommender systems need training on data in a sequential manner, often called sessions.
+	I implemented model by dividing data into unique users. Next for each user, I made many sessions for the user which shows many sequences of music that were of 
  interest of the user.
+	Then, I applied Ensembled CNN model in which I processed data in a Horizontal CNN model and a Vertical CNN model and then concatenated them to form a single but 
  powerful learning model.

  ![recom](https://github.com/ANUBHAVKAMBOJ/Music-Recommendation-System/assets/90023327/879e598c-83ac-4c4f-ad15-7e30f1177aa4)

# Evaluation
+	Used **adam** as optimizer and **categorical_crossentropy** as loss for training model.
+	Trained on **One Hot Embedding**, **Word2Vec Embedding** and **BERT Embeddings** giving results as **(42.91% vs 63.27% vs 74.68%)**.

# Advantages over Traditional Models
+	Scoring of products user-wise and in the form of sequences known as baskets.
+	Another edge, using Ensembled CNN model with pre-trained Embeddings for better understanding User's behaviour and preferences.

# Technologies Used
+	Numpy
+	Pandas
+	Convolutional Neural Network (CNN)
+	Tensorflow
+	BERT and Word2Vec Embeddings
+	Matplotlib
+	Python

# Tools
+	Jupyter Notebooks
+	Google Colab 
+	Github

# Data
I built Recommendation System based on a real-world dataset: 30Music. As entire dataset is very large (1.8 million samples of data), I used only a part of it for training model.\
Data Source Link: https://recsys.deib.polimi.it/datasets/

# Screenshots

 ![ss1](https://github.com/ANUBHAVKAMBOJ/Music-Recommendation-System/assets/90023327/00a05cf7-4d8e-430a-8103-6be167635b6e)

![ss2](https://github.com/ANUBHAVKAMBOJ/Music-Recommendation-System/assets/90023327/0eaabf61-94df-4534-8e58-70459be91163)

\
**Model Accuracy**

![ss31](https://github.com/ANUBHAVKAMBOJ/Music-Recommendation-System/assets/90023327/04aff548-6c43-4e4b-961f-3e4aee4080ec)



 


