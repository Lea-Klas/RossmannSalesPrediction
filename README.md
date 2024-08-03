
# Rossmann Store Sales Prediction

## Introduction
This project focuses on developing a unified model to predict weekly store sales using historical sales data from 2013 to 2015. Additionally, we perform a comprehensive exploratory data analysis (EDA) to identify key factors influencing sales performance. This analysis provides strategic insights and recommendations for optimizing future sales. Finally, we generate an overall performance report and individual performance reports for each store.

## Files
- `rossmann.ipynb`: The main Jupyter Notebook containing the code.
- `data/test.csv`: The dataset containing the historical sales data of 1,115 Rossmann stores.
- `data/store.csv`: The dataset containing additional information about the 1,115 Rossmann stores.

## Features
- Predict weekly sales for Rossmann stores
- Perform exploratory data analysis (EDA)
- Analyze the impact of various factors on sales
- Provide strategic recommendations to optimize sales
- Generate individual and overall performance reports

## Installation
To set up this project on your local PC, open your terminal/command prompt and run the following commands:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Lea-Klas/RossmannSalesPrediction.git
   ```
2. **Navigate to the Project Repository**
   ```bash
   cd RossmannSalesPrediction
   ```
3. **Set Up a Virtual Environment** (optional but recommended)
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
4. **Install the Required Libraries**
   ```bash
   pip install -r requirements.txt
   ```
5. **Open the Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

## Dependencies
The project requires the following Python libraries:
- pandas
- numpy
- matplotlib
- seaborn
- plotly
- missingno
- scikit-learn

## Troubleshooting
If you encounter any issues, ensure that all dependencies are correctly installed and the data files are in the correct location. Check for any version conflicts with the libraries.

## Contributors
- [Lea Klas](mailto:lea.klas@gmx.de)

## License
This project is licensed under the MIT License.
