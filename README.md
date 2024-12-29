# Feature_Scaling

## Definition
> Feature scaling is a data preprocessing technique used to normalize the range of independent variables (features) in a dataset. It ensures that all features contribute equally to a model, regardless of their original scale or units.

## Important of Feature Scaling
>  + Equal Contribution:
> Features with larger ranges can dominate those with smaller ranges, skewing the model’s results.

> +Improved Convergence:
> Gradient-based algorithms (e.g., linear regression, logistic regression, neural networks) converge faster on scaled data.

> +Distance-Based Models:
> Algorithms like K-Nearest Neighbors (KNN) and Support Vector Machines (SVM) rely on distance metrics, which are sensitive to the scale of features.

> + Numerical Stability:
> Scaling reduces the risk of numerical instability in computations, especially with regularization techniques like Ridge and Lasso regression.

## Techniques for Feature Scaling
> 1. Standardization:
> + Transforms data to have a mean of 0 and a standard deviation of 1.
> + Suitable for algorithms assuming normally distributed data.

## Normalization:
Rescales data to a range of [0, 1].
Useful for features not following a normal distribution or when using models like KNN or SVM.

### Note: 
_Standardization works for all data types unlike Normalization_

## Formula for Standardization and Normalization
[Click here to view formula](https://ibb.co/C55ywF4)

