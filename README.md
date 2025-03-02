Traffic Data Analysis  

## Overview  
This project processes and analyzes a traffic dataset to extract insights about vehicle counts, traffic conditions, and temporal trends. It includes data preprocessing, feature engineering, outlier detection, and visualization.  

## Files  
- **untitled77.py**: Python script for loading, preprocessing, analyzing, and visualizing traffic data.  

## Requirements  
The script requires the following Python libraries:  
- `pandas`  
- `numpy`  
- `matplotlib`  
- `seaborn`  
- `sklearn.preprocessing`  

You can install the dependencies using:  
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Data Processing  
1. **Loading Data**: Reads the `traffic.csv` file into a Pandas DataFrame.  
2. **Data Cleaning**: Handles missing values, converts data types, and removes duplicates.  
3. **Feature Engineering**:  
   - Extracts hour and minute from the `Time` column.  
   - Extracts day, month, year, and weekday from the `Date` column.  
   - Converts numerical columns and handles negative values.  
4. **Outlier Detection & Handling**:  
   - Uses boxplots and the Interquartile Range (IQR) method to detect and remove outliers.  
   - Applies transformations (log, square root) to handle skewness.  
5. **Encoding**: Uses Label Encoding for categorical columns.  

## Visualizations  
- Boxplots and histograms to analyze vehicle count distributions.  
- Bar and pie charts for traffic situation distribution.  
- Scatter plots and bar plots to analyze relationships between vehicle counts and traffic situations.  
- Heatmaps to visualize traffic trends across hours and days.  

## Usage  
Run the script in a Python environment:  
```bash
python untitled77.py
```

