## 🔹 Understanding Tails in Hypothesis Testing

| Test Type        | Alternative Hypothesis | Rejection Region                |
| ---------------- | ---------------------- | ------------------------------- |
| **Two-tailed**   | $H_1: \mu \ne \mu_0$   | Both sides (±Z)                 |
| **Right-tailed** | $H_1: \mu > \mu_0$     | Right side (Z > critical value) |
| **Left-tailed**  | $H_1: \mu < \mu_0$     | Left side (Z < negative value)  |

---

## 🔸 Critical Z-values Table

| **Significance Level (α)** | **Two-Tailed (±Z)** | **Right-Tailed (Z >)** | **Left-Tailed (Z <)** |
| -------------------------- | ------------------- | ---------------------- | --------------------- |
| 0.10 (10%)                 | ±1.645              | 1.28                   | -1.28                 |
| 0.05 (5%)                  | ±1.96               | 1.645                  | -1.645                |
| 0.01 (1%)                  | ±2.576              | 2.33                   | -2.33                 |

---

## ✅ Example Use:

* **Two-tailed test at 5%**:
  Reject $H_0$ if $Z < -1.96$ or $Z > 1.96$

* **Right-tailed test at 1%**:
  Reject $H_0$ if $Z > 2.33$

* **Left-tailed test at 10%**:
  Reject $H_0$ if $Z < -1.28$

---

# Example Questions:

Great! Let’s now do **full detailed questions with step-by-step solutions** for:

1. **Z-Test** (with hypothesis testing)
2. **Min-Max Normalization** (with multiple values)

---

## 🔴 **1. Z-Test Full Question**

### 📝 **Question:**

A company claims that the **average salary** of its employees is ₹45,000. A random sample of **36 employees** shows an **average salary of ₹47,000** with a **population standard deviation (σ)** of ₹6,000.
At **5% significance level**, test whether the average salary is **actually more than ₹45,000**.

---

### ✅ **Step-by-Step Solution:**

### **Step 1: Define Hypotheses**

* Null Hypothesis $H_0$: $\mu = 45,000$
* Alternate Hypothesis $H_1$: $\mu > 45,000$

(One-tailed test)

---

### **Step 2: Given Data**

* Population mean $\mu = 45,000$
* Sample mean $\bar{x} = 47,000$
* Standard deviation $\sigma = 6,000$
* Sample size $n = 36$
* Significance level $\alpha = 0.05$

---

### **Step 3: Use Z-Test Formula**

$$
z = \frac{\bar{x} - \mu}{\sigma / \sqrt{n}}
$$

$$
z = \frac{47,000 - 45,000}{6,000 / \sqrt{36}} = \frac{2,000}{6,000 / 6} = \frac{2,000}{1,000} = 2.0
$$

---

### **Step 4: Decision Rule**

At 5% significance level (one-tailed), the **critical value** is **1.645**

* Since $z = 2.0 > 1.645$, we **reject** the null hypothesis.

---

### ✅ **Conclusion:**

There is **enough evidence** to support the claim that the average salary is **more than ₹45,000**.

---

## ✅ **Z-Test Summary Table:**

| Term                  | Value        |
| --------------------- | ------------ |
| Sample Mean (x̄)      | ₹47,000      |
| Population Mean (μ)   | ₹45,000      |
| Std. Dev (σ)          | ₹6,000       |
| Sample Size (n)       | 36           |
| Z-value               | 2.0          |
| Critical Z (α = 0.05) | 1.645        |
| Decision              | Reject $H_0$ |
