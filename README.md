# Chi-Square-Test-for-Analyzing-the-Relationship-Between-Study-Habits-and-Exam-Confidence  

## 📝 __Overview__  
This project investigates whether students who spend more time studying feel more confident about their exam performance. It uses a simulated dataset of 250 student responses, categorizing both study hours and exam confidence on an ordinal scale.  
  
📊 The Chi-Square Test of Independence is applied as the core statistical method, ideal for examining the relationship between two categorical variables.  
📊 The data was randomly generated to reflect possible real-world survey responses, and the entire analysis is performed in Python using Google Colab.  
📊 This test helps determine whether the observed association between study habits and confidence is statistically meaningful or just due to chance.  
    
💡 Other Use Cases for A/B Testing:  
* Testing email subject lines for better open rates.  
* Comparing two app layouts to reduce user drop-off.  
* Measuring the impact of pricing strategies on sales.  
* Evaluating different call-to-action buttons for signup rates.  
  
## __📂 Contents__  
|    File Name     | File Type | Description |
|------------------|-----------|-------------|
|      README      |    MD     | Read this before anything else |
| Student_Study_vs_Confidence_250 |    XLSX    | Dataset used for analysis |
| Code_Chi_Square_Test |   IPYNB   | Python Notebook |
  
## __▶️ How to Execute the Program__
Before executing the program, download the XLSX file `Student_Study_vs_Confidence_250` and the IPYNB file `Code_Chi_Square_Test` from this repository. Afterwards, follow these steps:  
### If you are using Google Colab:  
•	Upload the downloaded files to a folder in your Google Drive.  
•	Open a browser and go to https://colab.research.google.com.  
•	Click on File > Upload Notebook.  
•	Select and open the downloaded IPYNB file.  
•	Click on the run button adjacent to each code snippet to run the code.  
### If you are using Jupyter Notebook:  
•	If you don’t have Anaconda or Jupyter Notebook installed, visit: https://www.anaconda.com and download the installer appropriate for your OS.  
•	After downloading, double-click on the downloaded file and follow the on-screen instructions to complete the installation process.  
•	Locate and run the program ‘Anaconda Prompt’.  
•	Run Jupyter Notebook after navigating to the folder containing the downloaded IPYNB file and the CSV file. For instance, if the files are located in a folder called PythonCode in Local Disk (D:), then you have to run _D:\PythonCode>jupyter notebook_.  
•	After opening the IPYNB file, select the code snippets and click on Run to run the code.  
  
## 🔍 __Observation__  
* The contingency table summarizes responses from 250 students, categorized by study hours and exam confidence levels.  
* The chi-square statistic is approximately 19.90, with 16 degrees of freedom.  
* The p-value is 0.225, which is greater than the 0.05 significance level, indicating that there is no statistically significant association between study hours and exam confidence.  
* All expected frequencies are greater than 5, satisfying a key assumption of the chi-square test.  
* The results suggest that, based on this dataset, students' confidence levels are likely independent of how much they study.  
  
## 📌 __Things to Keep in Mind__  
* Significance level used: 5% (α = 0.05)  
* Both variables are categorical and measured on an ordinal scale.  
* Ensure random sampling or simulation mimics realistic distributions.  
* Ensure data integrity—no missing values in key columns.  
* The chi-square test does not measure strength or direction of relationship—only whether an association exists.  
* Modify the file path if you're reading the dataset from your own Drive in Colab.  
