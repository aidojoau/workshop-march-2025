# Hands-on Exercise: Using the OpenAI Assistants API in Playground to Analyze Multiple Datasets

## Objective
By completing this exercise, you will:
- Learn how to use the **Assistants API** in OpenAI’s Playground.
- Upload and analyze datasets related to **clinical, financial, and higher education** data.
- Use the **code interpreter** tool to generate insights and visualizations from the datasets.

## Prerequisites
- **OpenAI Account**: Ensure you have access to OpenAI’s Playground.
- **Datasets**: Download the provided datasets:
  - [Clinical Dataset](sandbox:/mnt/data/clinical_dataset.csv)
  - [Financial Dataset](sandbox:/mnt/data/financial_dataset.csv)
  - [Higher Education Dataset](sandbox:/mnt/data/higher_education_dataset.csv)
- **Basic Python Knowledge** (Optional but helpful for interpreting results).

---

## Step-by-Step Instructions

### 1. Access OpenAI’s Playground

1. **Navigate to Playground:**
   - Visit the [OpenAI Playground](https://platform.openai.com/playground).

2. **Sign In:**
   - Log in using your OpenAI account credentials.

---

### 2. Create a New Assistant

1. **Go to the Assistants Tab:**
   - Click on "Assistants" in the Playground.

2. **Create a New Assistant:**
   - Click "+ Create Assistant".

3. **Configure the Assistant:**
   - **Name**: `Data Analyst Assistant`
   - **Model**: `gpt-4-turbo`
   - **Tools**: Enable **Code Interpreter** (allows Python-based data analysis).

---

### 3. Upload the Datasets

1. **Go to the Files Section:**
   - Click on “Files” in your Assistant.

2. **Upload the Datasets:**
   - Click "Upload File" and select:
     - `clinical_dataset.csv`
     - `financial_dataset.csv`
     - `higher_education_dataset.csv`

---

## **Step-by-Step Analysis for Each Dataset**

### **1. Clinical Dataset Analysis**

#### **Step 1: Load the Dataset**
Enter the following command:
```
Load the clinical dataset and display the first five rows.
```

#### **Step 2: Generate Summary Statistics**
Ask:
```
Provide summary statistics for the clinical dataset.
```

#### **Step 3: Analyze Patient Health Trends**
1. **"What is the average blood pressure of the patients?"**
2. **"Find the correlation between glucose levels and diabetes risk."**
3. **"How many patients have cholesterol levels above 200?"**

#### **Step 4: Generate Visualizations**
1. **"Plot a histogram of blood pressure levels."**
2. **"Create a scatter plot of glucose levels vs. cholesterol."**
3. **"Show a bar chart of diabetes risk categories."**

---

### **2. Financial Dataset Analysis**

#### **Step 1: Load the Dataset**
```
Load the financial dataset and display the first five rows.
```

#### **Step 2: Generate Summary Statistics**
```
Provide summary statistics for the financial dataset.
```

#### **Step 3: Analyze Financial Data**
1. **"What is the average annual income of individuals with an approved loan?"**
2. **"Find the relationship between credit score and loan approval."**
3. **"What percentage of loan applicants have a credit score below 600?"**

#### **Step 4: Generate Visualizations**
1. **"Plot a histogram of credit scores."**
2. **"Create a scatter plot showing the relationship between loan amount and credit score."**
3. **"Show a bar chart comparing loan approval rates by income level."**

---

### **3. Higher Education Dataset Analysis**

#### **Step 1: Load the Dataset**
```
Load the higher education dataset and display the first five rows.
```

#### **Step 2: Generate Summary Statistics**
```
Provide summary statistics for the higher education dataset.
```

#### **Step 3: Analyze Academic Performance**
1. **"What is the average GPA across all students?"**
2. **"Find the correlation between SAT scores and GPA."**
3. **"What percentage of students received a scholarship?"**

#### **Step 4: Generate Visualizations**
1. **"Plot a histogram of GPA scores."**
2. **"Create a scatter plot showing the relationship between SAT scores and GPA."**
3. **"Show a bar chart of the number of students in each major."**

---

### **4. Advanced Insights Across All Datasets**

Try combining data from multiple datasets for deeper insights.

1. **"Compare the average income of individuals with an approved loan to the average GPA of students who received a scholarship."**
2. **"Find out if there is any correlation between financial data and academic performance by analyzing credit scores and GPAs."**

---

## **Observing Model Limitations**
- **Does the assistant correctly analyze complex datasets?**  
- **Can it accurately process data without making misleading claims?**  
- **How well does it execute Python code for calculations and visualizations?**  
- **Does it recognize when it lacks context and acknowledge uncertainty?**  

## Expected Outcome
By following this exercise, you will:
- Successfully upload and analyze **clinical, financial, and higher education datasets** using the Assistants API.
- Extract **insights from real-world data** using AI-powered analysis.
- Understand **how AI can assist with decision-making across multiple industries**.
- Learn the **limitations of AI in predictive decision-making**.

---

## Additional Resources
- [OpenAI Assistants API Overview](https://platform.openai.com/docs/assistants/overview)
- [Using Code Interpreter in OpenAI API](https://platform.openai.com/docs/assistants/tools)
- [Data Science with Python: A Beginner’s Guide](https://realpython.com/python-data-science/)

By completing this exercise, you have **leveraged OpenAI’s Assistants API to analyze real-world datasets**, gaining insights relevant to clinical, financial, and educational professionals.
