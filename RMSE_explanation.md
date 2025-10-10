# What is RMSE (Root Mean Square Error)?

**RMSE** stands for **Root Mean Square Error**. Here’s what it means in simple terms:

- Imagine you are trying to predict something, like the temperature tomorrow, and you have both your predictions and the actual temperatures.
- RMSE measures how far off your predictions are from the actual values, on average.
- It does this by:
  1. Looking at the difference between your prediction and the actual value for each example (this difference is called the "error").
  2. Squaring each error (to make sure negative and positive errors don’t cancel each other out).
  3. Averaging all those squared errors.
  4. Taking the square root of that average to get back to the original units.

**If your RMSE is low, it means your predictions are close to reality. If it’s high, they’re often far off.**

**In summary:**  
RMSE tells you, on average, how much your predictions differ from what actually happened. It’s a common way to measure the accuracy of models in fields like data science and machine learning.

# What is RMSE (Root Mean Square Error)?

**RMSE** stands for **Root Mean Square Error**. Here’s what it means in simple terms:

- Imagine you are trying to predict something, like the temperature tomorrow, and you have both your predictions and the actual temperatures.
- RMSE measures how far off your predictions are from the actual values, on average.
- It does this by:
  1. Looking at the difference between your prediction and the actual value for each example (this difference is called the "error").
  2. Squaring each error (to make sure negative and positive errors don’t cancel each other out).
  3. Averaging all those squared errors.
  4. Taking the square root of that average to get back to the original units.

**If your RMSE is low, it means your predictions are close to reality. If it’s high, they’re often far off.**

**In summary:**  
RMSE tells you, on average, how much your predictions differ from what actually happened. It’s a common way to measure the accuracy of models in fields like data science and machine learning.

---

## Example of the RMSE Formula

Suppose you are comparing predicted elevation values to actual elevation values:

**Actual elevation:** 100, 105, 110, 120  
**Predicted elevation:** 98, 108, 111, 115

The RMSE formula is:

\[
RMSE = \sqrt{\frac{1}{N} \sum_{i=1}^{N} (Predicted_i - Actual_i)^2}
\]

**Step-by-step calculation:**

1. Find the squared difference for each pair:
   - (98 - 100)² = 4
   - (108 - 105)² = 9
   - (111 - 110)² = 1
   - (115 - 120)² = 25

2. Add them up: 4 + 9 + 1 + 25 = 39

3. Divide by the number of data points (N = 4): 39 / 4 = 9.75

4. Take the square root: √9.75 ≈ **3.12**

So, the RMSE for these elevation predictions is **3.12**.
