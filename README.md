# learning-log
My learning journey

# 📘 Day 1 — The Journey Begins

🎯 **First goal:** Learn the basics of statistics — the language behind data.  
Tiny steps today, but every journey begins with them.

### 📚 Today I learned:
- ✔️ The **mean** (arithmetic average)
- ✔️ The **median**, **percentiles**, and **quartiles**  
- ✔️ **Outliers** — the unexpected or extreme values  
- ✔️ The **minimum** and **maximum**

It’s a small beginning, but every bit matters.  
Onward. 🚀

# 📘 Day 2 — Diving Deeper into Dispersion

📈 **Still on my first goal:** Building a strong foundation in statistics.  
Today's focus: understanding how data varies, spreads, and where it sits.

### 📚 Today I learned:

- ✔️ **Mean** — average value  
  → `np.mean(data)`

- ✔️ **Median** — middle value in sorted data  
  → `np.median(data)`

- ✔️ **Mode** — most frequent value  
  → `stats.mode(data)`

- ✔️ **Variance** — average of squared deviations from the mean  
  → `np.var(data)`

- ✔️ **Standard deviation (std)** — average deviation from the mean  
  → `np.std(data)`

- ✔️ **Coefficient of variation (V)** — relative variability  
  → `V = np.std(data) np.mean(data)`  
  → `np.std(data) / np.mean(data)`

- ✔️ **Range (R)** — difference between max and min  
  → `R = max - min`  
  → `np.max(data) - np.min(data)`

- ✔️ **Interquartile range (IQR)** — spread of the middle 50%  
  → `IQR = Q3 - Q1`  
  → `np.percentile(data, 75) - np.percentile(data, 25)`

- ✔️ **Quartile deviation (Q)** — half of IQR  
  → `Q = IQR / 2`

- ✔️ **Quartile coefficient of variation (Vq)** — quartile-based relative variation  
  → `Vq = Q / median`

> Bonus: Plotted a histogram using `df["col"].hist()` — a fast and handy pandas shortcut.

🧰 **Working with libraries:**  
`numpy`, `pandas`, `matplotlib`, `scipy`

Each new term sharpens the picture. More tools, better insights.  
Onward. 🚀

# 📘 Day 3 — Exploring Distributions and Normalization

📈 **Still on my first goal:** Deepening my understanding of statistical distributions.  
Today I focused on distribution shapes, skewness, and normalization techniques.

### 📚 Today I learned:

- ✔️ **Normal distribution** — classic bell-shaped curve  

- ✔️ **Skewness** — measure of asymmetry in a distribution  
  - **Right-skewed (positive skewness)** — tail to the right  
  - **Left-skewed (negative skewness)** — tail to the left  
  → `scipy.stats.skew(data)`

- ✔️ **Long-tail distribution** — distributions with heavy tails

- ✔️ **Normalization techniques**:
  - **Log transformation** — `np.log_2_10(data)`
  - **Box-Cox transformation** — `boxcox(data)`
  - **Square root transformation** — `np.sqrt(data)`


- ✔️ **Histograms** — visualize data distribution  
  → `df["column"].hist()`

- ✔️ **Boxplots (box-and-whisker plots)** — visualize spread, median, and outliers  
  → `df.boxplot(vert=False, figsize=(15, 5));`
  ![image](https://github.com/user-attachments/assets/8356f31c-75cd-4b64-8af2-4d659caab645)


🧰 **Working with libraries:**  
`numpy`, `pandas`, `scipy`, `matplotlib`

> Configured pandas output for better readability:  
> `pd.set_option('display.float_format', lambda x: '%.3f' % x)`

Each adjustment to data reveals a little more of its hidden structure.  
Onward. 🚀
