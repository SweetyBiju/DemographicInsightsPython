# DemographicInsightsPython

# Overview
This repository contains a Python-based exploratory data analysis (EDA) project focused on uncovering demographic and socioeconomic insights from 2000 to 2022. The project integrates multiple datasets to analyze key indicators such as fertility rates, life expectancy, infant mortality, population growth, HIV prevalence, and GDP per capita. It includes data preprocessing, a variety of visualizations (boxplots, scatterplots, heatmaps, lineplots), and a simple linear regression model to explore trends and correlations.

## Features
- **Data Integration**: Merges datasets from UNESCO, World Bank, and custom country/continent mappings.
- **Preprocessing**: Implements data cleaning, missing value imputation (median/mean based on skewness), and linear interpolation.
- **Visualizations**: Offers diverse plots including boxplots, scatterplots, heatmaps, and lineplots to visualize trends and distributions.
- **Predictive Modeling**: Includes a simple linear regression to predict population growth based on fertility rates.
- **Skewness Analysis**: Evaluates data distribution skewness to guide preprocessing decisions.

## Installation
1. Clone the repository:
   ```
   git clone https://github.com/SweetyBiju/DemographicInsightsPython.git

2. Navigate to the project directory:
  ```
   cd DemographicInsightsPython
 ```  
   
3. Install required dependencies.

 ## Usage
1. Ensure all data files (`indicator_values.csv`, `indicator_codes.csv`, `country_codes1.csv`, `gdp.csv`, `continent_mapping.csv`) are placed in the appropriate subdirectories (e.g., root or as specified in the code).
2. Run the main script or individual modules:
   
     python data_preprocessing/data_preprocessing.py  # For preprocessing
   
     python Visualizations/visualisations.py          # For visualizations

     python plots/simple_regression.py                # For regression analysis
   
4. View the output in the console and generated plots (e.g., boxplots, scatterplots) saved in the `plots` or `Visualizations` directories.

## Dataset
- **Primary Source**: UNESCO Institute for Statistics Data Browser (demographic and socioeconomic indicators).
- **Secondary Sources**: World Bank open data portal (GDP data) and Wikipedia-derived country codes.
- **Custom Mapping**: `continent_mapping.csv` for regional segmentation.

## File Structure
```
DemographicInsightsPython/
│
├── README.md                    # This file
├── Visualizations/              # Visualization scripts and outputs
│   └── visualisations.py        # Contains heatmap, lineplot code
├── data_preprocessing/          # Data cleaning and preprocessing scripts
│   └── data_preprocessing.py    # Handles missing values and merging
├── plots/                       # Plot generation scripts
│   ├── simple_regression.py     # Simple linear regression code
│   └── visualisations.py        # Scatterplot and boxplot code
├── continent_mapping.csv        # Continent assignments
├── country_codes1.csv           # Country code mappings
├── gdp.csv                      # GDP data
├── indicator_codes.csv          # Indicator mappings
├── indicator_values.csv         # Main indicator data
└── requirements.txt             # Python dependencies (if added)
```

## Contributing
Contributions are welcome! Please fork the repository and submit pull requests with enhancements (e.g., new visualizations, improved preprocessing), bug fixes, or additional analyses. Update the README and add comments in the code for clarity.

## Acknowledgments
This project was developed with support from Lovely Professional University (LPU), which provided an exceptional academic environment and resources. Special thanks to my mentor, Maneet Kaur, for guidance, and to my colleagues for their collaboration and insights. The dataset integration benefited from publicly available data sources like UNESCO and the World Bank.

## Future Work
- Expand predictive models with more advanced techniques (e.g., machine learning).
- Add interactive visualizations using libraries like Plotly.
- Include additional socioeconomic indicators for deeper analysis.

