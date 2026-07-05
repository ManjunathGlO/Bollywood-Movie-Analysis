

# 🎬 Bollywood Movie Analysis

This project performs Exploratory Data Analysis (EDA) on a Bollywood movie dataset to discover insights into movie performance, ratings, genres, budgets, revenue, and other key factors.


## 🎯 Business Problem

Movie production companies invest significant budgets in films, but not every movie performs well at the box office. Understanding the factors that influence a movie's success can help producers, investors, and marketers make better business decisions.

This project analyzes Bollywood movie data to answer key business questions such as:

- Which movie genres generate the highest box office collections?
- Does the release period (Festive Season, Holiday Season, Long Weekend, or Normal Days) affect ROI?
- Is there a relationship between YouTube engagement and box office performance?
- Which movies produced the highest and lowest Return on Investment (ROI)?
- What trends exist in movie budgets and revenues over time?

## 🔄 Methodology

The project follows a structured data analysis workflow:

### 1. Data Collection
- Loaded the Bollywood movie dataset into a Pandas DataFrame.

### 2. Data Cleaning
- Removed leading/trailing spaces.
- Converted release dates into datetime format.
- Created new features such as **Year** and **ROI**.

### 3. Exploratory Data Analysis (EDA)
- Analyzed movie releases by year and release period.
- Examined genre distribution.
- Compared budgets, revenues, and ROI.
- Studied YouTube engagement metrics.
- Performed correlation analysis between numerical variables.
### 4. Data Visualization
Created visualizations using Matplotlib and Seaborn:
- Bar Charts
- Count Plots
- Box Plots
- KDE Distribution Plots
- Correlation Heatmaps

### 5. Business Insights
Generated actionable insights regarding:
- Best release periods for maximizing ROI.
- High-performing genres.
- Impact of marketing engagement (YouTube likes/views).
- Budget allocation trends.
- Factors associated with box office success.
- 
## 📌 Project Objectives
- Clean and preprocess movie data
- Perform exploratory data analysis (EDA)
- Identify trends in ratings and revenue
- Analyze genre popularity
- Visualize relationships between different movie attributes
- Generate actionable insights using data visualization

## 🚀 Features
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- ROI (Return on Investment) analysis
- Genre-wise and year-wise movie analysis
- Release time trend analysis
- Correlation analysis using heatmaps
- Interactive visualizations with Matplotlib & Seaborn
- Business insights from movie performance data

## 📊 Key Insights
- Analyzed **149 Bollywood movies** released between **2013–2015**.
- Identified the best-performing movie release periods.
- Compared genres based on budget, box office collection, and YouTube views.
- Calculated ROI to identify top flop movies.
- Found a positive correlation between YouTube likes and box office collections.
- Visualized trends using boxplots, bar charts, count plots, KDE plots, and heatmaps. :contentReference[oaicite:1]{index=1}

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📊 Analysis Performed
- Data Cleaning
- Missing Value Treatment
- Descriptive Statistics
- Genre Analysis
- Rating Distribution
- Revenue Analysis
- Correlation Analysis
- Data Visualization

## 📈 Key Insights
- Identified the most popular movie genres.
- Compared movie ratings across different genres.
- Explored relationships between revenue, budget, and ratings.
- Visualized trends using various charts and graphs.


## 🎯 Skills Demonstrated
- Data Cleaning
- Data Manipulation
- Exploratory Data Analysis (EDA)
- Statistical Analysis
- Data Visualization
- Business Intelligence
- Python Programming



## 📂 Project Structure

```
Bollywood-Movie-Analysis/
│
├── data/
│   └── bollywood.csv
│
├── notebooks/
│   └── BollywoodMovieAnalysis.ipynb
│
├── images/
│   ├── boxplot.png
│   ├── heatmap.png
│   ├── barplot.png
│   └── countplot.png
│
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore

```


## Folder Explanation
| Folder/File        | Purpose                                             |
| ------------------ | --------------------------------------------------- |
| `data/`            | Stores the dataset (`bollywood.csv`)                |
| `notebooks/`       | Contains the Jupyter Notebook (`.ipynb`)            |
| `images/`          | Stores charts and visualizations used in the README |
| `README.md`        | Project documentation                               |
| `requirements.txt` | Python libraries required to run the project        |
| `LICENSE`          | Open-source license (MIT recommended)               |
| `.gitignore`       | Prevents unnecessary files from being uploaded      |


## 📌 Conclusion
This project showcases practical data analysis skills by transforming raw movie data into meaningful insights through Python-based analytics and visualizations. It is an excellent portfolio project for aspiring Data Analysts.


