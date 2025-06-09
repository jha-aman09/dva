## 🔴 **2. Min-Max Normalization Full Question**

### 📝 **Question:**

Normalize the following student scores using **Min-Max scaling** to the range **\[0, 1]**:

$$
Scores = [50,\ 60,\ 70,\ 80,\ 90]
$$

---

### ✅ **Step-by-Step Solution:**

### **Step 1: Identify Min and Max**

* Minimum = 50
* Maximum = 90

---

### **Step 2: Use Min-Max Formula**

$$
x' = \frac{x - \min(x)}{\max(x) - \min(x)}
$$

---

### **Step 3: Normalize Each Score**

| Original Score (x) | $x' = \frac{x - 50}{90 - 50}$ | Normalized Value |
| ------------------ | ----------------------------- | ---------------- |
| 50                 | $\frac{0}{40} = 0$            | 0.00             |
| 60                 | $\frac{10}{40} = 0.25$        | 0.25             |
| 70                 | $\frac{20}{40} = 0.5$         | 0.50             |
| 80                 | $\frac{30}{40} = 0.75$        | 0.75             |
| 90                 | $\frac{40}{40} = 1$           | 1.00             |

---

### ✅ **Final Table:**

| Original Score | Normalized Score (0–1) |
| -------------- | ---------------------- |
| 50             | 0.00                   |
| 60             | 0.25                   |
| 70             | 0.50                   |
| 80             | 0.75                   |
| 90             | 1.00                   |

---

### 📌 **Interpretation:**

* All scores are now between 0 and 1.
* This helps in machine learning models or comparison where data must be on the same scale.

---

## 🟢 Want More?

I can also give:

* Same question using Excel or Python
* Min-Max normalization to a custom range (like \[5, 10])
* Z-test using sample standard deviation (i.e., **t-test**)

Let me know!
