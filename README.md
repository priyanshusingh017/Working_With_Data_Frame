# Data Validation Checks with Pandas

This repository contains a Jupyter notebook demonstrating various data validation checks using the pandas library in Python. It covers essential steps to understand and assess the quality of a dataset, which is a crucial part of the data cleaning and preprocessing phase in any data analysis or machine learning workflow.

## 📊 Notebook Contents

The notebook covers the following topics:

### 1. Data Loading
- **Creating DataFrames from different sources:**
  - Lists and dictionaries
  - NumPy arrays
  - UCI Machine Learning Repository datasets
  - Reading from URLs

### 2. Basic Data Exploration
- Displaying the head of the DataFrame
- Column names and index information
- Dataset dimensions
- Data types overview
- Summary statistics

### 3. Data Validation Checks
-  **Missing Values Detection**: Identifying null and NaN values
-  **Data Type Validation**: Ensuring correct data types for analysis
-  **Unique Values Analysis**: Understanding data uniqueness
-  **Value Counts**: Analyzing categorical column distributions
-  **Duplicate Detection**: Identifying and handling duplicate rows
-  **Range Validation**: Checking numerical column ranges

##  Datasets Used

The notebook demonstrates validation techniques using these datasets:

1. **Iris Dataset**: Classic machine learning dataset fetched directly from the UCI Machine Learning Repository using the `ucimlrepo` library
2. **Wine Quality Dataset (White)**: Wine quality data read from a public URL provided by the UCI Machine Learning Repository

##  Getting Started

### Prerequisites

To run this notebook, you need Python installed along with the following libraries:

- `pandas` - Data manipulation and analysis
- `numpy` - Numerical computing
- `ucimlrepo` - UCI ML Repository data access

### Installation

Install the required libraries using pip:

```bash
pip install pandas numpy ucimlrepo
```

### Running the Notebook

1. Clone this repository:
```bash
git clone https://github.com/priyanshusingh017/Working_With_Data_Frame.git
cd Working_With_Data_Frame
```

2. Launch Jupyter Notebook:
```bash
jupyter notebook
```

3. Open `Working_with_Data_Frame_.ipynb` and run the cells

##  Key Learning Outcomes

After working through this notebook, you will understand how to:

- Load data from various sources into pandas DataFrames
- Perform comprehensive data quality assessments
- Identify and handle common data quality issues
- Apply systematic validation checks to any dataset
- Prepare data for further analysis or machine learning tasks

##  Contributing

Feel free to fork this repository and submit pull requests for any improvements or additional validation techniques you'd like to share.

##  License

This project is open source and available under the [MIT License](LICENSE).

##  Contact

If you have any questions or suggestions, feel free to reach out!

---

⭐ **Don't forget to star this repository if you found it helpful!** ⭐