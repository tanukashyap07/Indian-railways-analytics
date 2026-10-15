# Indian Railways Analytics Dashboard

An end-to-end data analytics project focused on exploring Indian Railways journey data, identifying operational patterns, and presenting insights through Python-based Exploratory Data Analysis (EDA) and an interactive Power BI dashboard.

## Project Overview

This project analyses railway journey data to understand passenger movement, revenue performance, train delays, cancellations, and operational trends. Python is used for data exploration and analysis, while Power BI is used to build an interactive dashboard for visual reporting and decision-making.

## Objectives

- Analyse passenger and revenue trends.
- Understand train delays and cancellation patterns.
- Compare railway zones and train types.
- Explore the relationship between journey distance and cancellations.
- Examine passenger distribution across travel classes.
- Identify useful operational insights through data visualisation.

## Tools & Technologies

- **Python** – Data analysis and exploration
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical operations
- **Matplotlib / Seaborn** – Data visualisation, if used
- **Microsoft Power BI** – Interactive dashboard development
- **Microsoft Excel** – Dataset storage and preparation

## Dataset Description

The dataset contains railway journey information, including the following fields:

| Column | Description |
|---|---|
| Train_Name | Name of the train |
| Train_Type | Category of train |
| Source | Journey starting location |
| Destination | Journey ending location |
| Weather | Weather conditions |
| Class | Travel class |
| Payment_Method | Payment method used |
| Zone | Railway zone |
| Cancelled | Journey cancellation status |
| Date | Journey date |
| Journey_ID | Unique journey identifier |
| Passengers | Passenger count |
| Revenue | Revenue generated |
| Delay_Minutes | Delay duration in minutes |
| Distance | Journey distance |

*Column definitions and data types should be verified against the actual dataset.*

## Project Workflow

### 1. Data Exploration
- Inspected dataset dimensions, column names, and data types.
- Examined descriptive statistics and unique categorical values.
- Checked missing values and duplicate records.
- Investigated duplicate journey identifiers and potentially suspicious values.

### 2. Data Preparation
- Examined date formats and extracted useful date features.
- Explored revenue per passenger.
- Created delay categories for operational analysis.
- Reviewed cancellation records and prepared distance categories for comparison.

### 3. Exploratory Data Analysis
- Analysed cancellation patterns.
- Explored distance categories against cancellation status.
- Investigated passenger, revenue, and delay patterns.

### 4. Interactive Power BI Dashboard
The dashboard is being developed to present key metrics and interactive visualisations, including:

- Total passengers
- Total revenue
- Total journeys
- Average delay
- Cancellation rate
- Revenue trends over time
- Passenger distribution by class
- Cancellations by train type
- Revenue and average delay by zone
- Distance category versus cancellation rate

Interactive slicers will allow users to explore the data by available dimensions such as year, month, zone, train type, class, and weather.

## Key Business Questions

1. How does revenue change over time?
2. Which train types have higher cancellation rates?
3. How do delays vary across railway zones?
4. Does cancellation behaviour differ by journey distance?
5. Which travel classes account for the largest passenger volumes?
6. How do revenue and passenger trends vary across different categories?

## Repository Structure

```text
indian-railways-analytics-dashboard/
│
├── data/
│   └── README.md
│
├── notebooks/
│   └── indian_railways_eda.ipynb
│
├── dashboard/
│   └── indian_railways_dashboard.pbix
│
├── screenshots/
│   └── dashboard_preview.png
│
└── README.md
```

*Update the filenames and folders to match your actual repository. Add files as each part of the project is completed.*

## How to Run the Project

### Python EDA
1. Clone or download this repository.
2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn jupyter openpyxl
   ```

3. Open the EDA notebook in Jupyter Notebook.
4. Update the dataset path if necessary.
5. Run the notebook cells to reproduce the analysis.

### Power BI Dashboard
1. Install Microsoft Power BI Desktop.
2. Open the `.pbix` file from the `dashboard` folder.
3. If prompted, update the data source path.
4. Refresh the data and interact with the available charts and filters.

## Dashboard Preview

Add a screenshot of your completed Power BI dashboard here.

```markdown
![Indian Railways Analytics Dashboard](screenshots/dashboard_preview.png)
```

## Insights & Findings

This section will be updated after the analysis and dashboard are completed. It will include verified findings about passenger trends, revenue performance, delays, cancellations, and differences across zones and train types.

## Future Improvements

- Add more detailed route-level analysis.
- Improve dashboard drill-through and cross-filtering.
- Identify factors associated with higher delays and cancellations.
- Add more detailed time-based comparisons.
- Publish a dashboard preview and document the main findings.

## Author

**Anchala Kumari**

Aspiring Data Analyst | Python | SQL | Power BI | Excel


