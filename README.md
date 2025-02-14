# Statistical Data Analysis with Python  

## 📌 Project Overview  
This project explores statistical data analysis using Python on a dataset containing Age, Gender, Height, Weight, Income, and Region. It includes descriptive statistics, visualizations, hypothesis testing (t-test, z-test, ANOVA), confidence intervals, correlation, and regression analysis.  

## 📂 Dataset  
The dataset (`Simulated_DatasetPython.csv`) contains demographic and financial attributes:  
- Age (Numerical)  
- Gender (Categorical)  
- Height (Numerical)  
- Weight (Numerical)  
- Income (Numerical)  
- Region (Categorical: North, South, East, West)  

## 🚀 Features & Analysis  
✔️ Data Preprocessing: Load & clean dataset  
✔️ Descriptive Statistics: Mean, median, standard deviation  
✔️ Data Visualization: Histograms, boxplots, scatter plots  
✔️ Hypothesis Testing:  
&nbsp;&nbsp;&nbsp; 📌 T-Test (Income by Gender)  
&nbsp;&nbsp;&nbsp; 📌 Z-Test (Height vs. Population Mean)  
&nbsp;&nbsp;&nbsp; 📌 ANOVA (Income across Regions)  
✔️ Confidence Interval Calculation  
✔️ Correlation Analysis (Age vs. Income)  
✔️ Linear Regression Model (Predicting Income from Age)  

## 🔧 Installation & Usage  
1️⃣ Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/statistical-analysis-python.git
   cd statistical-analysis-python
   ```  
2️⃣ Install required libraries:  
   ```bash
   pip install pandas numpy scipy matplotlib seaborn scikit-learn
   ```  
3️⃣ Run the Python script:  
   ```bash
   python analysis.py
   ```  

## 📊 Results & Insights  
- No significant income difference between genders (T-test).  
- Income does not vary significantly by region (ANOVA).  
- Very weak correlation between Age and Income.  
- Regression shows Age has little impact on Income (low R² value).  

## 👨‍💻 Technologies Used  
- Python 🐍  
- Pandas, NumPy, SciPy for data handling  
- Matplotlib, Seaborn for visualization  
- Scikit-learn for regression analysis  
