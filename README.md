# Home-Credit

## Description

Home Credit Analysis from Kaggle https://www.kaggle.com/c/home-credit-default-risk/submissions?sortBy=date&amp;group=all&amp;page=1

Many people struggle to get loans due to insufficient or non-existent credit histories. And, unfortunately, this population is often taken advantage of by untrustworthy lenders.

Home Credit Group

Home Credit strives to broaden financial inclusion for the unbanked population by providing a positive and safe borrowing experience. In order to make sure this underserved population has a positive loan experience, Home Credit makes use of a variety of alternative data--including telco and transactional information--to predict their clients' repayment abilities.

While Home Credit is currently using various statistical and machine learning methods to make these predictions, they're challenging Kagglers to help them unlock the full potential of their data. Doing so will ensure that clients capable of repayment are not rejected and that loans are given with a principal, maturity, and repayment calendar that will empower their clients to be successful.


## Evaluation

Submissions are evaluated on area under the ROC curve between the predicted probability and the observed target.

Submission File
For each SK_ID_CURR in the test set, you must predict a probability for the TARGET variable. The file should contain a header and have the following format:

SK_ID_CURR,TARGET
100001,0.1
100005,0.9
100013,0.2
etc.