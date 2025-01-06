Uses NLP to detect a person’s mental status based on the contents of their online posts (classes: normal, stressed, anxious, depressed, or suicidal). Utilizes an LSTM RNN deep learning model and Vader analysis. 

Jupyter notebook contains word clouds, other considered ML models, and past versions of the LSTM model. 

My major contributions: Noticed the model ID’d depressive posts as suicidal posts, and that we needed to to discern the posts’ level of negativity to make them easier to differentiate. Improved model accuracy by +20% in adding a value that detected the negativity level of the post (ala VADER analysis) as well as resampling the dataset to balance its contents.

Dataset used in this project (31.5 MB - too big to upload): https://www.kaggle.com/datasets/suchintikasarkar/sentiment-analysis-for-mental-health
