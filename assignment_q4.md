**Comparing MLP against RF and Logistic Regression models using F1-score**

F1 scores of :

a. MLP : 0.9221047126872927

b. Random Forest : 0.9704722695987773

c. Logistic Regression : 0.9210516141720867

*Observations*

1. Random Forest outperforms both MLP and Logistic Regression in terms of F1 score, with the highest F1 score of 0.9705.

2. MLP performs slightly better than Logistic Regression, with an F1 score of 0.9221 compared to 0.9211.

3. The F1 scores of MLP and Logistic Regression are relatively close, suggesting that the complexity of the MLP architecture might not be necessary for achieving comparable performance to Logistic Regression on this dataset.*

**Comparing MLP against RF and Logistic Regression models using Confusion matrix**

1. Random Forest have the fewest misclassifications overall, as indicated by smaller off-diagonal values in the confusion matrix.

2. MLP and Logistic Regression also perform well overall, but they seem to have slightly more misclassifications compared to Random Forest.

3. MLP tends to have a higher number of misclassifications across various classes. There are noticeable off-diagonal values in almost every row, indicating misclassifications across different digits. 
 
4. Random Forest misclassifications seem to be more sporadic, with some digits having very few misclassifications and others having slightly more.

5. Logistic Regression also shows misclassifications across various classes, although the distribution of errors might be slightly different from MLP.

6. In MLP, 2 is mostly misclassified as 3, 4 as 9 and 8 as 5.

7. In Logistic Regression, 2 is mostly misclassified as 8, 5 as 3, 4 and 7 as 9.

8. In RF, 7 is mostly misclassified as 2, 4 as 9.

**What all digits are commonly confused?**

1. The most common digit confused in all three models is 5.(next one is 8)

2. MLP - 5, 8, 2 , RF - 5 , Log Reg -  5, 8 

 **Contrast this with the t-SNE for the same layer but for an untrained model. What do you conclude?**
- relation b/w digits
- learned embeddings

 **Now, use the trained MLP to predict on the Fashion-MNIST dataset. What do you observe? How do the embeddings (t-SNE viz for the second layer compare for MNIST and Fashion-MNIST images)**
- 

 
