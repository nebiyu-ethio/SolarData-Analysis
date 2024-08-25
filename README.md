# Solar Radiation Analysis

## Project Overview

This repository contains the Python-based analysis conducted for MoonLight Energy Solutions, focusing on enhancing operational efficiency and sustainability through targeted solar investments. The analysis aims to identify high-potential regions for solar installation by examining environmental measurement data provided by the engineering team.

## Objective

The goal of this analysis is to perform a thorough exploratory data analysis (EDA) and statistical assessment to uncover key trends and valuable insights. These insights will inform a data-driven strategy report, which will guide MoonLight Energy Solutions in making informed decisions aligned with its long-term sustainability goals.

## Exploratory Data Analysis (EDA)

During the EDA phase, the following analyses are performed on the solar energy dataset:

[Click Here to view the EDA file](https://github.com/nebiyu-ethio/SolarData-Analysis/blob/task-1/notebooks/EDA.ipynb)

- **Summary Statistics**: Calculate descriptive statistics such as mean, median, and standard deviation for each numeric column in order to understand the data distribution.
- **Data Quality Check**: Identify missing values, outliers, or incorrect entries in columns such as GHI, DNI, DHI, and others.
- **Time Series Analysis**: Analyze how variables like GHI, DNI, DHI, and Tamb change over time. Plotting these metrics across the 'Timestamp' can help identify patterns or anomalies.
- **Correlation Analysis**: Determine the correlation between different variables, such as solar radiation components (GHI, DHI, DNI) and temperature measures (TModA, TModB), to uncover relationships.
- **Wind Analysis**: Explore wind speed (WS, WSgust, WSstdev) and wind direction (WD, WDstdev) data to identify trends or notable wind events.
- **Temperature Analysis**: Compare module temperatures (TModA, TModB) with ambient temperature (Tamb) to understand their relationship or variation under different conditions.
- **Histograms**: Create histograms for variables like GHI, DNI, DHI, WS, and temperatures to visualize their frequency distribution.
- **Box Plots**: Use box plots to examine the spread and presence of outliers in the solar radiation and temperature data.
- **Scatter Plots**: Generate scatter plots to explore relationships between pairs of variables, such as GHI vs. Tamb or WS vs. WSgust.

## Technologies Used

- Python
- Pandas
- Matplotlib/Seaborn for visualization
- Jupyter Notebook

## How to Use

1. Clone the repository.
```bash
git clone https://github.com/username/repository.git
```
2. Navigate to the SolarData-Analysis directory
```
cd SolarData-Analysis
```
3. Create a virtual environment specific to this project.
- **Windows:**
```
python -m venv .venv
.venv\Scripts\activate
```
- **Linux and macOS:**
```
python3 -m venv .venv
source .venv/bin/activate
```
4. Install necessary dependencies from `requirements.txt`.
```
pip install -r requirements.txt
```

### Usage

Once the environment is set up and the packages are installed, run the project locally:

1. **Start the Streamlit Dashboard**  
   Navigate to the `app` directory in the `dashboard-dev`and start the Streamlit dashboard:
   ```bash
   cd app
   streamlit run main.py
   ```

   This will launch the dashboard, providing an interactive interface for exploring the analyzed data.

### Dashboard Screenshots

**Uploaded File Contents:**
![Dashboard](https://github.com/nebiyu-ethio/SolarData-Analysis/blob/dashboard-dev/dashboard/Uploaded%20csv%20file.png)

**Correlation Analysis:**
![Correlation Analysis](https://github.com/nebiyu-ethio/SolarData-Analysis/blob/dashboard-dev/dashboard/Correlation%20Analysis.png)

**Time Series Analysis:**
![Time Series Analysis](https://github.com/nebiyu-ethio/SolarData-Analysis/blob/dashboard-dev/dashboard/Time-Series%20Analysis.png)

**Box Plot Analysis:**
![Box Plot Analysis](https://github.com/nebiyu-ethio/SolarData-Analysis/blob/dashboard-dev/dashboard/Box%20Plot%20Analysis.png)

### Deployed Dashboard URL

The deployed version of the Streamlit dashboard can be accessed at: [Solar Radation Data Dashboard](https://solar-data-analysis.streamlit.app/).

### Project Report

For a detailed analysis, insights, and recommendations, refer to the full project report: [Download PDF Report](https://drive.google.com/file/d/1SOTqAdbLSAi9gQ5effXxzy2AolDf7QgE/view?usp=drive_link).

## License

This project is licensed under the [MIT License](LICENSE).

### Contact

- **Email**: [Send Message](nebiyuethio@gmail.com)
- **LinkedIn**: [Nebiyu G Gelaw](https://www.linkedin.com/in/neba-gech)

### Author

👤 **Nebiyu Getachew**
