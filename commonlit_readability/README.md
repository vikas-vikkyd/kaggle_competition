# Commonlit Readability
https://www.kaggle.com/c/commonlitreadabilityprize

In this competition we have to predict reading level for a passage of text.
Implemented DNN with Embedding layer to predict readability of passage of text

![image](https://user-images.githubusercontent.com/29758488/128608821-9cfd8ee6-a8f5-4a98-bfc3-7c56e505ee75.png)

1. used 5th layer (output dimension 512) as a feature extractor for text.

2. Removed highly correlated feature from 512 dimensional vector and used Random forest for feature selection.

3. On refined feature list trained multliple regression model like Ridge, Random Forest, Xgboost and Support vector.

4. Stacked all model for final prediction.
