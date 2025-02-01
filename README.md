# Sentimental-Analysis-CNN
The digital age has changed how we communicate, with millions of people expressing their thoughts and opinions on social media platforms like Twitter. Analyzing the sentiment behind these posts offers valuable insights into public perception, which can help businesses, governments, and individuals make informed decisions. Natural language processing (NLP) techniques are essential for extracting meaning from this unstructured data.
This project focuses on using the Sentiment140 dataset and NLP methods to develop a model that automatically predicts tweet sentiment. The goal is to better understand public sentiment on various topics, which can inform marketing, product development, and policy decisions.
As an educational initiative, the decision was made to build everything from the ground up. This includes training custom Word2Vec models for word vectorization and designing a neural network classifier. This approach provides a deeper understanding of sentiment analysis, its steps, and the challenges involved in developing such a model.
The project is organized into three main notebooks:

1. Data Visualization and Cleaning: This notebook focuses on preparing the dataset for sentiment analysis by visualizing the data and cleaning it. Key tasks include removing stop-words, eliminating punctuation and accented characters, applying stemming to reduce words to their base form, and excluding non-alphabetic characters. After processing, the most frequent words are displayed, and the cleaned data is saved for further analysis.

2. Word Vectorization: This notebook covers the process of transforming text data into numerical vectors. Techniques like CountVectorizer, TF-IDF Vectorizer, and Word2Vec (using both Skip-Gram and CBOW models) are explored. A logistic regression model is also trained to evaluate the vectorized data's effectiveness.

3. Neural Network Modeling: Here, different neural network architectures (Feedforward, LSTM, and GRU) are trained and tested for sentiment classification. Hyperparameters are tuned, and statistical tests are performed to assess performance. MLflow is used for tracking and reproducibility of model outcomes.
