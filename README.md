📊 Employee Data Analysis

This project demonstrates data cleaning, transformation, and visualization using Python libraries such as Pandas and Matplotlib. The dataset contains employee information such as Names, Departments, and Salaries.

The project walks through:

Cleaning messy data (handling missing values, salary formatting, capitalization issues, etc.).

Analyzing employee salaries by grouping and aggregating.

Creating meaningful visualizations with Matplotlib.

⚙️ Features

Clean and preprocess raw employee dataset.

Convert inconsistent salary formats (30k, 40,000, -) into integers.

Normalize department names (hr → HR, it → IT).

Extract top 10 highest salary earners and visualize them.

Show employee distribution across departments using pie charts.

Use Matplotlib to create bar charts and pie charts with labels, annotations, legends, and styling.

🛠️ Tech Stack

Python 3

Pandas – Data cleaning & analysis

Matplotlib – Data visualization

📂 Project Structure
├── Cleaned_Data.csv       # Processed dataset
├── analysis.ipynb         # Jupyter notebook with full analysis
├── app.py                 # (Optional) Script form if not using notebook
└── README.md              # Project documentation

📊 Example Visualizations
🔹 Top 10 Highest Salaries (Horizontal Bar Chart)

Displays the top earners with labels on each bar.

🔹 Department Distribution (Pie Chart)

Shows how employees are spread across departments (Finance, HR, IT, Marketing, Sales).

🚀 Getting Started

Clone the repo:

git clone https://github.com/your-username/employee-data-analysis.git
cd employee-data-analysis


Install dependencies:

pip install pandas matplotlib


Run the analysis:

Jupyter Notebook:

jupyter notebook analysis.ipynb


Or Python script:

python app.py
