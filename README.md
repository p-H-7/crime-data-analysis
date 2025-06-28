# Crime Data Analysis - Cambridge Dataset

**EDA and crime category prediction using machine learning on Cambridge crime data (2009-2016)**

## 📊 Dataset
- **56,014 crime records** from Cambridge (2009-2016)
- **54 unique crime types** across 13 neighborhoods
- **7 key features**: Date, Crime Type, Location, Reporting Area, Neighborhood

## 🛠️ Technical Implementation

### Data Processing
- **Missing Value Handling**: SimpleImputer with most frequent strategy
- **Feature Engineering**: DateTime extraction, location standardization
- **Crime Categorization**: Grouped 54 crime types into 5 broader categories
- **Text Processing**: Location cleaning and normalization (3,785 → 734 unique locations)

### Advanced Analytics
- **Correlation Analysis**: Cramér's V for categorical variables
- **Data Balancing**: SMOTE for handling class imbalance
- **Multiple Encoding**: Target encoding for high-cardinality features

### Machine Learning
- **Algorithm**: Gaussian Naive Bayes
- **Performance**: 60.2% ROC AUC score
- **Features**: Engineered temporal, spatial, and categorical features

## 📈 Visualizations
- Crime distribution analysis with bar charts and pie charts
- Temporal trends showing crime patterns over 8 years
- Geographic heatmaps for neighborhood crime concentration
- Correlation matrix using Cramér's V statistics

## 💻 Technologies
**Python** | **pandas** | **scikit-learn** | **seaborn** | **matplotlib** | **SMOTE** | **category-encoders**
