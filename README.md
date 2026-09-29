# BH-PCMLAI-Practical-Assignment-17.1
This repository contains code for the practical application assignment 17.1
<br>-Manali Parmar

Link to [the notebook](https://github.com/manali-parmar/BH-PCMLAI-Practical-Assignment-17.1/blob/main/Assignment%2017.1.ipynb).

<div class="recommendations">
  <h2>Based on the analysis, here are the findings:</h2>
  <ol>
    <li>
      <p>The dataset is highly imbalanced, with very fewer customers subscribing to a term deposit 'yes' than declining 'no'. Therefore, I used F1 score alongside accuracy to better evaluate performance on the minority class.</p>
    </li>
    <li>
      <p>Four classification models were evaluated: Logistic Regression, K-Nearest Neighbors (KNN), Decision Tree, and Support Vector Machine (SVM)</p>
    </li>
    <li>
      <p>When specifically evaluating the important minority yes class, Logistic Regression performed substantially better, achieving an F1 score of 0.253, compared with Decision Tree (0.049), KNN (0.041), and SVM (0.017)</p>
    </li>
     <li>
      <p>The selected Logistic Regression model's confusion matrix produced 579 true positives and 349 false negatives, meaning it identified 579 customers who actually subscribed. However, it also generated 3,079 false positives, showing a trade-off between identifying potential subscribers and incorrectly targeting non-subscribers.</p>
    </li>
    <li>
      <p>Overall, the results demonstrate that model selection should not be based on accuracy alone for an imbalanced dataset. Logistic Regression provided the most useful performance for identifying the minority 'yes' class among the tested models, although the relatively low F1 score indicates room for improvement.</p>
    </li>
