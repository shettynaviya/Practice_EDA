# Data Analysis with Python 📊🐍

Comprehensive collection of data analysis notebooks covering bivariate/multivariate analysis, data profiling, univariate analysis, and essential data understanding techniques using Python, Pandas, and visualization libraries.

## 📌 Project Overview

This repository contains practical implementations of statistical analysis and data exploration techniques. Perfect for data scientists, analysts, and students learning data analysis fundamentals through hands-on examples.

## 📂 Repository Structure
```
Data-Analysis-Python/
├── .ipynb_checkpoints/              # Jupyter notebook checkpoints
├── output/                          # Analysis outputs and results
├── Bivariate and Multivariate.ipynb # Multi-variable analysis (928 KB)
├── iris.csv                         # Iris dataset (4 KB)
├── Pandas Profiling.ipynb           # Automated EDA (9 KB)
├── tips.csv                         # Tips dataset (8 KB)
├── train.csv                        # Training dataset (60 KB)
├── Understanding your data.ipynb    # Data exploration guide (19 KB)
├── Univariate Analysis.ipynb        # Single variable analysis (188 KB)
└── README.md                        # Project documentation
```

## 📚 Notebooks Overview

### 1. Bivariate and Multivariate Analysis (928 KB)
**Focus:** Relationship analysis between two or more variables

**Topics Covered:**
- Correlation analysis
- Scatter plots and pair plots
- Heatmaps
- Cross-tabulation
- Chi-square tests
- Regression analysis
- Multi-dimensional relationships

**Use Cases:**
- Understanding variable relationships
- Feature selection
- Predictive modeling preparation
- Pattern identification

### 2. Univariate Analysis (188 KB)
**Focus:** Single variable statistical analysis

**Topics Covered:**
- Distribution analysis
- Descriptive statistics (mean, median, mode)
- Variance and standard deviation
- Quartiles and percentiles
- Outlier detection
- Histograms and box plots
- Probability distributions

**Use Cases:**
- Data quality assessment
- Understanding variable distributions
- Identifying anomalies
- Initial data exploration

### 3. Understanding Your Data (19 KB)
**Focus:** Comprehensive data exploration techniques

**Topics Covered:**
- Data types and structures
- Missing value analysis
- Data shape and dimensions
- Basic statistics overview
- Data quality checks
- Initial visualizations

**Use Cases:**
- First look at new datasets
- Data cleaning preparation
- Quality assessment
- Documentation

### 4. Pandas Profiling (9 KB)
**Focus:** Automated exploratory data analysis

**Topics Covered:**
- pandas-profiling library usage
- Automated report generation
- Variable statistics
- Correlation matrices
- Missing data visualization
- Distribution analysis

**Use Cases:**
- Quick dataset overview
- Comprehensive EDA reports
- Client presentations
- Documentation

## 📊 Datasets Included

### 1. iris.csv (4 KB)
**Description:** Classic Iris flower dataset
- **Rows:** 150
- **Features:** 4 (sepal length, sepal width, petal length, petal width)
- **Target:** Species (3 classes)
- **Use:** Classification, visualization practice

### 2. tips.csv (8 KB)
**Description:** Restaurant tipping dataset
- **Features:** Total bill, tip, sex, smoker, day, time, size
- **Use:** Relationship analysis, statistical testing

### 3. train.csv (60 KB)
**Description:** Training dataset for machine learning
- **Purpose:** Model training and validation
- **Features:** Multiple variables for analysis

## 🛠️ Technologies Used

### Core Libraries
- **Python 3.8+** - Programming language
- **Pandas** - Data manipulation
- **NumPy** - Numerical computations
- **Jupyter Notebook** - Interactive development

### Visualization
- **Matplotlib** - Static plots
- **Seaborn** - Statistical visualizations
- **Plotly** (optional) - Interactive charts

### Analysis Tools
- **Pandas Profiling** - Automated EDA
- **SciPy** - Statistical tests
- **Statsmodels** - Statistical modeling

## 🚀 Getting Started

### Prerequisites
```bash
Python 3.8 or higher
pip package manager
```

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/shettynaviya/Data-Analysis-Python.git
cd Data-Analysis-Python
```

2. **Create virtual environment**
```bash
python -m venv venv

# Activate on Windows
venv\Scripts\activate

# Activate on macOS/Linux
source venv/bin/activate
```

3. **Install dependencies**
```bash
pip install -r requirements.txt
```

### Required Packages
```txt
pandas>=1.5.0
numpy>=1.24.0
matplotlib>=3.7.0
seaborn>=0.12.0
jupyter>=1.0.0
pandas-profiling>=3.6.0
scipy>=1.10.0
statsmodels>=0.14.0
```

### Running Notebooks
```bash
# Launch Jupyter Notebook
jupyter notebook

# Or use Jupyter Lab
jupyter lab
```

## 📊 Analysis Techniques

### Univariate Analysis Methods
✅ Central tendency (mean, median, mode)
✅ Dispersion (variance, standard deviation)
✅ Distribution shape (skewness, kurtosis)
✅ Frequency distributions
✅ Box plots for outliers
✅ Histograms for patterns

### Bivariate Analysis Methods
✅ Correlation coefficients
✅ Scatter plots
✅ Cross-tabulation
✅ Chi-square tests
✅ T-tests
✅ ANOVA

### Multivariate Analysis Methods
✅ Multiple correlation
✅ Pair plots
✅ Heatmaps
✅ Principal Component Analysis (PCA)
✅ Factor analysis
✅ Cluster analysis

## 💡 Key Concepts Demonstrated

### Statistical Analysis
- Descriptive statistics
- Inferential statistics
- Hypothesis testing
- Probability distributions
- Confidence intervals

### Data Quality
- Missing value handling
- Outlier detection
- Data validation
- Consistency checks

### Visualization
- Distribution plots
- Relationship charts
- Comparison visualizations
- Statistical graphics

## 🎯 Use Cases

### Business Analytics
- Customer behavior analysis
- Sales trend identification
- Market segmentation
- Performance metrics

### Data Science
- Feature engineering
- Model preparation
- Data preprocessing
- Exploratory data analysis

### Research
- Statistical validation
- Hypothesis testing
- Result visualization
- Report generation

## 📈 Learning Path

### Beginner Level
1. Start with **Understanding your data.ipynb**
2. Learn **Univariate Analysis.ipynb**
3. Practice with iris.csv dataset

### Intermediate Level
4. Master **Bivariate and Multivariate.ipynb**
5. Explore **Pandas Profiling.ipynb**
6. Work with tips.csv and train.csv

### Advanced Level
7. Combine multiple analysis techniques
8. Create custom analysis pipelines
9. Build automated reporting systems

## 🔧 Common Analysis Workflows

### Workflow 1: Initial Data Exploration
```python
1. Load data with Pandas
2. Check data types and shapes
3. Generate pandas profile report
4. Identify missing values
5. Review basic statistics
```

### Workflow 2: Statistical Analysis
```python
1. Univariate analysis per variable
2. Distribution visualization
3. Outlier detection
4. Statistical testing
5. Documentation
```

### Workflow 3: Relationship Analysis
```python
1. Correlation matrix
2. Scatter plots
3. Heatmap visualization
4. Statistical significance tests
5. Insight generation
```

## 📊 Output Files

The `output/` folder contains:
- Generated reports (HTML, PDF)
- Visualization exports
- Statistical summaries
- Analysis results

## 🎓 Skills Demonstrated

✅ Data manipulation with Pandas
✅ Statistical analysis techniques
✅ Data visualization
✅ Exploratory data analysis (EDA)
✅ Hypothesis testing
✅ Correlation analysis
✅ Distribution analysis
✅ Automated reporting
✅ Data quality assessment

## 🔮 Future Enhancements

- [ ] Add time series analysis
- [ ] Include advanced statistical tests
- [ ] Add machine learning integration
- [ ] Create interactive dashboards
- [ ] Add more real-world datasets
- [ ] Include video tutorials
- [ ] Add advanced visualization techniques

## 📧 Contact

**Shetty Naviya**
- GitHub: [@shettynaviya](https://github.com/shettynaviya)

## 📄 License

This project is open source and available under the MIT License.
