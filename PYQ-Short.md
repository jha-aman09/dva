**Q1 – Attempt any Ten of the following questions in brief (2.5 × 10 = 25 marks)** for the subject **Data Visualization and Analytics**:

---

### ✅ **(a) Segmentation**

Segmentation refers to the process of dividing a dataset into distinct, meaningful groups or segments based on shared characteristics. It is commonly used in marketing to segment customers by demographics, buying behavior, or usage patterns.

**Example:**
Clustering customers into segments such as "high spenders", "bargain seekers", and "brand loyalists" using algorithms like K-Means.

---

### ✅ **(b) Handling Missing Values**

Missing values in a dataset can lead to incorrect analysis if not treated properly. Common methods for handling missing data include:

* **Deletion:** Remove rows/columns with missing values (risk of losing data).
* **Imputation:** Replace missing values with:

  * Mean/Median/Mode (numerical/categorical)
  * Forward-fill/backward-fill (time series)
  * Predictive modeling (regression, KNN)

**Python Example:**

```python
df['Age'].fillna(df['Age'].mean(), inplace=True)
```

---

### ✅ **(c) Outlier Detection and Treatment**

Outliers are data points significantly different from others in a dataset. They can skew the results of statistical analyses.

**Detection Methods:**

* **Box Plot (IQR method)**
* **Z-score**
* **Scatter plot**

**Treatment:**

* Removal (if error)
* Capping/flooring (Winsorization)
* Transformation (e.g., log)

**Example:**
If the income of most users is between ₹30k–₹90k, and one entry is ₹10L, it's likely an outlier.

---

### ✅ **(d) Simpson’s Paradox**

Simpson’s Paradox occurs when a trend appears in separate groups of data but reverses when these groups are combined.

**Example:**
A treatment appears effective when viewed separately by gender but looks ineffective when data is combined. This paradox highlights the importance of analyzing subgroup behavior before drawing conclusions.

---

### ✅ **(e) P-Value**

P-value is the probability of obtaining results as extreme as the observed ones under the null hypothesis.

* **Low p-value (<0.05)**: Strong evidence against the null hypothesis
* **High p-value (>0.05)**: Weak evidence; fail to reject the null

**Example:**
In hypothesis testing for a new medicine:
H₀: Drug has no effect
H₁: Drug improves condition
If p = 0.03, we reject H₀ (the drug works).

---

### ✅ **(f) Confidence Interval**

A confidence interval provides a range within which we expect the true population parameter to lie with a certain level of confidence (e.g., 95%).

**Formula (for mean):**

$$
\bar{x} \pm Z \left(\frac{\sigma}{\sqrt{n}}\right)
$$

**Example:**
If a sample mean salary is ₹40,000 with a 95% CI of ₹38,000–₹42,000, we are 95% confident the population mean lies within this range.

---

### ✅ **(g) Correlation and Causation**

* **Correlation**: Measures the strength and direction of a linear relationship between two variables (e.g., Pearson’s r).
* **Causation**: Implies that one variable directly affects another.

**Important:** Correlation does **not** imply causation.

**Example:** Ice cream sales and drowning cases may be correlated due to summer heat but one does not cause the other.

---

### ✅ **(h) Subplots**

Subplots allow multiple visualizations in one figure to compare different data aspects.

**Python Example using Matplotlib:**

```python
fig, axs = plt.subplots(1, 2)
axs[0].plot(x1, y1)
axs[1].plot(x2, y2)
```

Useful for visual comparisons between datasets or different variables.

---

### ✅ **(i) Line Graph**

A line graph displays information as a series of data points connected by straight lines. It is commonly used for time-series data.

**Uses:**

* Tracking sales over months
* Showing temperature variation over time

**Python Example:**

```python
plt.plot(months, sales)
plt.title("Monthly Sales")
```

---

### ✅ **(j) Steps of MySQL Database Connectivity in Python**

1. Install mysql-connector using pip:

   ```bash
   pip install mysql-connector-python
   ```
2. Import module:

   ```python
   import mysql.connector
   ```
3. Establish connection:

   ```python
   conn = mysql.connector.connect(user='root', password='pass', database='db')
   ```
4. Create cursor:

   ```python
   cursor = conn.cursor()
   ```
5. Execute query:

   ```python
   cursor.execute("SELECT * FROM users")
   ```
6. Fetch data and close:

   ```python
   rows = cursor.fetchall()
   conn.close()
   ```

---

### ✅ **(k) GUI Widgets**

Widgets are elements of GUI interfaces like buttons, labels, and text fields.

**Tkinter Widgets:**

* **Label**: Display text
* **Entry**: Accept user input
* **Button**: Trigger actions

**Example:**

```python
Label(root, text="Username").pack()
Entry(root).pack()
Button(root, text="Login").pack()
```

---

### ✅ **(l) Color Palette**

A color palette is a set of colors used to enhance data visualization readability and aesthetics.

**Libraries:**

* **Seaborn**: “deep”, “muted”, “bright”, “pastel”
* **Matplotlib**: cmap options like “viridis”, “plasma”

**Usage:**

```python
sns.set_palette("muted")
```

Effective use of color improves clarity, distinguishes categories, and highlights key data.
