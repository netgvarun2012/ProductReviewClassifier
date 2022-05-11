# Introduction: 

The data set provided to has a mix of customer reviews for products across categories and retailers.

Goal is to model on the data to bucket the future reviews in their respective topics (Note: A review can talk about multiple topics) 
and Overall polarity (positive/negative sentiment): 

- Topics (Components, Delivery and Customer Support, Design and Aesthetics, Dimensions, Features, Functionality, Installation, Material, Price, Quality and Usability)
- Polarity (Positive/Negative)


## Dataset details

![image](https://user-images.githubusercontent.com/93938450/167915189-b6f2e9b5-4bcd-4723-bf98-78f45701a6da.png)


## Solution

- First, data is loaded into Pandas dataframe.
- Exploratory Data Analysis is done to find hidden patterns.
- Text preprocessing is done which involves removal of stop words, lemmatization etc.
- Finally, training is done for 12 epochs using [DistilBERT](https://huggingface.co/docs/transformers/model_doc/distilbert) transformer model.

![image](https://user-images.githubusercontent.com/93938450/167914892-a5130e8e-fc76-496d-90ab-625b2e3b423b.png)
