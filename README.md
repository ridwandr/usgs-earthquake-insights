# Earthquake Data Analysis

This repository provides a structured exploration and processing of earthquake event data with the goal of uncovering patterns and actionable insights using Python.

## Project Overview

Earthquakes are seismic events that carry important patterns in terms of time, location, magnitude, and depth. In this project, we perform a full Data Analytics workflow:

* Data extraction and cleaning (ETL)
* Exploratory Data Analysis (EDA)
* Visualizations and insight generation

The goal is to communicate useful findings from the earthquake dataset in a clear and reproducible way.

## Repository Structure

```
earthquake-data-analysis/
├── etl/                      # Scripts for extraction and preprocessing
│   ├── etl_main.py
│   ├── load.py
│   └── transform.py
├── notebook/                 # Jupyter notebooks for analysis
│   └── lm_etlProject.ipynb
├── .gitignore
├── README.md
├── etl_main.py
└── run.ipynb
```

## Data Source

The dataset used in this project is sourced from public earthquake records such as the USGS Earthquake Catalog — a widely available dataset of global earthquake events.

Typical fields include:
- time — event date and time
- latitude, longitude — geographical coordinates
- magnitude — earthquake magnitude
- depth — depth of the event

## ETL and Data Processing

The `etl/etl_main.py` script is designed to:
1. Load raw earthquake data
2. Clean and preprocess the dataset
3. Output a structured format ready for analysis

Common processing steps include:
- Parsing timestamps into datetime format
- Handling missing or inconsistent values
- Filtering by magnitude thresholds

You can customize data filters in the script to focus on different event subsets.

## Exploratory Analysis

The `notebook/run.ipynb` notebook contains:
- Summary statistics of earthquake occurrences
- Distribution of magnitudes
- Time-series patterns across years and months
- Geographic heatmaps or scatterplots

Use this notebook to interactively explore different aspects of the data and generate visual insights.

## Tech Stack

This project is built using:

Python for core programming  
Pandas for data manipulation  
Matplotlib or Seaborn for data visualization  
Jupyter Notebook for interactive analysis

## Key Insights

(Add your specific findings here after analysis — these examples are placeholders)

- Magnitude distribution pattern: Most earthquakes in the dataset fall between magnitudes 2.5 and 5.0.
- Temporal trend: There is a slight increase in recorded events over the last decade.
- Geographic trends: Certain latitude and longitude clusters show recurrent seismic activity.

Include visualizations (screenshots) under this section to enhance impact.

## How to Run This Project

1. Clone the repository:
```

git clone [https://github.com/ridwandr/earthquake-data-analysis.git](https://github.com/ridwandr/earthquake-data-analysis.git)

```

2. Install dependencies:
```

pip install -r requirements.txt

```

3. Run the ETL script:
```

python etl/etl_main.py

```

4. Launch the analysis notebook:
```

jupyter notebook notebook/run.ipynb

```

## Notes

This repository reflects a typical analytics pipeline:
data ingestion → cleaning → exploration → interpretation.

It is suitable to demonstrate analytic thinking and reproducibility, which are key competencies for data-focused roles.

## Contact

If you have questions or ideas, you can reach me via:
Email: [ridwandr.idn@gmail.com](mailto:ridwandr.idn@gmail.com)
LinkedIn: [https://linkedin.com/in/darmawanridwan](https://linkedin.com/in/darmawanridwan)
