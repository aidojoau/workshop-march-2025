# Hands-on Exercise: Using OpenAI’s Playground to Generate Custom Datasets

## Objective
By completing this exercise, you will:
- Learn how to use **OpenAI’s Playground** to create structured datasets.
- Generate **clinical, financial, and educational datasets** dynamically.
- Use **AI-assisted data generation** for research, modeling, or prototyping.

## Prerequisites
- **OpenAI Account**: Ensure you have access to OpenAI’s Playground.
- **Basic Understanding of Data Structure**: Knowing how tabular data works (rows & columns) will help.

---

## Step-by-Step Instructions

### 1. Access OpenAI’s Playground

1. **Navigate to Playground:**  
   - Visit the [OpenAI Playground](https://platform.openai.com/playground).

2. **Sign In:**  
   - Log in using your OpenAI account credentials.

---

### 2. Create a Structured Dataset

1. **Select a Model:**  
   - Choose **GPT-4 Turbo** for **high-quality structured output**.

2. **Define a Dataset Type:**  
   - Decide what kind of dataset you need (e.g., clinical, financial, educational).

3. **Enter a Prompt to Generate a Dataset:**  
   - Example prompt for **clinical data generation**:  
     ```
     Generate a structured dataset with 20 rows and 6 columns for patient data.
     Columns: Patient ID, Age, Blood Pressure (mmHg), Cholesterol Level (mg/dL), Glucose Level (mg/dL), Diabetes Risk (High/Normal).
     Output in CSV format.
     ```

   - Example prompt for **financial data generation**:  
     ```
     Generate a structured dataset with 20 rows and 5 columns for personal loan applicants.
     Columns: Account ID, Annual Income ($), Credit Score, Loan Amount ($), Loan Approval (Approved/Denied).
     Output in CSV format.
     ```

   - Example prompt for **higher education data generation**:  
     ```
     Generate a structured dataset with 20 rows and 5 columns for university students.
     Columns: Student ID, Age, GPA, SAT Score, Scholarship Awarded (Yes/No).
     Output in CSV format.
     ```

4. **Run the Prompt & Copy the Output:**  
   - The AI will return structured tabular data.  
   - Copy and paste it into a `.csv` file for further use.

---

### 3. Save and Use the Dataset

1. **Copy the Generated Data into a CSV File:**  
   - Open a text editor or spreadsheet software.  
   - Paste the AI-generated data.  
   - Save it as `custom_dataset.csv`.

2. **Upload and Analyze the Dataset in OpenAI’s Assistants API:**  
   - Follow the dataset analysis steps from the previous exercises to explore insights.

---

## Example Prompts for Different Fields

### **Healthcare Dataset**
```
Generate a dataset of 50 patient records with the following fields:
- Patient ID (Unique)
- Age (18-90)
- BMI (Body Mass Index)
- Blood Sugar Levels (mg/dL)
- Diagnosis (Hypertension, Diabetes, Normal)
Format as CSV.
```

### **Stock Market Dataset**
```
Generate a dataset of 30 stock prices over a month.
Columns: Date, Company Name, Opening Price ($), Closing Price ($), Daily Percentage Change.
Output in CSV format.
```

### **Retail Sales Dataset**
```
Create a dataset of 100 sales transactions.
Columns: Transaction ID, Date, Product Category, Price ($), Quantity Sold.
Format as CSV.
```

---

## Expected Outcome
By following this exercise, you will:
- Generate **custom datasets** using **AI in OpenAI’s Playground**.
- Save and analyze structured data for **research, finance, or clinical insights**.
- Gain hands-on experience in **AI-assisted data generation**.

---

## Additional Resources
- [OpenAI Playground Guide](https://platform.openai.com/playground)
- [OpenAI API Documentation](https://platform.openai.com/docs/overview)
- [Understanding Tabular Data](https://www.datacamp.com/community/tutorials/pandas-tutorial-dataframe-python)

By completing this exercise, you now know **how to generate structured datasets with AI** for analysis, research, or training models. 🚀
