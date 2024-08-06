The model is able to detect and classifies tweets into hate speech, offensive language or neither over an accuracy of 0.983. The algorithm used for the model is SGD Classifier. 
The dataset contained 24783 records and data preprocessing was performed using the NLTK library. The dataset was first word tokenized, then converted to lowercase. 
After this stop words were removed and then each word was stemmed. The resulting corpus was then tfidf vectorized and then model training was done. The project is currently on-going and I plan to deploy the model in future.
