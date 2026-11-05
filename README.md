# 🏅 Olympics Data Analysis

An exploratory data analysis and interactive dashboard project built using Python to explore Olympic Games data. The project analyses athlete participation, medal tallies, country-wise performance, sports, and athlete statistics through data manipulation and interactive visualisations.

## 📌 Project Overview

The objective of this project is to explore historical Summer Olympics data and extract meaningful insights through data analysis and visualisation.

The project combines a Jupyter Notebook for exploratory analysis with a Streamlit application that allows users to interactively explore different aspects of Olympic history.

## ✨ Features

### 1. Medal Tally
- View the overall Olympic medal tally.
- Filter medal statistics by country.
- Explore medal tallies for individual Olympic editions.
- Compare gold, silver, bronze, and total medals.

### 2. Overall Analysis
- Explore key statistics such as:
  - Number of Olympic editions
  - Host cities
  - Sports and events
  - Participating nations
  - Athletes
- Analyse the growth of participating nations over time.
- Visualise the growth in Olympic events and athlete participation.
- Explore the number of events across different sports and years using a heatmap.
- Identify the most successful athletes.

### 3. Country-wise Analysis
- Explore a country's medal tally across Olympic editions.
- Identify the sports in which a country has excelled.
- Visualise country-wise performance using heatmaps.
- Identify the top-performing athletes of a selected country.

### 4. Athlete-wise Analysis
- Analyse the age distribution of athletes.
- Compare age distributions of gold, silver, and bronze medalists.
- Explore age distributions of gold medalists across different sports.
- Analyse the relationship between athlete height and weight.
- Compare male and female participation across Olympic editions.

## 🛠️ Technologies Used

- **Python** – Core programming language
- **Pandas & NumPy** – Data manipulation and numerical computation
- **Matplotlib & Seaborn** – Data visualisation
- **Plotly** – Interactive visualisations
- **SciPy** – Statistical analysis and KDE distributions
- **Streamlit** – Interactive web application
- **Jupyter Notebook** – Exploratory data analysis

## 📂 Project Structure

```text
olympics-data-analysis/
│
├── Olympics_Analysis.ipynb
├── app.py
├── helper.py
├── preprocessor.py
│
├── athlete_events.csv
├── noc_regions.csv
│
├── requirements.txt
├── README.md
└── .gitignore
```

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/olympics-data-analysis.git
```

### 2. Navigate to the project directory

```bash
cd olympics-data-analysis
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

### 4. Activate the virtual environment

**Windows PowerShell:**

```powershell
.\venv\Scripts\Activate.ps1
```

### 5. Install dependencies

```bash
pip install -r requirements.txt
```

### 6. Run the Streamlit application

```bash
streamlit run app.py
```

The application will open in your browser.

## 📊 Dataset

The application uses two CSV files:

- `athlete_events.csv` – Olympic athlete and event records, including age, height, weight, country, sport, and medal information.
- `noc_regions.csv` – Mapping of National Olympic Committee (NOC) codes to country/region names.

Both datasets must be placed in the project root directory for the application to run.

## 📚 Learning Outcomes

Through this project, I explored and practised:

- Data cleaning and preprocessing.
- Exploratory Data Analysis (EDA).
- Grouping, aggregation, merging, and pivot tables using Pandas.
- Statistical distributions and Kernel Density Estimation (KDE).
- Univariate and bivariate analysis.
- Interactive data visualisation.
- Building interactive dashboards using Streamlit.
- Organising Python projects using modular programming.

---

**If you find this project interesting, feel free to explore the repository!**