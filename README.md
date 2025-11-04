# Chicago Socioeconomic Data Analysis

This project analyzes the "Selected Socioeconomic Indicators in Chicago" dataset (2008-2012) from the Chicago Data Portal. It uses SQL (via `ipython-sql`) and Python (Pandas, Seaborn) within a Jupyter Notebook to explore community data, answer key questions, and visualize findings.

## 📈 Analysis Highlights

The notebook connects to a SQLite database, loads the data from a remote CSV, and then performs SQL queries to answer questions such as:

* How many community areas are in the dataset?
* How many areas have a **Hardship Index** greater than 50?
* What is the maximum **Hardship Index** in the dataset?
* Which community area has the highest **Hardship Index**?
* Which communities have a **Per Capita Income** greater than $60,000?
* What is the correlation between **Per Capita Income** and **Hardship Index**? (Visualized with a scatter plot)



## 💻 Technologies Used

* **Python**
* **Jupyter Notebook**
* **SQL** (SQLite)
* **Pandas**: For loading the CSV into the SQL database.
* **ipython-sql**: For running SQL magic commands (`%sql`) in the notebook.
* **Seaborn** & **Matplotlib**: For data visualization.
