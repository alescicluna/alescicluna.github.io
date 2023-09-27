## Hack4SDS Competition: project a CV screening algorihtm

**Overview:** This project involved building a machine learning model to predict whether a NEO (Near Earth Objects) can potentially hit the Earth. The model was trained on a historical dataset which includes more than four thousand different NEOs observed and analysed together with their respective data.

### 1. Methods:

The project mainly used two machine learning algorithms: random forests, and gradient boosting machines (plus Logistic Regression as a baseline). We deleted reduntant features (e.g., 'Astronomical Units' or 'Epoch Date', which contained information already present in other features), those that contained only one value, as well as duplicates.
In training the models, cross-validation and robust scalers was performed, as well as an 50 per cent undersampling test, since the target variable was unbalanced. 

### 2. Results:

The best algorithm and the one with the most balanced results was, in general, Random Forest, which had the best results together with the dataset with less hyperparameters. This was a valuable model to limitate false negatives, even at the price of having very high false positives.
It achieved 99 per cent recall on the test set (the indicator of greatest interest to us). This means that the model is correct 99% of the time of not missing out any positive label. Specifically, the model was trained on the dataset with the least feature selection.

### 3. Impact:

This project has the potential to help the space agency understand which variables to pay more attention to, as well as a continuous monitoring tool. By using the model to identify high-risk NEOs, we can reduce the risk of an impact between an asteroid and the Earth.

### 4. Conclusion:

This project was my first test with the machine learning concepts studied during the year, together with my ability to lead a team of three. Looking back, I can say that it represented a fundamental piece of my learning.

###The challenges you faced, and the lessons you learned###

[GitHub Repository](https://github.com/alescicluna/Hack4SDS/blob/main/Hack4SDS(main).ipynb)
<a href="javascript:history.back()" class="text-green-600" style="weight: 5px; height: 3px; position: absolute; right: 20rem">
  &#8592; Back
</a>
