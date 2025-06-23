# AUTOMATED-REPORT-GENERATION

COMPANY: CODETECH IT SOLUTIONS

NAME: PATEL DIYA 

INTERN ID :CT04DF1541

DOMAIN: PYTHON PROGRAMMING

DURATION: 4 WEEKS

MENTOR: NEELA SANTOSH

## TASK DESCRIOTON:
This project is a Python-based data analysis and automated reporting application. It extracts, visualizes, and summarizes passenger data from the well-known Titanic dataset. The finished product is a well-organized PDF report with a pie chart showing the distribution of genders and important statistics. This project shows how to easily and successfully integrate data analysis, visualization, and automated document creation.

**Project Overview**
One of the most often used datasets for data science and machine learning education is the Titanic dataset. It includes information on the demographics and survival rates of Titanic passengers. This project's objective is to evaluate the data and automatically provide a visual report, not to forecast survival. After processing the dataset and extracting key insights, the Python script uses Matplotlib to produce visualizations and the ReportLab package to output the results into a PDF report with a polished appearance. Included in the report are:
- Total number of passengers
- Average age of passengers
- Average fare paid
- Count of male and female passengers
- A pie chart showing gender distribution

**Tools and Technologies**
- Python 3.x
- Pandas – for data manipulation and summary statistics
- Matplotlib – for generating the pie chart visualization
- ReportLab – for creating and formatting the PDF file

**How It Works**
- Data Loading: The dataset (test.csv) is loaded using Pandas.
- Data Analysis: Key statistics like total passengers, average age, fare, and gender count are calculated.
- Visualization: A gender distribution pie chart is created and saved as an image (gender_pie.png).
- PDF Report Generation: The generate_pdf() function uses ReportLab to format the title, write text, and embed the pie chart into the final report Titanic.pdf.

**How to Run**
All you need is Python installed on your computer to complete this project.  First, execute `pip install pandas matplotlib reportlab` in your terminal or command prompt to ensure that the necessary libraries are installed. The Titanic dataset (called `test.csv`) should then be placed in the same folder as your Jupyter notebook or Python application. You have two options: open the notebook and run each cell individually, or use the command `python report_generator.py` to run the `.py` file.  After processing the data, the script will automatically produce a PDF report called `Titanic.pdf` and produce a pie chart showing the gender distribution. To view your visual report after running the code, just open the PDF file. Make sure the dataset is correctly named and that the pie chart is generated before running the PDF creation step. 

