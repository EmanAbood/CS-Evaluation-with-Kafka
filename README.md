# CS-Evaluation-with-Kafka
Project Cyper Security Evaluation with Kafka DataSet
## About Project
the project has two data sets (Static Dataset & Dynamic"Kafka" Dataset) 
For Static DataSet
Data Analysis,Feature engineering and data cleaning,Feature Filtering/Selection,Model Training and Model evaluation
For Dynamic DataSet
- Use the Kafka dataset in the producer to send messages to the consumer. 
- Use Static dataset in consumer to add the data coming from the producer. 
- In the Dynamic file load static data and do the same reprocessing in the Static file. 
- Create a function to append 1,000 observations of data streaming information and use them as a window with the number of iterations. - Create function for cleaning, retrained model, and for mutual information which best select features. 
- Load the champion model in the dynamic model and static model. 
- The same that I used to fit the dynamic model and predict. 
- Evaluate the performance of each model on each window using Recall and f1-score metrics. 
- If the model’s f1-score is lower than 89% and retrains the Dynamic model because in static dataset most of models have f1-score higher than 89. 
- From results between dynamic and static, show that when adding 1000 samples on static data and retraining it gives sometime high f1-score that’s meaning the model extracted most of the correct expected and sometimes low f1-score that’s meaning there is atta
