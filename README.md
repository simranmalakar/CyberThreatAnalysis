# Cyber Threat Visualization

This project provides a comprehensive visual analysis of global cybersecurity threats from 2015 to 2024 using Python and popular data visualization libraries like Matplotlib, Seaborn, and Plotly.

## 📁 Project Files

- `cyberthreatvisual.py`: Main Python script that loads, cleans, and visualizes cyber threat data.
- `Global_Cybersecurity_Threats_2015-2024.csv`: [(https://www.kaggle.com/datasets/atharvasoundankar/global-cybersecurity-threats-2015-2024)](https://www.kaggle.com/datasets/atharvasoundankar/global-cybersecurity-threats-2015-2024) Required dataset containing details of cybersecurity incidents worldwide.

## 📊 Visualizations Included

1. **Line Chart – Cyber Attacks Over the Years**  
   Shows the trend of cyber attacks from 2015 to 2024.

2. **Bar Chart – Top 10 Attack Types**  
   Highlights the most common types of cyber attacks.

3. **Pie Chart – Top 10 Industries Affected**  
   Illustrates the proportion of incidents across the most targeted industries.

4. **Heatmap – Attacks by Year and Industry**  
   Displays the frequency of attacks across different industries over the years.

5. **Scatter Plot – Financial Loss by Year and Attack Type**  
   Explores the financial impact of various attack types over time.

6. **Choropleth Map – Global Attack Distribution**  
   Visualizes the number of attacks per country.

7. **Timeline Table – Top Cyber Incidents**  
   A simple timeline of notable cyber incidents (first 10 distinct entries).

8. **Box Plot – Financial Loss Distribution**  
   Compares financial losses for the top 5 attack types.

9. **Stacked Bar Chart – Attack Trends Over Time**  
   Shows how different attack types have trended each year.

## 🧹 Data Preprocessing
- Removed extra spaces and unified naming conventions in columns.
- Converted `Year` to numeric and dropped rows with missing critical data.
- Trimmed and standardized text fields for better visualization clarity.


## 🛠️ Dependencies
- Install the required Python libraries using:
- pip install pandas matplotlib seaborn plotly

##  How to Run
- Ensure the dataset Global_Cybersecurity_Threats_2015-2024.csv is in the same directory.
- Run cyberthreatvisual.py using any Python environment (e.g., Jupyter, Colab, or IDE).
- The script will generate and display all visualizations in sequence.

##  Notes
- The notebook was originally created in Google Colab and later exported as a Python script.
- All graphs are displayed inline; you can save them by adding plt.savefig() before each plt.show().
