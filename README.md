# VOIS_AICTE_Oct2025_MajorProject_Bhanu_Pratap
# 🎬 Netflix Content Trends Analysis for Strategic Recommendations

## 🌟 Project Overview

This repository contains the complete exploratory data analysis (EDA) and strategic content trend analysis of the Netflix catalog. The goal is to identify historical production patterns, genre popularity shifts, and geographic content distribution to provide actionable recommendations for future content investment.

The analysis focuses on the dataset spanning content releases from the early 1900s up to 2020.

---

## 🎯 Key Analysis Questions

1.  How has Netflix's content output (Movies vs. TV Shows) changed over time?
2.  What are the top-performing content genres, and how have their production trends evolved?
3.  How does content distribution differ between the top-producing countries (e.g., US vs. India)?
4.  What strategic recommendations can be made regarding investment in TV shows versus movies in key global markets?

---

## 🛠️ Technology and Libraries

* **Language:** Python
* **Environment:** Google Colaboratory (Recommended)
* **Libraries:**
    * `pandas` (Data manipulation)
    * `numpy` (Numerical operations)
    * `matplotlib` / `seaborn` (Static visualizations)
    * `plotly.express` (Interactive Choropleth Map)

---

## 📁 Repository Contents

* `Netflix Dataset (2).csv`: The raw dataset used for the analysis.
* `Netflix_Content_Analysis.ipynb`: The primary Jupyter Notebook containing the full analysis, visualizations, and code.
* `content_trend_us_india.png`: Key visualization comparing Movies vs. TV Shows release trends in the United States and India.

---

## 💡 Key Findings & Strategic Recommendations

Based on the analysis performed in the notebook, these are the primary conclusions and strategic imperatives:

### Content Trend Summary

| Market | Primary Focus | Key Trend | Implication |
| :--- | :--- | :--- | :--- |
| **Global/US** | Balanced (Movies & TV Shows) | Strong, sustained growth in **TV Shows**, signifying subscriber retention value. | Maintain high-quality Original TV content. |
| **India** | Movies (Dominant) | Content is overwhelmingly **Movie-focused**, with a notable deficit in local-language TV series. | Major untapped potential in TV series production. |

### Strategic Actions

1.  **Aggressive Local TV Investment in India:** Launch a focused, high-budget effort to produce local-language TV series in the Indian market to balance the content catalog and capitalize on sustained audience engagement.
2.  **Maintain Premium Global Focus:** Continue strong investment in high-production-value, original TV Shows and Limited Series globally, while focusing on selective acquisition of high-impact films.
3.  **Genre Diversification:** Strategically increase output in high-growth, underserved genres (e.g., Documentaries or specific International subgenres) to reduce market saturation in core areas like Drama/Comedy.

---

## 🚀 How to Run the Notebook

1.  **Clone the Repository:**
    ```bash
    git clone [YOUR-REPOSITORY-URL]
    ```
2.  **Open in Colab:** Upload the `Netflix_Content_Analysis.ipynb` file to your Google Drive and open it with Google Colaboratory.
3.  **Upload Data:** Upload the `Netflix Dataset (2).csv` file directly into your Colab environment's file system.
4.  **Run Cells:** Execute all cells sequentially. The first few cells perform data loading and cleaning, ensuring the subsequent visualizations run smoothly.
