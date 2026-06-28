#  Unemployment Analysis using Python

This project analyzes unemployment trends using a dataset containing dates, unemployment rates, and (optionally) regional information. The notebook is designed to automatically detect important columns, making it adaptable to different dataset formats.

##  Features

- **Automatic Column Detection**
  - Detects *date*, *unemployment rate*, and *region* columns.
- **Data Cleaning**
  - Handles missing values and converts date formats.
- **Trend Analysis**
  - Monthly and yearly unemployment trends.
  - Region-wise unemployment comparison.
- **Visualizations**
  - Line plots for overall trends  
  - Monthly & yearly averages  
  - Boxplots for regional comparison  
  - Heatmap for seasonal insights
- **Insights**
  - Highest & lowest unemployment year  
  - Months with highest/lowest unemployment  
  - Regions with highest unemployment (if available)

##  Dataset
Upload any CSV file that contains:
- A **Date** column  
- An **Unemployment Rate** column  
- A **Region** column (optional)

Example dataset source: Kaggle or government labour statistics.

## Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Google Colab

## How to Run
1. Open the notebook in **Google Colab**
2. Upload your unemployment CSV file when prompted
3. Run all cells to generate analysis and visualizations

## Output Includes
- Data summary & structure  
- Time-series trend plots  
- Monthly & yearly patterns  
- Regional unemployment comparisons  
- Seasonal unemployment heatmap  
- Automatic insights

## License
This project is open-source and available under the MIT License.
