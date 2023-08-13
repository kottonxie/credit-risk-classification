# credit-risk-classification

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* **Explain the purpose of the analysis:** The purpose of this analysis is to grade the model on how accurate it is at predicting the creditworthiness of borrowers!

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Balanced Accuracy Score: At 95.2%, the balanced accuracy score indicates that the model is pretty good at being able to correctly predict both positive and negative cases! 
  * Precision: In terms of precision, the model is able to predict positively predicted labels that are actually correct at 92%.
  * Recall scores: On the other hand, the recall score of the model is 95% accurate at correctly identifying positive instances out of all the actual positive instances in the dataset.



* Machine Learning Model 2:
  * Balanced Accuracy Score: At 99.4%, the oversampled model is even better at correctly predicting than the first model.
  * Precision: The oversample model's precision is scored at 92%, which is the same as the first model.
  * Recall scores: This recall score goes up to 99%, which is a great improvement compared to model 1.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
  * Overall, it looks like Model 2 performed better with a higher balanced accuracy score and a higher recall score.
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
  * Yes, Predicting 1's or 0's is significant depending on the context. In medical diagnosis, predicting the presence of disease (which would be a 1) is crucial. In spam classification, predicting non-spam emails (which is a 0) is more important.

In conclusion, I would pick Machine Learning Model 2, the oversamples model, due to the better performance on its prediction. 
