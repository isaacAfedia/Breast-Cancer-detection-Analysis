# Breast-Cancer-detection-Analysis
Predictive analysis of Breast cancer to classify if its malignant or benign using its physical attributes.
1. Problem Statement
Breast Cancer Prediction Using the physical attributes.
2. Dataset Description
> The Cancer Prediction Dataset contains features computed from a digitized image of a fine needle aspirate of a breast mass. They describe the characteristics of the Cell Nuclei
> Input variables are area mean, radius mean, perimeter mean, compactness mean, concavity mean, concave points mean, radius worst, Perimeter worst, area worst, compactness worst concavity worst and concave points worst. 
And my Target is: Diagnosis 
I split and trained my data using this description.
> 3. Dataset Analysis and Observations
 ![image](https://github.com/isaacAfedia/Breast-Cancer-detection-Analysis/assets/124618169/3623d502-d7de-495f-a44a-b3e3d1d4a892)


4. Proposed Prediction Model
> With my analysis on the dataset, I have independent features that directly can significantly affect cancer diagnosis
> My dataset is clearly a classification dataset that why I am using the Logistic Regression and Perceptron Models to predict breast cancer and then I compared both of their performances
5. Results and Discussions
Below gives a summary of the result as both models were good, the logistic regression model produced a better F1-score and Accuracy than the perceptron model.
You can also find the precision, macro and weighted average.
It is also good to note that the Perceptron model is bias to the Malignant.
![image](https://github.com/isaacAfedia/Breast-Cancer-detection-Analysis/assets/124618169/b31a7fe2-cea3-49da-b3d0-fbdcfebd8934)

The above plots show the performance of the models against each other with logistic regression doing way better.
CONCLUSION:
•	In conclusion, Logistic regression has a better performance than Perceptron model with respect to f1-score and Accuracy in prediction if a tumor is Malignant or Benign. Thus, the Logistic Regression Model is better for this data Evaluation.
