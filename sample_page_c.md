## Hack4SDS Competition: project a CV screening algorihtm

**Overview:** This project involved the creation of a machine learning model to predict whether or not a candidate would be considered suitable to pass to the second stage of the selection process. The model was trained on a historical dataset which includes more than seventy thousand different candidates. Part of the challenge was to complete the model within 24 hours.

### 1. Methods:

The project mainly used two machine learning algorithms: random forests, and XGBoost (plus Logistic Regression as a baseline). We deleted reduntant features (which contained information already present in other features), as well as those with not useful information.
In training the models, cross-validation and robust scalers was performed. 

### 2. Results:

The best algorithm and the one with the most balanced results was, in general, Random Forest, which had the best results together with the dataset with less hyperparameters. This was a valuable model to limitate false negatives, even at the price of having very high false positives.
It achieved 99 per cent recall on the test set (the indicator of greatest interest to us). This means that the model is correct 99% of the time of not missing out any positive label. Specifically, the model was trained on the dataset with the least feature selection.

### 3. Impact:

This project has the potential to help companies fine-tune their selection process, ensuring greater focus on the most promising candidates. By using this model, they can speed up the recruitment process.

### 4. Conclusion:

This project has been particularly important in my learning journey so far, as it has allowed me to hone my leadership and teamwork skills under stress.

-- ###The challenges you faced, and the lessons you learned###

[GitHub Repository](https://github.com/alescicluna/Hack4SDS/blob/main/Hack4SDS(main).ipynb)
<a href="javascript:history.back()" class="text-green-600" style="weight: 5px; height: 3px; position: absolute; right: 20rem">
  &#8592; Back
</a>
