# text message spam or not



In this project, I explored about 5000 text messages annotated either spam and ham.
The goal is to have a model that accurately predicts whether a text message is spam or not spam. 
To do this: 

1. Read the raw text data
2. Clean the text and tokenized 
3. Created features
4. Fit them into 2 models - Random Forest, Gradient Boosting)
5. Tune and evaluated grid search cross validation 
6. Decide which model works best 

**Results**: 
Random forest (RF) - 
fit time: 0.45534682273864746, predict time: 0.026226043701171875, precision: 0.984375, recall: 0.8689655172413793, accuracy: 0.981149012567325

Gradient boosting (GB) - 
fit time: 31.55548596382141, predict time: 0.016566991806030273, precision: 0.8888888888888888, recall: 0.8827586206896552, accuracy: 0.9703770197486535

**Conclusion**:
Even though GB took much lonter to git, it was shorter to predict than RF. However GB's precision was lower than RF. RF's recall was slightly lower than GB. We can select the model depending what metric we prioritize more. 
