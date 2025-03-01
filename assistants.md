# Hands-on Exercise: Building an AI Assistant with File Handling and Code Execution Using OpenAI's Playground

## Objective
By completing this exercise, you will:
- Create an AI assistant in OpenAI's Playground.
- Integrate file handling capabilities to enhance the assistant's knowledge base.
- Enable code execution capabilities within the assistant.
- Explore how the assistant can be used in **clinical and financial** contexts.

## Prerequisites
- **OpenAI Account:** Ensure you have an active OpenAI account.
- **Supported File Formats:** Prepare files in supported formats (e.g., `.txt`, `.csv`, `.pdf`) containing relevant data for your assistant.
- **Basic Programming Knowledge:** Familiarity with Python is beneficial but not mandatory.

## Step-by-Step Instructions

### 1. Access OpenAI's Playground

1. **Navigate to Playground:**
   - Visit the [OpenAI Playground](https://platform.openai.com/playground).

2. **Sign In:**
   - Log in using your OpenAI account credentials.

### 2. Create a New Assistant

1. **Initiate Assistant Creation:**
   - Click on the "Assistants" tab in the Playground.
   - Select "Create New Assistant."

2. **Configure Assistant Settings:**
   - **Name:** Assign a descriptive name to your assistant.
   - **Description:** Provide a brief overview of your assistant's purpose.
   - **Model Selection:** Choose a suitable model (e.g., `gpt-4-turbo`) based on your requirements.

### 3. Enable File Handling Capabilities

1. **Activate File Search Tool:**
   - In the assistant's settings, navigate to the "Tools" section.
   - Enable the "File Search" tool to allow the assistant to access and search through uploaded files.

2. **Upload Files:**  
   - Go to the "Files" section within your assistant's settings.
   - Click "Upload Files" and select the prepared files from your device.
   - Ensure the files are in supported formats and contain the data you want your assistant to utilize.

3. **Attach Files to Assistant:**  
   - After uploading, attach the files to your assistant to integrate them into its knowledge base.

### 4. Enable Code Execution Capabilities

1. **Activate Code Interpreter Tool:**  
   - In the assistant's settings, navigate to the "Tools" section.
   - Enable the "Code Interpreter" tool to allow the assistant to execute code snippets during interactions.

### 5. Test Your Assistant

1. **Interact in the Playground:**  
   - Return to the Playground interface.
   - Select your newly created assistant.
   - Enter queries or commands to test file retrieval and code execution capabilities.

2. **Example Interactions:**  
   - **File Retrieval:** Ask the assistant to summarize information from an uploaded file.
   - **Code Execution:** Request the assistant to perform a calculation or run a code snippet.

---

## **Industry-Specific Exercises: Clinicians & Bankers**

Now that you have set up your assistant, let's test how it performs on clinical and financial tasks.

### **For Clinicians (Medical Professionals)**
Test how well the assistant can process **medical knowledge, clinical data, and evidence-based decision-making.**

#### **File-Based Exercises (Using Uploaded Clinical Files)**
1. **Summarization Task:** Upload a research paper on diabetes and ask the assistant to summarize the key findings.  
   _Example:_ *"Summarize the main findings from the research paper on Type 2 Diabetes management."*  

2. **Guidelines Extraction:** Upload a clinical guideline document and ask for specific treatment recommendations.  
   _Example:_ *"What are the latest hypertension treatment guidelines from the uploaded document?"*  

3. **Patient Report Analysis:** Upload a CSV file containing anonymized patient lab results. Ask the assistant to analyze trends.  
   _Example:_ *"From the uploaded patient lab results, identify patients at risk of chronic kidney disease."*  

#### **Code-Based Exercises (Using Code Interpreter)**
4. **BMI Calculator:** Ask the assistant to generate a Python script that calculates Body Mass Index (BMI).  
   _Example:_ *"Write a Python script to calculate BMI given height and weight."*  

5. **Data Analysis:** Upload patient blood test data and ask the assistant to compute average cholesterol levels.  
   _Example:_ *"Analyze the cholesterol levels in the uploaded patient dataset and provide insights."*  

6. **Medical Image Processing (Advanced):** If working with DICOM files (medical imaging), ask the assistant to process them.  
   _Example:_ *"Analyze the uploaded DICOM file and identify abnormalities."*  

---

### **For Bankers (Finance Professionals)**
Test how the assistant can process **financial data, regulatory compliance, and investment analysis.**

#### **File-Based Exercises (Using Uploaded Financial Files)**
1. **Financial Statement Analysis:** Upload a company's financial report and ask for key insights.  
   _Example:_ *"Summarize the financial health of the company based on the uploaded balance sheet."*  

2. **Market Trends Extraction:** Upload a market report and ask the assistant to identify emerging trends.  
   _Example:_ *"From the uploaded market report, identify three key investment trends."*  

3. **Regulatory Compliance Check:** Upload a document on banking regulations and ask the assistant to check compliance for a given scenario.  
   _Example:_ *"Does the uploaded report indicate compliance with Basel III requirements?"*  

#### **Code-Based Exercises (Using Code Interpreter)**
4. **Loan Payment Calculator:** Ask the assistant to generate a Python script that calculates monthly loan payments.  
   _Example:_ *"Write a Python script to calculate mortgage payments based on principal, interest rate, and loan term."*  

5. **Stock Market Analysis:** Upload stock price data and ask the assistant to compute moving averages.  
   _Example:_ *"Analyze the stock prices from the uploaded dataset and compute the 50-day moving average."*  

6. **Portfolio Optimization (Advanced):** Ask the assistant to generate an optimal investment portfolio using Python.  
   _Example:_ *"Using the uploaded stock performance data, suggest an optimized investment portfolio."*  

---

### **Observing Model Limitations**
- **Does the assistant correctly analyze complex financial/medical documents?**  
- **Can it accurately process clinical or financial data without making misleading claims?**  
- **How well does it execute Python code for calculations and data analysis?**  
- **Does it recognize when it lacks the latest market/medical data and acknowledge uncertainty?**  

## Expected Outcome
- Successfully set up and tested an **AI assistant with file handling and code execution**.  
- Explored **how the assistant performs in clinical and financial contexts**.  
- Understood **strengths, limitations, and potential biases** in AI-generated insights.  

## Additional Resources
- [OpenAI Assistants API Overview](https://platform.openai.com/docs/assistants/overview)
- [OpenAI Assistants API Tools](https://platform.openai.com/docs/assistants/tools)
- [OpenAI Developer Community Discussions](https://community.openai.com/)

By completing this exercise, you have **built an AI assistant tailored to real-world professional tasks** in medicine and finance. Keep experimenting to refine its capabilities!  
