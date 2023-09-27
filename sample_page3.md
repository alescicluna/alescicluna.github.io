## Asteroids Classification: detecting NEOs (Near Earth Objects)

**Overview:** This project involved building a machine learning model to predict whether a NEO (Near Earth Objects) can potentially hit the Earth. The model was trained on a historical dataset which includes more than four thousand different NEOs observed and analysed together with their respective data.

### 1. Methods:

The project mainly used two machine learning algorithms: random forests, and gradient boosting machines (plus Logistic Regression as a baseline). We deleted reduntant features (e.g., 'Astronomical Units' or 'Epoch Date', which contained information already present in other features), those that contained only one value, as well as duplicates.
In training the models, cross-validation and robust scalers was performed, as well as an 50 per cent undersampling test, since the target variable was unbalanced. 

### 2. Results:

The best-performing model was a random forest algorithm, which achieved 96 per cent precision on the test set (the indicator of greatest interest to us), and 80 per cent recall. This means that the model is correct 96% of the time when it says whether or not the client has the appropriate characteristics to receive financing.
Specifically, the model was trained on the dataset on which 45 percent undersampling was performed, and without a feature selection following the preparation phase. (i.e., RFECV and random search did not allow for better generalization with this dataset.)

### 3. Impact:

This project has the potential to help the space agency understand which variables to pay more attention to, as well as a continuous monitoring tool. By using the model to identify high-risk NEOs, we can reduce the risk of an impact between an asteroid and the Earth.

### 4. Conclusion:

This project was my first test with the machine learning concepts studied during the year, together with my ability to lead a team of three. Looking back, I can say that it represented a fundamental piece of my learning.

###The challenges you faced, and the lessons you learned###

[GitHub Repository](https://github.com/alescicluna/Asteroids-Classification-Project)
<a href="javascript:history.back()" class="text-green-600" style="weight: 5px; height: 3px; position: absolute; right: 20rem">
  &#8592; Back
</a>
