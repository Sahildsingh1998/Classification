# Classification Project On Arline Referal

**Problem Statement**

To ascertain using the various Machine learning models as to a passenger is going to refer a airline to a friend based on the service experience of the airline.

**Data Description**

In the given dataset there were 17 variables out of which the recommended varible was chosen as the Target variable.

**airline** : Name of the airline
**overall** : ocerall rating of the airline
**author** : Passenger name
**review_date** : Date on which review was added
**customer_review** : Reviews of customers
**aircraft** : Aircraft type
**traveller_type** : solo, couple, Business, Family
**cabin** : cabin type
**route** : Route taken by the flight
**date_flown** : Date of flight
**seat_comfort **: rating for seat comfort
**cabin_service **: Rating for cabin service
**food_bev** : Rating for food amd ancillaries
**entertainment** : Rating for entertainment
**ground_service** : rating for ground service
**value_for_money **: Rating for value for money
**recommended **: whether the airline is recommended by the passenger or not.

**Exploratory Data Analysis**

The EDA shows that the data is imbalanced. The target variable shows that 'yes' in recommended column are around 9744 while the 'No' are around 4000. Therefore to apply the classification model the data was balanced using the minority class.
There is also the problem of multicollinearity present in the data which was ascertained using the heatmap and cutoff correlation coffient to remove the multicollinearity was taken 0.8 and thus overall column was dropped from the dataset.
The data values for the cathy pacific airlines itself contribute about 10% of the data i.e 1026 values
Most of the traveller types prefer the Economy class because of cheaper fairs except for business traveller type which are edge to edge with the economy and business class.
The 1st class cabin service is not as good as other classes because even of the bulk ratings are close to 4 then also the EDA shows that the passenger is not going to recommend the airline and its wick in box plot goes to rating of 5.
The data values for Germanwings airline is just 4 in count.
The best tradeoff between the in airservice and the ground service is provided by the All ANA Nippon Airways as found using the scatterplot

**Approach**

EDA and Feature Selection.
Removed class imbalance.
Removed Multicollinearity.
Feature Selection.
Splitting Dataset into train and test set.
Model Training.
Model Evaluation.

**Classification models used**

1. Logistic Regression
2. Decision Tree
3. Decision Tree with Hyperparameter tuning
4. Random Forest
5. Random Forest with Hyperparameter Tuning
6. Support vector Classification

**Conclusion**

The data modeled was quite successful in predicting the recommendation of a arline by the traveller. The accuracy was as high as 94% in case of decision tree algorithm while in case of the random forest classification algorithm the accuracy was 2nd best i.e 93.12. Hence, the chossen variables for the data are quiet well to predict the target varible.

Thankyou and Regards
Sahil D. Singh
