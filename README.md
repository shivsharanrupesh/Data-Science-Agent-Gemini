# Google's Data Science Agent in Colab Powered by Gemini. 

Google's **Data Science Agent in Colab**, powered by **Gemini**, automates tedious setup tasks like:  
- Importing libraries  
- Loading data  
- Writing boilerplate code  

Initially available to **trusted testers**, it has proven to **streamline workflows and accelerate insights**.  

## EDA on Customer Churn Prediction Dataset  

Recently tested out **EDA on Customer Churn Prediction Dataset** using **Google's Data Science Agent (Gemini Utility) in Google Colab Notebook**.  

### **Why Use Google's Data Science Agent?**  
- Allows users to perform **Exploratory Data Analysis (EDA)** efficiently by simply **providing a well-structured prompt**.  
- Eliminates the need for extensive coding while ensuring a **thorough understanding of the data**.  
- Automates dataset analysis, trend visualization, and insight generation, significantly **reducing manual effort**.  

## **Steps Performed by the Agent**  

### **1. Data Overview:**  
- Checked total number of **records, columns, and data types**.  
- Detected and handled **missing values** and **duplicate entries**.  

### **2. Summary Statistics & Data Cleaning:**  
- Generated **descriptive statistics** (mean, median, standard deviation, min-max values, unique counts).  
- Separated **categorical and numerical variables** for better insights.  
- Identified and treated **outliers** using **boxplots and the Interquartile Range (IQR) method**.  

### **3. Data Visualization & Insights:**  
- **Histograms & KDE Plots:** Explored feature distributions to identify **skewness**.  
- **Boxplots:** Detected potential **outliers** in numerical features.  
- **Count Plots:** Analyzed **categorical feature distributions**, particularly for the **churn column**.  
- **Pairplots:** Visualized **feature relationships**.  
- **Correlation Heatmap:** Showed relationships between variables, identifying **highly correlated features** that might affect model performance.  

### **4. Statistical Analysis:**  
- **Skewness & Kurtosis:** Computed to understand the shape of distributions.  
- **Normality Tests:** Applied **Shapiro-Wilk** and **Kolmogorov-Smirnov** to determine if key features followed a **normal distribution**.  

### **5. Key Findings & Observations:**  
- **High correlation** detected in certain features, suggesting possible **multicollinearity**.  
- **Class imbalance** in the churn variable, which might impact model predictions.  
- **Outliers** in transaction amounts and customer activity required careful handling to **prevent model bias**.  

---

## **Note:**  
🔹 **Google's Data Science Agent (Gemini Utility) in Google Colab is designed to assist humans, not replace them.**  
🔹 It helps automate repetitive tasks like **importing libraries, loading data, and generating boilerplate code**, allowing users to focus on deeper analysis and insights.  
🔹 However, **human expertise remains crucial**—users can **modify, customize, and refine** the generated code as needed.  
🔹 This tool is meant to **enhance productivity** by streamlining workflows, not eliminating the need for **critical thinking and problem-solving**.  

## **Notebook:**  
📌 https://github.com/CodeCipheAI/Data-Science-Agent-Gemini/blob/main/Bank_Churn_Prediction.ipynb

