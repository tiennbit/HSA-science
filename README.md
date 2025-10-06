# HSAR-science Dataset

This repository hosts tutorials for data analysis and machine learning modeling using the HSA (Highschool Student Assessment) dataset in Python. This project aims to analyze students' academic performance in high school as reported by the HSAR dataset. The analysis focuses on exploring relationships between gender, regional factors, GPA scores, and HSA performance. Machine learning models will be trained to predict student performance outcomes. The prediction performance will be evaluated using various metrics including accuracy, precision, recall, and F1-score. The code is written in Python with Jupyter notebooks for interactive analysis.

## Dataset Description

The HSA-science dataset supports research in educational data mining, learning analytics, and performance prediction. It enables analysis of academic factors, regional and gender disparities, and early warning systems for at-risk students. HSA scores serve as the key outcome variable. All personal identifiers have been removed to protect privacy while preserving the dataset's research value.

## Steps for Data Analysis and Machine Learning with HSA Dataset

### 1. Download the HSAR Dataset

Use the DOI link from the Zenodo repository to access the HSA dataset: https://doi.org/10.5281/zenodo.16752430. The dataset includes:
- `HSA_dataset.xlsx` - Main dataset file (31.8 MB)
- `Variable_Codebook_HSA.xlsx` - Variable descriptions and codebook (21.6 kB)

### 2. Install Dependencies

This project requires Python with the following packages:
- `pandas` - Data manipulation and analysis
- `numpy` - Numerical computing
- `matplotlib` - Data visualization
- `seaborn` - Statistical data visualization
- `scikit-learn` - Machine learning library
- `jupyter` - Interactive notebook environment

Install the required packages using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 3. Data Analysis Process

The analysis follows these main steps:

1. **Data Loading and Exploration**: Load the HSA dataset and explore its structure, data types, and basic statistics
2. **Data Preprocessing**: Handle missing values, encode categorical variables, and prepare data for analysis
3. **Exploratory Data Analysis**: Visualize relationships between variables including gender, region, GPA, and HSA scores
4. **Statistical Analysis**: Perform statistical tests to identify significant relationships
5. **Machine Learning Modeling**: Train predictive models for student performance outcomes
6. **Model Evaluation**: Assess model performance using appropriate metrics

### 4. Run the Analysis

1. Clone this repository or download the project files
2. Download the dataset from the provided DOI link
3. Open `data_q1.ipynb` in Jupyter Notebook or VS Code
4. Update the file path in the notebook to point to your downloaded dataset
5. Run the cells sequentially to perform the complete analysis

## Project Structure

```
HSA-science/
├── README.md                    # Project documentation
├── data_q1.ipynb              # Main analysis notebook
├── Metadata_Description_HSA.docx # Dataset metadata description
└── .git/                       # Git repository files
```

## Key Research Questions

This analysis addresses several important research questions:

1. What are the relationships between gender and academic performance (GPA, HSA scores)?
2. How do regional factors influence student performance outcomes?
3. What patterns exist in the distribution of HSA scores across different demographic groups?
4. Can machine learning models effectively predict student performance based on available features?
5. What factors are most predictive of academic success in high school assessments?

## Data Privacy and Ethics

The HSA dataset has been carefully prepared to protect student privacy:
- All personal identifiers have been removed
- Data has been anonymized while preserving research value
- The dataset follows ethical guidelines for educational research

## Citation

If you use this dataset or code in your research, please cite:

```
tiennbit. (2025). tiennbit/HSA-science: Dataset HSA (v1.0). Zenodo. https://doi.org/10.5281/zenodo.16752430
```

## License

This project is licensed under the Creative Commons Attribution 4.0 International License (CC BY 4.0).

## Contact

For questions about the dataset or analysis, please refer to the GitHub repository or the original dataset publication on Zenodo.
