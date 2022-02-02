# Sentiment analysis for tweeter dataset using CNN

I have used these following data preprocessing techniques before running the CNN model,
	
1.	Stop Word Remove
2.	URL Remove
3.	Mention Remove
4.	Number Remove
5.	Punctuation Remove
6.	Converting Lowercase
7.	Stemming
8.	Empty Row Remove

After that I have used these layers to build the CNN model.

![image](https://user-images.githubusercontent.com/39572828/152203166-37c7427d-ffb3-4c23-b834-044fcec41d5a.png)

I have got 86.05% after running the model.


The model accuracy during the epoch running is shown below.


![image](https://user-images.githubusercontent.com/39572828/152203251-b0aca18d-fb48-4914-abf4-65acf4ecab71.png)

Here, the accuracy was above 90% during train period. And it became around 86% during test period.

The model loss curve during epoch running is shown below,

![image](https://user-images.githubusercontent.com/39572828/152203352-a03bc3fd-48e4-4689-accd-94f6dde72ba9.png)

Here, the loss was about 30% during train period, and it became around 40% during test period.

Accuracy Summary:

Accuracy: 86.0544 
Precision: 86.0544 
Recall: 86.0544 
F1 score: 86.0544


![image](https://user-images.githubusercontent.com/39572828/152203407-3121d65e-f5b7-4d28-bb1b-80b2e27c174d.png)


This matrix shows that the model has successfully predicted 1548 sentences as negative successfully and failed to predict 42 sentences as negative. For Positive, it only predicted 245 sentences successfully and failed to predict 223 sentences. So we can see, this dataset has imbalanced data with a large number of negative sentences. This model has trained properly only to detect negative sentence. 
