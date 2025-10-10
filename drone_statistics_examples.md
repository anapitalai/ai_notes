# Calculated Examples: Mean, Standard Deviation, and RMSE with Drone Data

Let's use the following example drone altitude data (in meters):

```
10, 12, 15, 13
```

---

## 1. Mean (Average)

Add up all the numbers and divide by the number of values.

**Calculation:**

Mean = (10 + 12 + 15 + 13) / 4  
Mean = 50 / 4  
Mean = **12.5 meters**

---

## 2. Standard Deviation

Standard deviation shows how much the values differ from the mean.

**Step-by-step Calculation:**

1. Find the mean (already calculated): 12.5
2. Subtract the mean from each value, then square the result:
   - (10 - 12.5)² = 6.25
   - (12 - 12.5)² = 0.25
   - (15 - 12.5)² = 6.25
   - (13 - 12.5)² = 0.25
3. Add up those squared differences: 6.25 + 0.25 + 6.25 + 0.25 = 13
4. Divide by the number of values (for population standard deviation):
   - 13 / 4 = 3.25
5. Take the square root:
   - √3.25 ≈ **1.8 meters**

---

## 3. RMSE (Root Mean Square Error)

Suppose your drone predicted altitudes:

```
Predicted: 11, 14, 14, 14
Actual:    10, 12, 15, 13
```

**Step-by-step Calculation:**

1. Find the error (difference between predicted and actual), then square each:
   - (11 - 10)² = 1
   - (14 - 12)² = 4
   - (14 - 15)² = 1
   - (14 - 13)² = 1
2. Add up squared errors: 1 + 4 + 1 + 1 = 7
3. Divide by number of values: 7 / 4 = 1.75
4. Take the square root:
   - √1.75 ≈ **1.32 meters**

---

## Summary Table

| Statistic           | Value      |
|---------------------|:----------:|
| Mean                | 12.5 m     |
| Standard Deviation  | 1.8 m      |
| RMSE                | 1.32 m     |

---

These calculations help you understand both the typical value and how much the data varies or how far off your predictions are from reality.