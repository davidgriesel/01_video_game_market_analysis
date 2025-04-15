# 🎮 01-video-game-sales-analysis

This project presents a descriptive analysis of historical video game sales data for **GameCo**, a hypothetical game development company. The goal is to extract insights that can inform game development, marketing strategy, and competitive positioning by understanding sales trends across genres, platforms, time periods, and geographic regions.

## 📌 Objectives

- Identify popular game genres and platforms to guide future game development
- Evaluate key competitors based on publisher performance
- Analyse changes in game popularity over time
- Compare sales performance across geographic regions

## 🛠️ Tools Used

- Excel (data exploration, pivot tables, visualisations)

## 📊 Key Results

- Action and sports games consistently perform well globally, especially in North America
- Major publishers such as Nintendo and Electronic Arts dominate sales across multiple genres
- Game popularity fluctuates over time, with trends influenced by platform and genre innovation
- Regional differences in genre preference highlight the importance of market-specific strategies

## 📁 Data Overview

The dataset was sourced from **VGChartz**, which tracks global video game sales for titles that have sold more than 10,000 units between 1980 and 2016. The data includes variables such as platform, genre, publisher, and sales by region.

🔗 [VGChartz Methodology](http://www.vgchartz.com/methodology.php)  
🔗 [Download Dataset](https://images.careerfoundry.com/public/courses/intro-to-data/E1/vgsales.xlsx)

Due to licensing considerations, the original raw file is not included in this repository.  
A cleaned and structured version (`data/cleaned_vgsales.csv`) is available for reference.  
More details on the cleaning process can be found in [`data/data_README.md`](data/data_README.md).

## 📈 Visuals

The analysis includes:
- Bar charts showing top-selling genres and platforms
- Box plots comparing regional performance
- Time series visualisations of sales trends by year

Visualisations are included in:
- `notebooks/vgsales_analysis.ipynb`
- `visuals/` folder (exported images for easy preview)

## 📋 Project Deliverables

This project was completed as part of the **CareerFoundry Data Analytics Program**, fulfilling the criteria for an end-to-end descriptive analysis. The work involved:
- Data exploration and cleaning
- Grouping and summarising using pivot tables
- Descriptive statistics and trend analysis
- Insight generation and visual storytelling

It addresses stakeholder questions from multiple business perspectives, including marketing, finance, and sales.

---

*This analysis is intended for demonstration purposes only. It is not affiliated with VGChartz or any actual game publisher.*