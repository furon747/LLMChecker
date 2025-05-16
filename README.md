# 🧠 LLM Message Detector
*A model designed to detect messages generated with a tool like Chat GPT*

## 🔍 Overview  
**Goal:** This project was designed to make a prediction of whether a given input message was generated with an LLM such as Chat GPT.  
**Tech Used:** Python, PyTorch, SciKit Learn, Numpy 
**Status:** `Completed` 

## 📊 Sample Output  

Input (truncated): There is no one-size-fits-all answer to whether overwriting old data in a data warehouse is best practice. It depends on factors such as data retention policies,
data quality requirements, storage considerations, compliance obligations, and business use cases. Further, overwriting old data increases the risk of losing valuable historical
information, so it's important to have processes in place to recover data if needed. It's essential to carefully evaluate these factors and implement a data management strategy
that aligns with your organization's needs and objectives. Also, matching new data to old data in a data warehouse when they are from two different platforms can be challenging
but feasible with the right approach. Some of the strategies used would be: Standardization of Data Formats: Ensure that data from both platforms are in a standardized format or
can be transformed into a common format. This might involve converting data types, standardizing naming conventions, and ensuring consistent structures.
```
Output: I am 95.6561% confident this message was written by an LLM
```

---

## 🚀 Features  
- Dynamic filtering using DAX  
- Responsive dashboard layout  
- Custom KPIs and trend analysis  
- SQL views to normalize raw data  

---

## 🧩 Technologies  
- `Python`, `Pandas`  
- `SQL`, `SQLite`  
- `Power BI`, `DAX`  
- *(Update based on your stack)*

---

## 📁 Dataset  
- [Sample Sales Data from Kaggle](https://www.kaggle.com/)

---

## 🧠 What I Learned  
This project helped me solidify my understanding of Power BI's data modeling and visualization capabilities. I also gained hands-on experience with DAX formulas and SQL joins to prepare the dataset for analytics.

---

## 📌 How to Run  
```bash
# Step 1: clone the repo
git clone https://github.com/your-username/project-name.git

# Step 2: install dependencies (if needed)
pip install -r requirements.txt

# Step 3: run or open your file

