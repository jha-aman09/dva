# **Q2(e) Hypothesis Testing (Detailed Explanation)**  

### **1. Introduction to Hypothesis Testing**  
Hypothesis testing is a **statistical method used to make decisions or inferences about a population based on sample data**. It helps in determining whether there is enough evidence in the sample data to support a given assumption (**hypothesis**) about the population.  

📌 **Example:** A company claims that its new battery lasts **20% longer** than the old one. Hypothesis testing helps determine whether this claim is statistically valid.  

---

### **2. Key Concepts in Hypothesis Testing**  

Before diving into the process, let’s understand some fundamental terms:  

- **Null Hypothesis (\(H_0\))** – The default assumption that **there is no significant difference** or effect.  
  - 📌 **Example:** "The new drug has no effect on blood pressure."  
- **Alternative Hypothesis (\(H_1\))** – The assumption that **there is a significant difference** or effect.  
  - 📌 **Example:** "The new drug significantly lowers blood pressure."  
- **Significance Level (\(\alpha\))** – The probability of rejecting the null hypothesis when it is actually true (Type I error). Common values: **0.05 (5%) or 0.01 (1%)**.  
- **P-value** – The probability of obtaining the observed results **if the null hypothesis is true**.  
  - If **P-value < α**, reject \(H_0\) (significant result).  
  - If **P-value > α**, fail to reject \(H_0\) (not significant).  
- **Test Statistic** – A numerical value used to decide whether to reject \(H_0\) (e.g., Z-score, t-score).  

---

### **3. Steps in Hypothesis Testing**  

🔹 **Step 1: Define the Null and Alternative Hypothesis**  
   - \(H_0\): There is no difference/effect.  
   - \(H_1\): There is a difference/effect.  

🔹 **Step 2: Choose the Significance Level (\(\alpha\))**  
   - Common values: **0.05 (5%) or 0.01 (1%)**.  

🔹 **Step 3: Select the Appropriate Test and Calculate the Test Statistic**  
   - Choose **Z-test, t-test, chi-square test, ANOVA, etc.**, depending on the data type and sample size.  
   - Compute the **test statistic (Z, t, F, or χ² value)**.  

🔹 **Step 4: Compute the P-value**  
   - Determine the probability of obtaining the observed result under \(H_0\).  

🔹 **Step 5: Compare P-value with \(\alpha\) and Make a Decision**  
   - If **P-value < α**, reject \(H_0\) (significant result).  
   - If **P-value > α**, fail to reject \(H_0\) (no significant result).  

---

### **4. Types of Hypothesis Tests**  

### **A. Z-Test**  
Used when the **sample size is large (n > 30)**, and the **population standard deviation (\(\sigma\)) is known**.  

📌 **Example:** A factory claims its **light bulbs last 1,000 hours**. A random sample of 50 bulbs has an **average lifespan of 980 hours** with \(\sigma = 50\) hours. A Z-test checks if the difference is statistically significant.  

Formula for Z-score:  

\[
Z = \frac{\bar{X} - \mu}{\frac{\sigma}{\sqrt{n}}}
\]

Where:  
- \(\bar{X}\) = Sample mean  
- \(\mu\) = Population mean  
- \(\sigma\) = Population standard deviation  
- \(n\) = Sample size  

---

### **B. T-Test**  
Used when the **sample size is small (n < 30)** and the **population standard deviation is unknown**.  

#### **1. One-Sample t-Test**  
Compares a sample mean with a population mean.  

📌 **Example:** A teacher claims students score an **average of 75 marks**. A sample of **15 students** scores an average of **70 marks**. A **t-test** determines if the difference is significant.  

\[
t = \frac{\bar{X} - \mu}{\frac{s}{\sqrt{n}}}
\]

Where:  
- \(s\) = Sample standard deviation  

#### **2. Two-Sample t-Test**  
Compares the means of **two independent groups**.  

📌 **Example:** Testing whether male and female employees have different **average salaries**.  

---

### **C. Chi-Square (\(\chi^2\)) Test**  
Used for **categorical data** to check if there is an association between variables.  

📌 **Example:** A company surveys customers on **brand preference (Brand A vs. Brand B)**. A **chi-square test** determines if preferences differ by **age group**.  

\[
\chi^2 = \sum \frac{(O - E)^2}{E}
\]

Where:  
- \(O\) = Observed frequency  
- \(E\) = Expected frequency  

---

### **D. ANOVA (Analysis of Variance)**  
Used to compare **means of more than two groups**.  

📌 **Example:** A researcher compares the **exam scores of students from three different schools** to check if there is a significant difference.  

If **F-statistic** is high and **P-value < α**, at least one group differs significantly.  

---

### **5. Errors in Hypothesis Testing**  

| **Type of Error** | **Definition** | **Impact** |
|------------------|--------------|------------|
| **Type I Error (False Positive)** | Rejecting \(H_0\) when it is actually true | Example: A doctor incorrectly diagnoses a healthy patient as sick. |
| **Type II Error (False Negative)** | Failing to reject \(H_0\) when it is actually false | Example: A doctor fails to diagnose a sick patient. |

💡 **Reducing \(\alpha\) (e.g., from 0.05 to 0.01) lowers Type I errors but increases Type II errors.**  

---

### **6. One-Tailed vs. Two-Tailed Tests**  

#### **One-Tailed Test**  
- Tests for an effect in **one direction only**.  
- \(H_1\): New method is **better** than the old method.  

📌 **Example:** Testing if **new medicine reduces blood pressure** compared to the old one.  

#### **Two-Tailed Test**  
- Tests for an effect in **both directions**.  
- \(H_1\): New method is **different** from the old method (could be better or worse).  

📌 **Example:** Testing if **new medicine has any effect on blood pressure** (increase or decrease).  

---

### **7. Real-World Applications of Hypothesis Testing**  

📌 **Business:**  
- Testing whether **new marketing strategies** increase sales.  

📌 **Healthcare:**  
- Comparing effectiveness of **two different treatments**.  

📌 **Manufacturing:**  
- Ensuring product **quality meets industry standards**.  

📌 **Finance:**  
- Analyzing stock market trends to predict **investment risks**.  

---

### **8. Summary Table**  

| **Test** | **Use Case** | **Example** |
|---------|------------|------------|
| **Z-Test** | Large sample size (n > 30), known \(\sigma\) | Testing if average height of a population is 170 cm. |
| **T-Test** | Small sample (n < 30), unknown \(\sigma\) | Checking if two teaching methods produce different student scores. |
| **Chi-Square Test** | Categorical data | Analyzing customer preference for different product brands. |
| **ANOVA** | Comparing multiple group means | Testing if different diet plans lead to different weight loss results. |

---

### **9. Conclusion**  
Hypothesis testing is a powerful tool in **data analytics, research, and decision-making**. Choosing the right test **depends on sample size, data type, and research objective**.  

Would you like a **Python implementation** of any hypothesis test? 😊
