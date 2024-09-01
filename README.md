## Purpose of Min-Max Scaling

Min-Max Scaling, also known as normalization, is used to transform features to a common scale, typically [0, 1]. This scaling ensures that all features have the same scale, which is crucial for algorithms that are sensitive to the scale of input data, such as k-nearest neighbors (KNN) and gradient descent-based methods.

## Procedure

Given a dataset with features \(x_i\) where \(x_i\) represents the \(i\)-th feature, the Min-Max Scaling procedure is as follows:

1. **Determine the Minimum and Maximum Values:**

   For each feature \(x_i\), compute the minimum value \(x_{min}\) and maximum value \(x_{max}\).

2. **Apply the Scaling Formula:**

   Transform each value \(x\) of the feature \(x_i\) using the formula:
   \[
   x_{scaled} = \frac{x_i - x_{min}}{x_{max} - x_{min}}
   \]
   where \(x_{scaled}\) is the scaled value.

3. **Result:**

   After applying the above formula, each feature \(x_i\) will be scaled to the range [0, 1].
