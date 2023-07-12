# Vehicle Insurance Analysis

This project focuses on analyzing vehicle insurance data using Jupyter Notebook as the development platform. The analysis includes three types of analysis: univariate analysis, bivariate analysis, and outlier analysis. PySpark and SparkSQL are utilized for data processing, and data visualization is performed using Matplotlib and Seaborn libraries.

## Project Structure

The project directory is structured as follows:

```
vehicle_insurance_analysis/
    ├── data/
    │   └── insurance_data.csv
    ├── notebooks/
    │   └── Vehicle_Insurance_Analysis.ipynb
    ├── README.md
    └── requirements.txt
```

- `data/`: This directory contains the insurance data file (`insurance_data.csv`) used for analysis.
- `notebooks/`: This directory includes the Jupyter Notebook (`Vehicle_Insurance_Analysis.ipynb`) where the analysis is performed.
- `README.md`: The file you're currently reading, providing an overview of the project.
- `requirements.txt`: This file lists the required Python packages and their versions.

## Prerequisites

Before running the project, ensure you have the following dependencies installed:

- Python 3.x
- Jupyter Notebook
- PySpark
- SparkSQL
- Matplotlib
- Seaborn

To install the necessary packages, use the following command:

```bash
pip install -r requirements.txt
```

## Running the Project

1. Clone the repository:

```bash
git clone https://github.com/your-username/vehicle_insurance_analysis.git
```

2. Navigate to the project directory:

```bash
cd vehicle_insurance_analysis
```

3. Start Jupyter Notebook:

```bash
jupyter notebook
```

4. Open the `Vehicle_Insurance_Analysis.ipynb` notebook from the `notebooks/` directory in the Jupyter Notebook interface.

5. Execute the code cells in the notebook to perform the vehicle insurance analysis.

## Dataset

The dataset used for analysis is located in the `data/` directory. It is stored in a CSV file named `insurance_data.csv`. The dataset contains information about vehicle insurance policies and various attributes associated with them.

## Analysis

The Jupyter Notebook (`Vehicle_Insurance_Analysis.ipynb`) contains detailed steps and code for performing the following types of analysis:

1. **Univariate Analysis**: This analysis focuses on exploring individual variables in the dataset to understand their distributions, central tendencies, and spread. Various statistical measures, histograms, and other visualizations are used to gain insights into the variables.

2. **Bivariate Analysis**: In this analysis, relationships between two variables are examined to identify any dependencies or correlations. Scatter plots, box plots, and other visualizations are employed to analyze the relationships between different variables in the dataset.

3. **Outlier Analysis**: Outliers, if present, can significantly impact the analysis and results. This analysis identifies and treats outliers by using appropriate techniques such as box plots, z-scores, or interquartile range (IQR).

## Results and Visualizations

Throughout the notebook, visualizations are created using Matplotlib and Seaborn libraries to present the results of the analysis. The visualizations provide a graphical representation of the data, making it easier to interpret the findings.

## Conclusion

The vehicle insurance analysis project utilizes PySpark, SparkSQL, Matplotlib, and Seaborn to analyze a dataset containing vehicle insurance policy information. The notebook presents the steps and code used for univariate analysis, bivariate analysis, and outlier analysis. The visualizations and results obtained from the analysis provide valuable insights into the dataset.

For any questions or issues, please feel free to contact [S Antony vinothan] at [antonyvino777@gmail.com].
