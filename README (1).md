
# COVID-19 Global Data Tracker

This project, authored by **Ednah Nyamusi Ochwoga**, is a data-driven analysis of global COVID-19 trends using the [Johns Hopkins University (JHU) CSSE COVID-19 dataset](https://github.com/CSSEGISandData/COVID-19). The notebook performs data cleaning, exploratory data analysis (EDA), visualizations, and a summary report, focusing on key countries including Kenya, United States, and India.

## Table of Contents
- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [How to Run](#how-to-run)
- [Key Findings](#key-findings)
- [Future Work](#future-work)
- [License](#license)

---

## Project Overview
This Jupyter Notebook analyzes the spread and impact of COVID-19 across selected countries. It examines confirmed cases and deaths over time, and visualizes trends with line plots and a choropleth map. The analysis also includes calculated death rates and a final summary of insights.

## Objectives
- Import and clean global COVID-19 time series data.
- Analyze time trends of confirmed cases and deaths.
- Compare metrics across Kenya, the United States, and India.
- Visualize trends using `matplotlib`, `seaborn`, and `plotly`.
- Present a narrative summary highlighting key insights and anomalies.

## Dataset
Data is sourced directly from the [Johns Hopkins University Center for Systems Science and Engineering (CSSE)](https://github.com/CSSEGISandData/COVID-19).

- [Time Series - Confirmed Cases](https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_confirmed_global.csv)
- [Time Series - Deaths](https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_deaths_global.csv)

No local files are required; the notebook fetches data via URLs.

## Technologies Used
- Python 3.8+
- Jupyter Notebook
- pandas
- matplotlib
- seaborn
- plotly

Install dependencies using:

```bash
pip install pandas matplotlib seaborn plotly
```

## How to Run
1. Clone this repository or download the notebook.
2. Open `covid_global_data_tracker.ipynb` in Jupyter Notebook or JupyterLab.
3. Run the cells sequentially to load, clean, analyze, and visualize the data.

## Key Findings
1. **Case Trends**: The U.S. had the highest number of cases (>100M by mid-2022), followed by India and Kenya.
2. **Death Rates**: Kenya reported a slightly higher death rate (~1.7%) compared to the U.S. (~1.2%) and India (~1.1%).
3. **Anomalies**: India experienced a major case spike in April 2021, corresponding with the Delta variant.
4. **Global Trends**: Higher case densities were observed in North America, Europe, and parts of Asia. Africa had lower reported cases.
5. **Data Gaps**: Vaccination and policy data are not included, which limits full-spectrum analysis.

## Future Work
- Integrate vaccination data from **Our World in Data**.
- Create an interactive **Streamlit** dashboard for dynamic exploration.
- Analyze the effect of policies (lockdowns, mandates) on case/death trends.

## License
This project is released under the [MIT License](LICENSE).
