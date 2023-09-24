## Predicting creditworthiness for small and medium-sized enterprises

**Overview:** This project involved building a machine learning model to predict the creditworthiness for loan applicants. The model was trained on a historical dataset of loan applications, including features such as score accounting, revenues, ebitda, pfn-to-ebitda ratio, type of industry, and geographical area.

### 1. Methods:

The project mainly used two machine learning algorithms: random forests, and gradient boosting machines. 'score_accounting' and 'score_trend' have been binned. Since toward the end of the data preparation process, there were only two features left to impute, I decided to do so using not the median, but the median by the type of industry, in order to get a slightly better approximation.
In training the models, cross-validation was always performed, as well as feature selection using algorithms such as RFECV and random search.
The models were tested both with the original data (unbalanced dataset 15-85 per cent) and following undersampling at 35 and 45 per cent.

### 2. Results:

The best-performing model was a random forest algorithm, which achieved 96 per cent precision on the test set (the indicator of greatest interest to us), and 80 per cent recall. This means that the model is correct 96% of the time when it says whether or not the client has the appropriate characteristics to receive financing.
Specifically, the model was trained on the dataset on which 45 percent undersampling was performed, and without a feature selection following the preparation phase. (i.e., RFECV and random search did not allow for better generalization with this dataset.)

### 3. Impact:

This project has the potential to help Credimi Bank make more informed decisions about which loan applicants to approve. By using the model to identify high-risk borrowers, they can reduce their risk of losses, improve their overall profitability and reputation.

### 4. Conclusion:

This project demonstrates my ability to use machine learning to solve real-world problems, as well as compare my current level of knowledge with other aspiring data scientists. I am confident that the skills and experience I gained from this project will be valuable to future employers.

###The challenges you faced, and the lessons you learned###

[GitHub Repository](https://github.com/alescicluna/Rating_Score_Competition_by_Credimi-Bank/blob/main/rating_score_final_github.ipynb)
<a href="javascript:history.back()" class="text-green-600" style="weight: 5px; height: 3px; position: absolute; right: 20rem">
  &#8592; Back
</a>
