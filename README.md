# Economic Analysis Project using World Bank Open Data API

This repository contains a comprehensive economic analysis project that utilizes the World Bank Open Data API to analyze relationships between key economic indicators across multiple countries.

## Repository Contents

1. **Data Collection and Processing**: Scripts to fetch, clean and preprocess economic data
2. **Exploratory Data Analysis**: Notebooks analyzing trends in economic indicators
3. **Statistical Analysis**: Correlation analysis, regression modeling, and hypothesis testing
4. **Machine Learning Models**: Clustering analysis and predictive models
5. **Visualization**: Interactive dashboards and data visualizations
6. **Documentation**: Comprehensive documentation and reports

## Installation and Setup

```
# Clone the repository
git clone https://github.com/Saloni-Agg/Economic-Analysis-.git

# Navigate to project directory
cd economic-analysis-project

# Create a virtual environment
python -m venv env

# Activate virtual environment
# On Windows:
env\Scripts\activate
# On macOS/Linux:
source env/bin/activate

# Install dependencies
pip install -r requirements.txt
```

## Usage

The project contains multiple notebooks and scripts organized in a logical workflow:

1. Start with data collection notebooks in `notebooks/01_data_collection/`
2. Proceed with exploratory analysis in `notebooks/02_exploratory_analysis/`
3. Run statistical analyses in subsequent notebooks
4. Launch the interactive dashboard with `python src/visualization/dashboard.py`

## Project Structure

```
economic_analysis_project/
├── data/                      # Data directory
│   ├── raw/                   # Raw data from World Bank API
│   ├── processed/             # Cleaned and processed datasets
│   └── external/              # External data from other sources
├── src/                       # Source code
│   ├── data/                  # Data collection and processing
│   ├── features/              # Feature engineering
│   ├── models/                # Model training and evaluation
│   └── visualization/         # Visualization code
├── notebooks/                 # Jupyter notebooks
│   ├── 01_data_collection/    
│   ├── 02_exploratory_analysis/
│   └── ...
├── models/                    # Saved model files
├── reports/                   # Generated reports and figures
├── tests/                     # Test files
├── docs/                      # Documentation
├── requirements.txt           # Dependencies
└── README.md                  # This file
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.
