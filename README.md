# Statistical Analysis and Simulation Projects in R

This repository contains two mini-projects focused on foundational statistical concepts, probability distributions, data visualization, and hypothesis testing implemented in **R**.

---

## 📁 Project 1: Distribution Comparison & CLT Demonstration

This project explores the properties of random exponential distributions and demonstrates the practical application of the **Central Limit Theorem (CLT)**.

### Key Highlights:
* **Exponential Distribution Analysis:** Generates random exponential samples (rate=0.2), calculates sample means and variances, and compares them against theoretical expectations.
* **Central Limit Theorem:** Demonstrates that while a single sample of exponential numbers is heavily skewed, the distribution of multiple sample means approximates a normal (Gaussian) distribution.
* **Normality Diagnostics:** Evaluates distribution shape using **Skewness** and **Kurtosis** metrics alongside **Normal Q-Q Plots**.
  
<img width="878" height="546" alt="1" src="https://github.com/user-attachments/assets/dbe0cca1-34fa-4811-aebf-fafb25cebc45" />

[See the Project 1](project_1.Rmd)

---

## 📁 Project 2: Statistical Descriptive Analysis & Hypothesis Testing

This project conducts an exploratory data analysis and hypothesis testing pipeline using the built-in **`ToothGrowth`** dataset, investigating the effects of vitamin C delivery methods and dosages on tooth growth.

### Key Highlights:
* **Data Exploration:** Examines data structures, summary statistics, and data types (`len`, `supp`, `dose`).
* **Data Visualization:** Utilizes `ggplot2` to create custom boxplots (`geom_boxplot`) illustrating teeth length distributions across supplement categories.
* **Hypothesis Testing (Welch's Two-Sample t-tests):**
  * Evaluated differences between supplement types (`OJ` vs. `VC`).
  * Tested dose-dependent growth effects (`0.5 vs. 1.0` and `1.0 vs. 2.0` mg/day) using one-sided directional hypotheses.
  * Analyzed interaction effects at specific dosage levels (e.g., `dose = 2`).

<img width="876" height="542" alt="2" src="https://github.com/user-attachments/assets/902c5025-dc17-4e35-a5ba-1855537f7afb" />

[See the Project 2](project_2.Rmd)

---

## 🛠️ Tech Stack & Libraries
* **Language:** R
* **Core Libraries:** 
  * `tidyverse` (Data manipulation and visualization via `ggplot2`)
  * `e1071` (Skewness and Kurtosis calculations)
  * `car` (Statistical diagnostics)
