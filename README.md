# OITNB Sentiment Analysis
In this project, I perform sentiment analysis on the script of the pilot episode of Orange is the New Black. Initially, I create a pandas database of the characters speaking and their respective dialogue using regular expressions. Next, I preprocess each line and run sentiment analysis and part of speech tagging. Finally, using part of speech and vocabulary as features, I explore using logistic regression models to classify dialogue lines as holding positive, neutral, or negative sentiment. 

After training and evaluating these logistic regression models, I consider other factors which may help improve our model in future iterations by identifying potential shortcomings. 

The entirety of this project can be seen in the Jupyter Notebook 'OITNB_Tokenization.ipynb', in which I use Python. 
