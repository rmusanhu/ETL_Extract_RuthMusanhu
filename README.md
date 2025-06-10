**Student Name**: Ruth Musanhu
**Student ID**: 670474 
**Submission Date**: [10th june 2025]


## 📌 Project Overview
The project is a practical demonsration of Extract-Transform-Load (ETL) operations focusing on **full** and **incremental** data extraction patterns.It was developed using Python within a Jupyter Notebook environment, it processes synthetic sales transaction data to simulate a real-world data pipeline scenario.


## 🛠️ Tools & Technologies
- **Python 3**
- **Pandas** for Data manipulation
- **Jupyter Notebook** for Interactive development
- **Git/GitHub** for Version control

## 📂 Project Structure
ETL_Extract_ruthmusanhu
├── etl_extract.ipynb         # Your Jupyter notebook containing ETL logic
├── custom_data.csv           # The chosen/generated sales dataset
├── last_extraction.txt       # Stores the timestamp for incremental extraction
├── .gitignore                # Excludes unneeded files from version control
├── README.md                 # This project explanation file
├── image.png               # Screenshot: Full Extraction Output
├── image-1.png               # Screenshot: Incremental Extraction Output
└── README.pdf                # PDF version of the README (if applicable)


## Dataset Origin
The dataset `custom_data.csv` is synthetically generated and contains 100 sales records with timestamps.




## 🧩 Key Features
1. **Full Extraction**:
Full Extraction is the process of extracting all data from the source system every time the ETL process runs. It does not consider whether the data has changed or not.In this case the  notebook displays key statistics like the total number of rows and columns, along with a sample of the loaded data,confirming a successful full extraction.

![alt text](image.png)


2. **Incremental Extraction**
Incremental Extraction retrieves only the new or changed data since the last extraction. It uses a mechanism such as timestamps, log files, or change data capture (CDC) to identify what has changed. This method is more efficient for large datasets as it minimizes data movement and processing


![alt text](image-1.png)

3. **Save timestamp**
Updates the timestamp after successful extraction.


## How to Reproduce
1. Open `etl_extract.ipynb` in Jupyter Notebook.
2. Run all cells in order.
3. Ensure `custom_data.csv` and `last_extraction.txt` are in the same directory.





