
# 🏃 Ultra Marathon Data Analysis

## 📊 Project Overview
This project performs an **Exploratory Data Analysis (EDA)** on a dataset of ultra marathon races, aiming to understand key patterns, trends, and answer important questions about ultra marathon history and performance over time.

## 🚀 Steps Followed

1. **Data Import**  
   The dataset is imported from a CSV file located in Google Drive using Pandas.

2. **Data Cleaning & Manipulation**  
   Data cleaning and transformation steps are performed to prepare the dataset for analysis.

3. **Data Visualization**  
   Various charts and graphs are created using Seaborn and Pandas plotting functionality to analyze trends and distributions.

4. **Insight Generation**  
   Key questions related to race history, performance trends, and other metrics are answered through the analysis.

## 📁 Dataset

- **Source**:  
  The dataset file used is:  
  `TWO_CENTURIES_OF_UM_RACES.csv`

- **Columns Overview** (examples):  
  Typical columns include:  
  - Race Name  
  - Year  
  - Country  
  - Distance  
  - Winner Name  
  - Time  
  (More columns available in the dataset.)

## 📊 Sample Code

```python
import pandas as pd
import seaborn as sns
from google.colab import drive

# Mount Google Drive to access dataset
drive.mount('/content/drive')

# Load the dataset
df = pd.read_csv('/content/drive/MyDrive/Colab Notebooks/DataSet/TWO_CENTURIES_OF_UM_RACES.csv')

# Preview data
df.head()
```

## 📈 Visualizations

Some of the visual analyses performed include:
- Distribution of race distances over time
- Count of races by country
- Performance time trends over the years
- Outlier detection on race durations

*(Detailed graphs are available in the Jupyter notebook.)*

## ⚙️ Tools & Libraries Used

- Python 3.x  
- Pandas  
- Seaborn  
- Matplotlib  
- Google Colab

## 📚 How to Run

1. Clone this repository.
2. Open the `ultra_marathon_data_analysis.ipynb` notebook in Google Colab.
3. Make sure the dataset file `TWO_CENTURIES_OF_UM_RACES.csv` is available in your Google Drive.
4. Run the notebook cells sequentially.

## 🎯 Insights & Conclusions

The analysis provides insights into historical ultra marathon trends, performance improvements over time, and geographical distribution of races.

## 📄 License

This project is open-source under the MIT License.
