# EDA Python - Boston Housing Analysis (https://jaytech9.github.io/EDA-Boston/) Kindly open in chrome 

A comprehensive Exploratory Data Analysis (EDA) project analyzing the Boston Housing dataset using Python. This project demonstrates various data analysis techniques, visualization methods, and statistical insights.

**File: README.md** - Complete project documentation

## 🎯 Project Overview

This project performs an in-depth exploratory data analysis on the Boston Housing dataset, providing insights into factors that influence housing prices in Boston. The analysis includes data cleaning, statistical analysis, correlation studies, outlier detection, and comprehensive visualizations.

## 📊 Dataset Information

The Boston Housing dataset contains information about various factors that might influence housing prices:

- **CRIM**: Per capita crime rate by town
- **ZN**: Proportion of residential land zoned for lots over 25,000 sq.ft.
- **INDUS**: Proportion of non-retail business acres per town
- **CHAS**: Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
- **NOX**: Nitric oxides concentration (parts per 10 million)
- **RM**: Average number of rooms per dwelling
- **AGE**: Proportion of owner-occupied units built prior to 1940
- **DIS**: Weighted distances to five Boston employment centres
- **RAD**: Index of accessibility to radial highways
- **TAX**: Full-value property-tax rate per $10,000
- **PTRATIO**: Pupil-teacher ratio by town
- **B**: Proportion of blacks by town
- **LSTAT**: % lower status of the population
- **MEDV**: Median value of owner-occupied homes in $1000's (Target Variable)

## 🚀 Features

### Data Analysis Components
- **Basic Dataset Information**: Shape, data types, memory usage
- **Missing Data Analysis**: Detection and handling of null values
- **Distribution Analysis**: Histogram and density plots for all numerical variables
- **Correlation Analysis**: Heatmap and correlation coefficients
- **Outlier Detection**: Box plots and statistical outlier identification
- **Target Variable Analysis**: Deep dive into housing price distributions
- **Feature-Target Relationships**: Scatter plots showing relationships with price

### Visualizations Generated
- Distribution plots for all numerical variables
- Correlation heatmap
- Outlier detection box plots
- Target variable analysis plots
- Feature-target relationship scatter plots

## 📋 Requirements

```
pandas>=1.3.0
numpy>=1.21.0
matplotlib>=3.4.0
seaborn>=0.11.0
scipy>=1.7.0
scikit-learn>=1.0.0
```

## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/EDA-Python.git
cd EDA-Python
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

## 🎮 Usage

### Quick Start
```python
from main import BostonHousingEDA

# Initialize and run complete EDA
eda = BostonHousingEDA()
eda.run_full_eda()
```

### Custom Analysis
```python
# Initialize EDA
eda = BostonHousingEDA()

# Run individual components
eda.basic_info()
eda.distribution_analysis()
eda.correlation_analysis()
eda.outlier_analysis()
```

### Running the Script
```bash
python main.py
```

## 📈 Key Insights

The analysis reveals several important findings:

- **Strong Predictors**: Features like LSTAT (% lower status population) and RM (average rooms) show strong correlations with housing prices
- **Geographic Factors**: Charles River proximity and accessibility affect property values
- **Quality of Life**: Crime rates and pollution levels negatively impact housing prices
- **Socioeconomic Patterns**: Clear relationships between demographic factors and property values

## 📊 Generated Files

The analysis produces several visualization files:
- `distributions.png` - Distribution plots for all variables
- `correlation_heatmap.png` - Correlation matrix heatmap
- `outlier_boxplots.png` - Box plots for outlier detection
- `target_analysis.png` - Target variable analysis
- `feature_relationships.png` - Feature-target relationship plots

## 🔧 Project Structure

```
EDA-Python/
│
├── main.py              # Main EDA class and execution
├── README.md            # Project documentation
├── requirements.txt     # Python dependencies
├── .gitignore          # Git ignore file
│
└── outputs/            # Generated visualizations (created after running)
    ├── distributions.png
    ├── correlation_heatmap.png
    ├── outlier_boxplots.png
    ├── target_analysis.png
    └── feature_relationships.png
```

## 🤝 Contributing

Contributions are welcome! Here are some ways you can contribute:

1. **Fork the repository**
2. **Create a feature branch**: `git checkout -b feature/amazing-feature`
3. **Commit your changes**: `git commit -m 'Add amazing feature'`
4. **Push to the branch**: `git push origin feature/amazing-feature`
5. **Open a Pull Request**

### Ideas for Contributions
- Add more advanced statistical tests
- Implement machine learning models for prediction
- Create interactive visualizations with Plotly
- Add time series analysis if temporal data available
- Enhance documentation with more examples

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Boston Housing dataset from UCI Machine Learning Repository
- Inspiration from Generation Ghana DA 
- Inspiration from various EDA projects in the data science community
- Thanks to the Python data science ecosystem (pandas, matplotlib, seaborn, scipy)

## 📚 Learning Resources

- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Seaborn Tutorial](https://seaborn.pydata.org/tutorial.html)
- [Matplotlib Gallery](https://matplotlib.org/stable/gallery/)
- [EDA Best Practices](https://towardsdatascience.com/exploratory-data-analysis-8fc1cb20fd15)

---

⭐ If you found this project helpful, please give it a star!
