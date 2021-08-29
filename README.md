# Football Players Price Prediction

In the notebooks I have performed EDA and evaluated different models on Football players price dataset.

As I expected during EDA Eventhough we have processed our data well and preserved correlations so well while reducing dimensionality from 44 to 13, still loss values are huge. It is due to high standard deviation in our target variable "price". So, The loss value cannot be reduced below a certain level.
Finally, I have concluded that we can't use this dataset to achieve great accuracy since the price value is distributed with huge variance and it does not reflect any player's properties. Also the dataset is imbalanced in some main features like position.
