# 7390_TalkingData-Ad-Tracking-Fraud-Detection

### TalkingData Ad Tracking Fraud Detection is a challenge that took place on Kaggle Competition Three months ago. This project chose this competition as topic to predict whether it is a fraudulent click for mobile app ads covered by the test set, using information available three months ago. This project used basic features provided by dataset, proposed several new features to improve the accuracy of prediction, and applied four machine learning models – Random Forest, Gradient Boosting & AdaBoost, Logistic Regression, and SVM, three deep learning algorithms, ANN, RNN and MLP. The solution is evaluated with ROC curve. The best result is of 100%.

### Background
#### Fraud risk is everywhere, but for companies that advertise online, click fraud can happen at an overwhelming volume, resulting in misleading click data and wasted money. Ad channels can drive up costs by simply clicking on the ad at a large scale. Ad fraud is defined as any deliberate activity that prevents ads from being served to human users. It may cause illegal bot activity, historically fraudulent URLs, or specific page-level fraud. Furthermore, it costs the industry $8.2 billion a year in the U.S. alone, according to the IAB. As advertising budgets keep shifting to digital, fraudsters have found ways to game the system and earn money by serving ads in ways that have no potential to be seen by a real person. Needless to say, this has a negative effect on the entire advertising community.
#### China is the largest mobile market in the world and therefore suffers from huge volumes of fraudulent traffic, With over 1 billion smart mobile devices in active use every month. 
#### TalkingData, China’s largest independent big data service platform, covers over 70% of active mobile devices nationwide. It handles 3 billion clicks per day, of which 90% are potentially fraudulent. In order to always be one step ahead of fraudsters, we will build algorithms that predicts whether a user will download an app after clicking a mobile app ad. In this way, if the result is satisfactory, it can generate a model for TalkingData to build up its strategy to prevent from users clicking a fraudulent ad.



#### Datasets: https://drive.google.com/file/d/1INF9CHPF4HZyCVSpUi63USloGykJQU8X/view?usp=sharing

#### For the dataset, we have the train.csv for the training. After training, using the test.csv for our prediction. 
#### But for our model, we have to create new features for our prediction. So, we translated this test.csv to test_small_all_features.csv that has 1,000,000 rows size with all needed columns (features). 
#### Due to this small size (our computers are not powerful enough to run all data), for our second part of columns, we have 100% accuracy and it also caused 100% accuracy of the all-featured prediction, which maybe overfitted. If we can run all of the data, our output the prediction can be more reliable.
### In conclusion, our new created featured successfully increase the prediction.