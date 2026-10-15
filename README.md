# Umucyo Supermarket – Retail Market Intelligence

An interactive retail analytics dashboard developed using **R and Shiny** to explore supermarket data, analyze sales performance, and gain insights into customers and products.

## Live Dashboard

Explore the deployed dashboard here:

**[Launch Umucyo Supermarket Dashboard](https://datawiserwanda.shinyapps.io/umucyo_supermarket_-_retail_market_intelligence/)**

The dashboard is hosted on shinyapps.io and can be accessed through a web browser.

## Project Overview

The Umucyo Supermarket Dashboard is a data-driven project designed to transform retail data into meaningful insights that support business understanding and decision-making.

By integrating data preparation, analysis, and interactive visualization, the project provides an accessible way to explore supermarket operations and identify patterns in retail performance.

## Project Objectives

- Analyze supermarket sales and retail performance.
- Explore customer purchasing behavior and characteristics.
- Examine product performance and sales trends.
- Present retail data through interactive visualizations.
- Demonstrate the practical application of data science and statistical programming in business analytics.

## Key Features

- **Interactive dashboard:** Explore retail information through a user-friendly interface.
- **Sales analysis:** Examine sales performance and patterns in the available transaction data.
- **Customer insights:** Explore customer-related information to better understand purchasing behavior.
- **Product analysis:** Investigate product performance and identify sales patterns.
- **Data preparation:** Integrate and organize retail datasets for analysis and visualization.

## Technologies Used

| Technology | Purpose |
|---|---|
| R | Data processing and statistical analysis |
| Shiny | Interactive dashboard development |
| CSV | Retail data storage and integration |
| Git and GitHub | Version control and project documentation |
| shinyapps.io | Online dashboard deployment |

## Project Structure

```text
Umucyo_Shiny_Dashboard/
│
├── deploy_to_shinyapps.R
├── run_dashboard.R
├── sync_data_into_dashboard.R
│
└── dashboard/
    ├── app.R
    │
    ├── data/
    │   ├── processed/
    │   │   ├── retail_integrated_clean.csv
    │   │   ├── customers_cleaned.csv
    │   │   └── products_cleaned.csv
    │   │
    │   └── raw/
    │       ├── transactions.csv
    │       ├── customers.csv
    │       └── products.csv
    │
    └── outputs/
        └── tables/
            ├── cleaning_log.csv
            └── removed_rows.csv
```

## Getting Started

### Prerequisites

Install [R](https://cran.r-project.org/) and [RStudio](https://posit.co/download/rstudio-desktop/).

### Run the Dashboard Locally

1. Clone or download this repository.
2. Open the project folder in RStudio.
3. Ensure the required retail datasets are available in the appropriate folders.
4. Install the packages required by the application.
5. Open `run_dashboard.R` or `dashboard/app.R` and run the application.

Example:

```r
# Install Shiny if it is not already installed
install.packages("shiny")

# Launch the dashboard
shiny::runApp("dashboard")
```

The application will open in your default web browser or RStudio viewer.

## Deployment

The dashboard is deployed using shinyapps.io.

The deployment script, `deploy_to_shinyapps.R`, is used to publish the application and update the online version when the dashboard code or data changes.

**Live application:** [Umucyo Supermarket – Retail Market Intelligence](https://datawiserwanda.shinyapps.io/umucyo_supermarket_-_retail_market_intelligence/)

## Academic Project

This project was developed by **Group 3** as part of the course:

*Programming for Data Scientists (Python and R)*

African Centre of Excellence in Data Science (ACE-DS)  
University of Rwanda

## Data and Security

The dashboard uses retail datasets prepared for this academic project.

Before publishing this repository, ensure that:

- No confidential customer information or personally identifiable data is included.
- No shinyapps.io tokens, secrets, passwords, or other credentials are committed.
- Dataset sharing complies with the applicable data permissions.

## Acknowledgment

We acknowledge the academic learning environment provided by ACE-DS, University of Rwanda, which supports the practical application of programming, data analysis, and data visualization skills.

---

**Umucyo Supermarket – Retail Market Intelligence**  
Turning retail data into meaningful insights through interactive analytics.
