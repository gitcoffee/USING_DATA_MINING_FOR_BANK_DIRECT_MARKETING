# USING_DATA_MINING_FOR_BANK_DIRECT_MARKETING

# Model Performance Summary

## Model Comparison

| Model                | Train Time (s) | Train Accuracy | Test Accuracy |
|----------------------|----------------|----------------|---------------|
| Logistic Regression  | 0.2137         | 0.9085         | 0.9098        |
| KNN                  | 0.0225         | 0.9317         | 0.9014        |
| Decision Tree        | 0.1610         | 1.0000         | 0.8865        |
| SVM                  | 5.8837         | 0.8985         | 0.8945        |

## Current Results

### Logistic Regression
- **Test Accuracy**: 0.9098
- Observations: Performs well, but improving convergence methods could make it more robust.

### KNN (K-Nearest Neighbors)
- **Test Accuracy**: 0.9014
- Observations: Solid performance; scaling the data may enhance its results.

### Decision Tree
- **Test Accuracy**: 0.8865
- Observations: Achieves perfect accuracy on the training set (1.0000), suggesting potential overfitting.

### SVM (Support Vector Machine)
- **Test Accuracy**: 0.8945
- **Train Time**: 5.8837 seconds
- Observations: Good accuracy but has a significantly higher training time.

## Conclusion
Each model has its strengths and trade-offs. While Logistic Regression and KNN provide efficient training times and solid test accuracies, Decision Tree and SVM highlight the importance of balancing performance metrics with computational cost and overfitting considerations.


## Additional Resources
- [Notebook Solution on GitHub](https://github.com/gitcoffee/USING_DATA_MINING_FOR_BANK_DIRECT_MARKETING/blob/main/prompt_III_solution.ipynb)

## Conclusion
Each model has its strengths and trade-offs. While Logistic Regression and KNN provide efficient training times and solid test accuracies, Decision Tree and SVM highlight the importance of balancing performance metrics with computational cost and overfitting considerations.

