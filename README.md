# Air-Quality-Data-Processing
This project was completed as part of the Data Engineering course. The focus of the project is on data preprocessing and cleaning, ensuring that the dataset is ready for further analysis or modeling.

> [!NOTE]
> This project is part of my learning journey, and as such, there may be steps that are incorrect or analyses that could be flawed. I welcome any feedback or suggestions for improvement as I continue to learn and refine my skills in data processing and analysis.

## Stages of Data Processing

### 1. Data Cleaning
   - **Handling missing values**: Missing data were handled using appropriate techniques, including dropping irrelevant columns and imputing missing values for others.
   - **Outlier detection and removal**: Outliers were detected and removed using the IQR method to ensure the dataset reflects realistic conditions.

### 2. Data Transformation
   - **Encoding categorical features**: Categorical features, such as station names and air quality categories, were encoded into numerical values for ease of use in further analysis.
   - **Feature scaling**: The dataset was standardized to ensure that all features contribute equally in future analyses.

### 3. Dimensionality Reduction (PCA)
   - **Principal Component Analysis (PCA)** was applied to reduce the dimensionality of the dataset, retaining the most informative components without losing significant information.

## Dataset

The dataset used for this project is publicly available and can be accessed [here](https://www.kaggle.com/datasets/senadu34/air-quality-index-in-jakarta-2010-2021/data).

### Dataset Description:
- The dataset contains air quality data from various stations in Jakarta, Indonesia, spanning multiple years.
- Key features include:
  - **PM10**: Particulate matter with a diameter of ≤10 µm.
  - **SO₂, CO, O₃, NO₂**: Concentrations of sulfur dioxide, carbon monoxide, ozone, and nitrogen dioxide.
  - **Max**: The maximum pollutant value for each record.
  - **Critical**: The pollutant that contributed most to the max value.
