# fraud-detection-in-paysim-dataset
fraud detection in paysim dataset
Fraud detection using ML based supervised techniques

Paysim dataset link: https://www.kaggle.com/datasets/ealaxi/paysim1

This is typically high imbalance dataset having 0.2% of frauds in 6 million samples which makes the training very tough

And only transfer and cashout types columns have that frauds marked and others are all not frauds

So I have sepearted transfer and cashout types individually and built models on them and finally merged again

I used : log regression svm with rbf and linear xg boost

logreg and xg boost performed very well and log reg made a quite impressive performance due to it fit that linear decision boundary in the data pca used

And smote cant be used and is it is largest dataset and this smote process is complex

