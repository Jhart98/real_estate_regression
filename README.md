Problem Statement

How is tax affected in real estate and by which features?

Data

data.csv - real estate data set

Analysis:

Industry has a direct positive correlation with tax. <br>
There is also a postive correlation between the RAD number and the tax <br>
However other than those 2 features the others did not have much correlation <br>


Conclusion:

After running a basic linear regression the score was already at 90% on the test data<br>
Since it scored 87% on the training data, the model was not overfit. The Decision tree regressor however was overfit as it scored 100% on the training data.
The Random forest Regressor was only slightly overfit. The Decision tree regressor had the lowest mean squared error score of 165 and linear regression had the highest at 2782.47%. Overall, the Random Forest model can be said to perform the best as it had a low mse while also not being too overfit. 