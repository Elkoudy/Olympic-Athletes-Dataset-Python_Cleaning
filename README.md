# Olympic Athletes Dataset Cleaning

This project focuses on cleaning and preprocessing the Olympic Athletes dataset, specifically the `bios.csv` file. The primary goal is to transform the raw data into a clean and usable format for further analysis.

## Project Structure

The project directory is organized as follows:

```plaintext
Olympic-Athletes-Dataset-Python_Cleaning/
│
├── data/
│   ├── raw/
│   │   └── bios.csv              # Original uncleaned dataset
│   ├── processed/
│   │   └── cleaned_data.csv       # Cleaned dataset after processing
│
├── notebooks/
│   └── bios_cleaned.ipynb         # Jupyter notebook containing data cleaning script
│
└── README.md                      # Project description and documentation
```

# Project documentation


## 1. Overview of the Cleaning Process

This project employs the following data cleaning techniques:

- **Importing Libraries**: Essential libraries such as `pandas`, `numpy`, `seaborn`, and `matplotlib` are imported for data manipulation and visualization.
- **Loading the Dataset**: The raw dataset is read into a pandas DataFrame for processing.
- **Initial Data Inspection**: The dataset is inspected to understand its structure, including checking for missing values, duplicates, and basic statistics.
- **Data Transformation**: Various columns are cleaned and transformed, including:
  - Renaming and rearranging columns for better organization.
  - Handling missing values and duplicates.
  - Splitting and formatting columns (e.g., `Born`, `Measurements`, `NOC`).
- **Final Cleanup**: After cleaning, the processed DataFrame is saved as `cleaned_data.csv`.

## 2. Required Libraries

Ensure you have the following libraries installed in your Python environment:

- `pandas`
- `numpy`
- `seaborn`
- `matplotlib`
- `scikit-learn`

You can install these libraries using pip:

```bash
pip install pandas numpy seaborn matplotlib scikit-learn
```
3. Usage
To run the cleaning process, open the Jupyter notebook bios_cleaned.ipynb and execute each cell sequentially. The cleaned dataset will be saved in the data/processed/ directory as cleaned_data.csv.

4. Author

Elkoudy
