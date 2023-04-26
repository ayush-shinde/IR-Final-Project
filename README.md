# Social Media Information Response for Natural Disaster

### Introduction
This project aims to analyze social media data, specifically from Twitter, to understand user sentiment during natural disasters and evaluate the effectiveness of various machine learning models in classifying this data. The goal is to improve disaster response efforts by leveraging the power of social media information sharing.

### About Dataset
The dataset used in this project is the Natural Hazards Twitter Dataset which contains tweets related to various natural disasters. The dataset is publicly available on GitHub and comprises tweets that were collected during significant natural disaster events, such as hurricanes, earthquakes, and wildfires.

### Analysis
#### Models Used
In this project, we used the following machine learning models to analyze and classify the sentiment of tweets related to natural disasters:
BERT
DeBERTa
RoBERTa
K-Nearest Neighbors (KNN)
Decision Tree
Multiple Neutral Network (MNN)
Support Vector Machine (SVM)

#### Performance Evaluation
We assessed the performance and accuracy of each model in classifying tweet sentiment. The findings emphasize the advantages and drawbacks of each model concerning prediction accuracy, computational time, and other relevant metrics. The analysis offers valuable insights into which models are most appropriate for this specific classification task.

#### Results
Our analysis results indicate that some models, such as BERT and RoBERTa, achieved high accuracy in sentiment classification, while others, like KNN and Decision Tree, had lower accuracy. Overall, the study showcases the potential of using sophisticated natural language processing techniques and machine learning models to enhance disaster response initiatives through social media analysis.

#### Conclusion
This project demonstrates that social media data, particularly from Twitter, can be an invaluable asset for understanding user sentiment during natural disasters and guiding disaster response initiatives. By analyzing this data using various machine learning models, we can gain insights into which models excel in sentiment classification and make more informed decisions regarding disaster relief approaches.

*About the python files*
Required Libaries
1. transformers
2. sentence_transformers
3. tqdm
4. datasets
5. evaluate
6. peft

Required changes in code:
1. Change the directory path to dataset folder
