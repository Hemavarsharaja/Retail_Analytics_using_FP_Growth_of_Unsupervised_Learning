# Retail_Analytics_using_FP_Growth_of_Unsupervised_Learning
📌 Project Title

Market Basket Analysis using FP-Growth Algorithm

📖 Introduction

Market Basket Analysis is a data mining technique used to analyze customer transaction data and discover patterns in purchasing behavior. It helps identify products that are frequently bought together, enabling businesses to make data-driven decisions.

This project uses the FP-Growth (Frequent Pattern Growth) algorithm, an unsupervised learning approach that efficiently discovers frequent itemsets without generating candidate sets.

🎯 Objective of the Project

To analyze customer purchase transactions

To identify frequent item combinations

To discover hidden patterns in shopping behavior

To apply unsupervised learning for pattern discovery

🧠 Algorithm Used – FP-Growth

Uses a compact FP-Tree data structure

Avoids costly candidate generation

Faster and more memory-efficient than Apriori

Suitable for large transactional datasets

🛠️ Tools & Technologies Used

Programming Language: Python

Platform: Jupyter Notebook

Libraries Used:

pandas

numpy

mlxtend

matplotlib / seaborn

📂 Dataset Description

Transaction-based retail dataset

Each row represents a customer transaction

Items purchased together are recorded per transaction

Dataset does not contain labeled output (unsupervised learning)

⚙️ Implementation Steps

Load the dataset

Preprocess data into transaction format

Apply one-hot encoding to transactions

Use FP-Growth algorithm to generate frequent itemsets

Analyze results using support values
