# SENTIMENT-ANALYSIS-WITH-NLP

*COMPANY*: CODETECH IT SOLUTIONS

*NAME*: K VIVEK

*INTERN ID*: CT12KMG

*DOMAIN*: MACHINE LEARNING

*DURATION*: 8 WEEKS

*MENTOR*: NEELA SANTHOSH KUMAR

*DESCRIPTION*: In this task, I performed sentiment analysis on a dataset of customer reviews from the airline industry using TF-IDF (Term Frequency-Inverse Document Frequency) vectorization and Logistic Regression for classification. The dataset consisted of customer feedback on their experiences with airlines, where the reviews were labeled as either positive or negative based on the sentiment expressed in the text. The goal of this task was to analyze the reviews and classify them accurately based on their sentiment, using machine learning techniques.The first step in the task was to load and preprocess the dataset. The data was provided in text format, with each record containing a customer review and its corresponding sentiment label. Before proceeding, I cleaned the text data by removing any unwanted characters, stopwords, and performing stemming or lemmatization to reduce words to their base form. Text preprocessing is crucial in natural language processing (NLP) tasks to ensure that the model can focus on the essential features without being affected by irrelevant information. After cleaning the data, I split the dataset into training and testing sets to evaluate the model’s performance on unseen data, typically using an 80/20 split. The next step was to convert the text data into numerical features, which is a critical aspect of working with textual data in machine learning. I used TF-IDF Vectorization, a widely used technique in NLP, to transform the text data into a matrix of numerical features. TF-IDF works by weighing the importance of words in a document relative to their frequency in the entire corpus. Words that occur frequently in a specific document but infrequently across the entire dataset are considered more important. This transformation helped to capture the semantic meaning of the reviews, allowing the machine learning model to understand the text. After the vectorization, I obtained a sparse matrix where each row represented a review, and each column represented a unique word from the dataset.Once the text data was vectorized, I moved on to model training. For this task, I chose Logistic Regression, a simple yet effective classification algorithm for binary classification problems. Logistic regression works by estimating the probability that a given input belongs to a particular class (in this case, positive or negative sentiment). It does this by learning a linear decision boundary that separates the two classes. I trained the logistic regression model on the training data, tuning its parameters such as regularization to prevent overfitting and improve generalization.After training the model, I evaluated its performance on the test dataset using several metrics, such as accuracy, precision, recall, and F1-score. The accuracy provided a general measure of how well the model predicted the sentiment of the reviews. However, to gain a deeper understanding of its performance, I also examined the confusion matrix, which allowed me to see how well the model classified positive and negative reviews and identify any potential biases or misclassifications. A high precision and recall value for both classes would indicate that the model was accurately identifying both positive and negative sentiments.In conclusion, this task involved using TF-IDF vectorization to transform textual customer reviews into numerical features and applying logistic regression for sentiment classification. Through this process, I was able to successfully predict the sentiment of customer reviews, providing valuable insights into customer satisfaction and airline service quality. The use of TF-IDF helped capture the most meaningful words from the reviews, and logistic regression proved to be an effective method for classifying the sentiment into positive or negative categories. This task enhanced my understanding of NLP techniques, text preprocessing, and sentiment analysis while working with real-world data from the airline industry.

#OUTPUT

<img width="521" alt="Image" src="https://github.com/user-attachments/assets/5f757802-42b9-4a7c-a101-f852d9c2f7bc" />
