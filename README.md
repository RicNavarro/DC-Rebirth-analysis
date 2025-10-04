# DC Comics Publication Analysis - Rebirth Era (2016-2021)

![Project Status](https://img.shields.io/badge/Status-In%20Progress-yellow)
![Python](https://img.shields.io/badge/Python-3.9+-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-lightgrey?logo=pandas&logoColor=black)

## 🔅 Project Overview 

This data analytics project explores the universe of DC Comics publications during the  **Rebirth Era**, spanning from 2016 to 2021, which was marketed by DC as a starting point for new readers. The primary goal is to uncover interesting patterns, trends, and insights into comic book production, the focus on different protagonists, and the significance of major events within this editorial phase.

From data collection and cleaning to interactive visualization, this project demonstrates skills in data manipulation with Python (Pandas) and eventual the creation of dynamic dashboards with Power BI.

## 📈 Project Status

This project is actively being developed. Here’s a summary of current progress and what's planned next:

### ✅ Completed So Far:
*   Initial data extraction from [Comic Book Reading Orders](https://comicbookreadingorders.com/dc/dc-rebirth-reading-order/).
*   Basic data cleaning and structuring.
*   Dataset uploaded and made available on [Kaggle](https://www.kaggle.com/datasets/ricardotimes2/dc-rebirth-read-list).

### 🚧 Currently In Progress:
*   **Data Enhancement in Python:** Actively working on planned dataset improvements, including:
    *   Adding columns to identify multiple protagonists (e.g., handling "Batman/Superman").
    *   Introducing a column to indicate a comic book's participation in a specific `Event`.
    *   Integrating individual event files into the main dataset for richer contextual analysis.

### 📝 Next Steps:
*   **Exploratory Data Analysis (EDA):** Conduct deeper dives into the dataset to uncover initial trends and prepare for advanced analysis.
*   **Visualization Development:** Design and develop an interactive dashboard in Power BI to present key insights.
*   **Reporting:** Compile a comprehensive report detailing the methodology, key findings, and recommendations.

## 📚 Data Source

The dataset used was initially extracted from [Comic Book Reading Orders](https://comicbookreadingorders.com/dc/dc-rebirth-reading-order/), a comprehensive resource for comic book reading orders.

I performed basic cleaning and uploaded the dataset to Kaggle for easier access and reproducibility of the analysis:
[DC Rebirth Read List on Kaggle](https://www.kaggle.com/datasets/ricardotimes2/dc-rebirth-read-list)

### 🏗 Dataset Structure

The main dataset is `Comic_Order.csv`, which currently contains the following columns:
*   `Comic Name`: Title of the comic book.
*   `Character`: Main character(s) or team featured in the comic book.

**Planned Dataset Enhancements:**
*   Addition of an extra column to identify multiple protagonists (e.g., "Batman/Superman"). That way the main table would have a `Main Character` and a `Side Character` column.
*   Introduction of a column to indicate a comic book's participation in a specific `Event`.
*   Integration of individual files for each `Event` to enrich the contextual analysis.

## 💭 Business Questions and Analysis

This project aims to answer key questions, such as:

*   **Which heroes or teams had the highest number of publications** during the Rebirth era?
*   **What is the relevance of events:** Which publications within events are most worth following (e.g., most impactful, involving a larger number of titles)?
*   **Character Variety:** What was the diversity of characters that received publications? Was there an increase or decrease in variety over the Rebirth years?
*   **Characters in Events vs. Regular Titles:** Are the main characters of events the same as those with the highest number of regular titles?
*   **Is there a correlation between the release of major events and the total number of publications** in a given period?

### ❗ Additional questions

To further deepen the analysis and add value to the project, I plan to explore the following questions:

*   **Character Engagement:** Is it possible to infer which characters are more "engaged" in the overall Rebirth narrative, appearing in different titles and events?
*   **How is the publication of comic books distributed** over time during the Rebirth era?
*   **What would be the best events** for someone to follow if they're only interested in a particular set of characters? 


## 🛠️ Methodology and Tools

### Data Phase:
1.  **Collection and Acquisition:** Initial extraction from [Comic Book Reading Orders](https://comicbookreadingorders.com/dc/dc-rebirth-reading-order/).
2.  **Cleaning and Transformation (ETL):** Utilization of **Python** with the **Pandas** library for:
    *   Handling missing or inconsistent data.
    *   Creating new columns for multiple protagonists and event identification.
    *   Consolidating and enriching the main dataset.
3.  **Publication:** Making the cleaned and enriched dataset available on Kaggle.

### Analysis and Visualization Phase:
1.  **Exploratory Data Analysis (EDA):** Initial analysis to identify trends and patterns.
2.  **Interactive Visualization:** Development of dynamic dashboards and reports using **Power BI** to present insights clearly and accessibly.

## 🚀 Next Steps

*   Complete the planned dataset enhancements in Python.
*   Conduct deeper exploratory analyses.
*   Develop an interactive dashboard in Power BI.
*   Write a report detailing key findings and recommendations.

## 🤝 How to Contribute

This project is an individual effort, but I am open to discussions and feedback. Feel free to open an issue with suggestions or questions.

## ✉️ Contact

[![GitHub](https://img.shields.io/badge/GitHub-Profile-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/RicNavarro)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ric-navarro/)
[![Email](https://img.shields.io/badge/Email-Contact%20Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](ricardonavarro2611@gmail.com)