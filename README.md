# OLST_prediction_part_2
second part of the OLST prediction
The second section is using supervised machine learning models to predict balance ability based on gait task. The balance ability was defined by the performance of eye-close OLST which were rated by three assessors mentioned in the first section. The features fed in the SL models were extracted from each step of the gait task and included the signal from the motion capture system and force plates. Based on the information above, the SL models were the 3-classes predictive model and trained by the features with different properties. Before training the models, the missing data was filled with the average value of the corresponding feature. To avoid multilinearity, the high correlated (correlation more than 0.9) features were removed. Finally, the dataset was normalized and standardized and then 70% were used to train the models and 30% for the testing.

Research question:
Which algorithm works best?
Which gait features can produce an outperforming predictive model?

![image](https://user-images.githubusercontent.com/104646372/178052194-47eab483-5342-43a3-8b30-6223f305c472.png)
