# Exploratory Data Analysis of Video Game Sales

This repository contains Python code and a comprehensive exploratory data analysis (EDA) of video game sales data. The analysis uncovers insights into sales trends, platform performance, genre popularity, and more—providing a data-driven look into the video game industry.

---

## Project Objectives

1. **Global and Regional Sales Analysis**
   - Evaluate total global sales for each game and compare performance across platforms.
   - Break down and visualize regional sales (North America, Japan, PAL, Other) to identify region-specific bestsellers.

2. **Platform Performance**
   - Compare the sales performance of different gaming consoles (e.g., PS4 vs. X360).
   - Analyze how different platforms contributed to overall sales across regions and genres.

3. **Genre and Developer Insights**
   - Identify top-selling genres globally and regionally.
   - Discover which publishers and developers consistently produce high-selling games.

4. **Critic Score Correlation**
   - Analyze the relationship between critic scores and total sales to determine if higher-rated games generally sell more.
   - Investigate outliers (e.g., low-rated games with high sales or vice versa).

5. **Release Date & Temporal Trends**
   - Study the release timeline to determine peak years for game sales.
   - Analyze whether games released in certain years or seasons perform better commercially.

6. **Top 10 Titles by Various Metrics**
   - Generate lists of top 10 games by:
     - Total global sales
     - Regional sales (NA, JP, PAL, Other)
     - Critic score
     - Sales per console or genre

7. **Publisher Market Share**
   - Determine which publishers dominate the video game market.
   - Visualize publisher-wise contributions to global and regional sales.

---

## Dataset

**File:** `Pythonproject.xlsx`

The dataset contains aggregated sales and metadata for a broad range of video games. Each entry includes:

- `title`: Name of the video game  
- `console`: Gaming platform (e.g., PS4, X360, PS2)  
- `genre`: Genre of the game (e.g., Action, Shooter)  
- `publisher`: Publishing company  
- `developer`: Development studio  
- `critic_score`: Average critic score (out of 10)  
- `total_sales`: Total global sales in millions  
- `na_sales`: North America sales (millions)  
- `jp_sales`: Japan sales (millions)  
- `pal_sales`: PAL region sales (millions)  
- `other_sales`: Sales in other regions (millions)  
- `release_date`: Date of release  
- `last_update`: Last recorded update to the data  

---

## Tools and Libraries Used

- `pandas`: Data manipulation and preprocessing  
- `numpy`: Numerical operations  
- `matplotlib`: Data visualization  
- `seaborn`: Statistical graphics and advanced plots  

---

## Project Structure

```plaintext
├── videogamesales.ipynb         # Jupyter notebook containing full EDA and visualizations
├── Pythonproject.xlsx       # Main dataset used for the analysis
└── README.md                # Project documentation
