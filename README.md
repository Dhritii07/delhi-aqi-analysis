# **Air Quality Analysis of Delhi - Big Data Analytics Project**

## 📌 **Project Overview**
This project analyzes the air quality of Delhi using Big Data technologies. The dataset contains pollutant levels recorded over time, and we use **Apache Spark** for data preprocessing, analysis, and visualization. The goal is to extract meaningful insights regarding pollution trends and correlations between different pollutants.

## 🎯 **Objectives**
- Process large-scale air quality data efficiently.
- Identify trends and seasonal variations in pollutant levels.
- Perform statistical analysis and correlation studies.
- Visualize air quality metrics using advanced data visualization techniques.
- Demonstrate the application of Big Data tools in environmental analytics.

## 🛠️ **Tech Stack Used**
- **Programming Language**: Python (PySpark, Pandas, Matplotlib, Seaborn)
- **Big Data Framework**: Apache Spark
- **Visualization Tools**: Matplotlib, Seaborn
- **Jupyter Notebook** for development
- **Dataset Format**: CSV

## 📂 **Dataset Information**
- **Dataset Name**: Air Quality Data of Delhi
- **Source**: [Download Link](https://www.kaggle.com/datasets/deepaksirohiwal/delhi-air-quality)
- **Attributes**:
  - `date`: Timestamp of recording
  - `co`, `no`, `no2`, `o3`, `so2`, `pm2_5`, `pm10`, `nh3`: Pollutant concentrations

## 📊 **Analysis Performed**
- Data Cleaning (handling missing values, type conversion)
- Descriptive statistics on pollutant concentrations
- Time-series analysis of pollutant trends
- Correlation heatmap of air pollutants
- Monthly and yearly AQI trends
- Comparison of pollutant levels across different locations

## 🚀 **Implementation Steps**
1. **Data Preprocessing**
   - Load dataset into Apache Spark.
   - Handle missing/null values.
   - Convert data types and standardize values.
2. **Exploratory Data Analysis (EDA)**
   - Calculate summary statistics.
   - Perform analysis using PySpark.
3. **Data Visualization**
   - Charts for pollutant variation over time.
   - Heatmaps to analyze correlation between pollutants.
   - Charts to compare AQI levels across years.
4. **Big Data Analysis using PySpark**
   - Using correlation heatmap for data to find insights.
   - Identify the most average air pollutant levels.
   
## 📈 **Results & Insights**
- Identified peak pollution months (Winter has the highest AQI levels due to inversion effects).
- PM2.5 and PM10 are the most significant contributors to poor air quality.
- Traffic-heavy and industrial areas show higher pollution levels.
- A strong correlation was observed between NO2 and PM2.5, indicating vehicular emissions as a major source.

## 💡 **Future Enhancements**
- Incorporate real-time air quality prediction models.
- Use geospatial analysis to visualize pollution distribution across Delhi.
- Integrate deep learning models for more accurate forecasting.

## 📜 **How to Run the Project**
1. **Clone the Repository**
   ```bash
   git clone https://github.com/Dhritii07/delhi-aqi-analysis.git
   cd delhi-aqi-analysis
   ```
2. **Set up the Environment**
   ```bash
   pip install pyspark pandas matplotlib seaborn
   ```
3. **Run the Jupyter Notebook**
   ```bash
   jupyter notebook
   ```
4. **Execute the Notebook Cells** to see data processing, analysis, and visualizations.

## 📬 **Contributing**
- Feel free to fork the repository and submit pull requests.
- Any suggestions or improvements are welcome!

## 🏆 **Acknowledgment**
- The dataset is sourced from publicly available air quality monitoring records.
- Thanks to the open-source community for providing tools like PySpark and Pandas for big data analytics.

---
**Author:** [Dhriti]  
🔗 **GitHub**: [Dhritii07](https://github.com/Dhritii07)  
📧 **Contact**: 07dhriti@gmail.com 

