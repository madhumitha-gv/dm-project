### Intelligent System for Inventory Demand Forecasting

Problem Statement

Develop a comprehensive inventory analysis platform that processes order demand data to identify patterns, detect outliers, and optimize inventory management decisions. The system utilizes statistical analysis and visualization techniques to provide insights into inventory distribution and help businesses make data-driven decisions for their supply chain management.

Tech Required

1. Analytical Skills
- Data Analysis:
  - Use tools like Pandas for data manipulation and exploratory data analysis
  - Implement statistical methods for outlier detection
- Statistical Analysis:
  - Perform distribution analysis and data transformation
  - Calculate descriptive statistics for inventory metrics

2. Data Visualization
- Box Plot Analysis:
  - Create visual representations of data distribution
  - Display outliers and quartile information
- Transformation Visualization:
  - Show effects of log transformation on data distribution
  - Compare original and transformed data patterns

3. Statistical Methods
- Outlier Detection:
  - Implement IQR-based outlier identification
  - Analyze extreme values in order demand
- Data Transformation:
  - Apply logarithmic transformation for better data interpretation
  - Normalize data distribution for analysis

Tech Stack

Frontend
- Matplotlib
- Jupyter Notebook
- Python Data Visualization Libraries

Backend
- Python
- NumPy
- Pandas

Project Team Members
Madhumitha Gannavaram
Lahari Gandrapu
Sreeja Pasupuleti

Summary
The Inventory Analysis System is a data-driven tool designed to help businesses understand their order demand patterns and optimize inventory management. Through advanced visualization and statistical analysis, it provides clear insights into data distribution and identifies unusual patterns in order demands.

Key Features

 1. Distribution Analysis
- Visualize order demand distribution through box plots
- Identify data spread and central tendencies

 2. Outlier Detection
- Automatically detect and visualize outliers in order demands
- Provide statistical measures for unusual patterns

 3. Data Transformation
- Implement log transformation for better data visualization
- Normalize skewed distributions for analysis

 4. Statistical Insights
- Calculate key statistical measures
- Provide comprehensive data summaries

 5. Visual Analytics
- Generate clear and informative box plots
- Compare original and transformed data distributions

 6. Data Processing
- Handle large datasets efficiently
- Process and clean inventory data

How to Run the Project

### **1. Set up Python Environment**
```bash
python -m pip install --upgrade pip
```

### **2. Install Required Libraries**
```bash
pip install pandas numpy matplotlib
```

### **3. Import Dependencies**
```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
```

### **4. Load and Process Data**
```python
data = pd.read_csv('final_food.csv')
```

### **5. Generate Visualizations**
```python
plt.figure(figsize=(12, 6))
plt.boxplot(data['Order_Demand'])
```

