# 2025 MSA Phase 2 – Data Science Portfolio

This repository contains my submission for the **2025 Microsoft Student Accelerator (MSA)** Data Science stream.  
It highlights hands-on experience in data preprocessing, model development, and deploying optimized deep learning models.

---

## Part 1 – Exploratory Data Analysis (EDA)

The first section focuses on analyzing a store sales dataset using basic EDA techniques.

- **Cleaning and preparation:**  
  Dealt with duplicate records, managed outliers, normalized numeric values, and encoded categorical columns.

- **Data visualization:**  
  Built histograms, boxplots, and heatmaps to examine distributions and relationships.

- **Insights gained:**  
  - Profit values were sometimes negative, and sales were not evenly distributed.
  - Discounts tended to reduce profit moderately.
  - There was a weak but positive link between sales volume and profit margins.

---

## Part 2 – Building Machine Learning Models

This stage centered around developing predictive models to generate business insights.

- **Preprocessing:**  
  Filled missing entries, converted categorical data into numeric form, and scaled features.

- **Modeling and evaluation:**  
  - Applied models like **Gradient Boosting** and **Random Forests**.
  - Performance assessed using metrics such as precision, recall, F1-score, and accuracy.

- **Feature analysis:**  
  Identified which variables had the most influence on the target prediction.

- **Main results:**  
  - Built a solid model capable of generalizing well to unseen data.
  - Generated clear interpretations that could help guide decision-making.

---

## Part 3 – Model Compression via Knowledge Distillation

In the final part, I explored how to reduce model size using knowledge distillation techniques.

- **Project name:**  
  *Improving Image Classification with Knowledge Distillation: A Student-Teacher Strategy*

- **Objective:**  
  Compress a deep model by training a lightweight ResNet18 to imitate a larger ResNet34.

- **Method:**  
  - Leveraged KL divergence and cross-entropy loss with temperature scaling for soft label training.
  - Compared validation performance between teacher and student networks.

- **Outcomes:**  
  - **Teacher (ResNet34):** 94.85% accuracy, 21.8M parameters  
  - **Student (ResNet18 + KD):** 85.76% accuracy, 11.2M parameters

- **Real-world benefit:**  
  Achieved large reduction in model size with only minor accuracy loss—ideal for deploying on limited-resource devices.

---

## Project Directory

<pre><code>``` Part1/ ├── part1–submission.ipynb Part2/ ├── part2_submission.ipynb Part3/ ├── IEEE_Report_ShuoSun.docx ├── part3.ipynb ├── submission.csv README.md ``` </code></pre>


---

## Final Takeaways

This portfolio reflects my development in the following areas:

1. **Data cleaning and exploratory analysis**
2. **Supervised machine learning workflows**
3. **Efficient deep learning through model distillation**

---

*Authored by Shuo Sun – University of Auckland, July 2025.*


