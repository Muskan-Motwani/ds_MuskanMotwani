

# **Trader Behavior & Market Sentiment Analysis**

### *A Data Science Assignment for Web3 Trading Team*

**By: Muskan Motwani**

---

#  **Project Structure**

| Folder / File      | Description                                                  |
| ------------------ | ------------------------------------------------------------ |
| `notebook_1.ipynb` | Main Colab notebook (cleaning, EDA, merging, visualizations) |
| `csv_files/`       | All raw & processed CSV files                                |
| `outputs/`         | Saved images from EDA & plots                                |
| `ds_report.pdf`    | Final report containing insights & conclusions               |
| `README.md`        | Project overview + instructions                              |

---

#  **Objective**

To analyze **how trading behavior** (profitability, trade volume, risk-taking) aligns with or deviates from **overall crypto market sentiment** (Fear → Greed).
This analysis helps identify **patterns, signals, and market conditions** useful in trading strategy development.

---

# 📊 **Datasets Used**

| Dataset                               | Description                                                    | Key Columns                                                |
| ------------------------------------- | -------------------------------------------------------------- | ---------------------------------------------------------- |
| **Historical Trader Data**            | All executed trades with price, volume, direction, profit/loss | Execution Price, Size USD, Side, Closed PnL, Timestamp IST |
| **Bitcoin Fear–Greed Sentiment Data** | Daily sentiment reflecting overall market mood                 | Date, Classification (Fear / Greed), Sentiment Number      |

---

#  **Steps to Run the Project**

###  1. Clone the Repository

```bash
git clone https://github.com/Muskan-Motwani/ds_MuskanMotwani.git
cd ds_MuskanMotwani
```

### ⭐ 2. Open in Google Colab

Upload & open `notebook_1.ipynb`.

### ⭐ 3. Place Data Files

Put your CSVs inside the `csv_files/` folder.

### ⭐ 4. Run All Notebook Cells

This will perform:

✔ Data Cleaning
✔ Exploratory Data Analysis
✔ Sentiment Mapping
✔ Feature Engineering
✔ Dataset Merging
✔ Graphs & Visualizations
✔ Final Insights

---

#  **Key Features of the Project**

###  **1. Individual EDA**

* Missing value checks
* Outlier detection with IQR
* Distribution visualizations
* Trend analysis
* Trade direction patterns
* Time-based trade activity

---

###  **2. Sentiment Analysis**

* Mapping sentiment classes → numeric scores
* Visualizing Fear vs Greed distribution
* Rolling averages to smooth trends
* Trend changes & sentiment flips

---

### ✅ **3. Combined (Merged) Analysis**

| Analysis                      | What It Shows                                   |
| ----------------------------- | ----------------------------------------------- |
| **Sentiment vs Trade Volume** | How Fear/Greed affects number of trades         |
| **Sentiment vs PnL**          | Whether Greed days are more profitable          |
| **Regime-Based Analysis**     | Behavior in Fear / Neutral / Greed days         |
| **Correlation Study**         | Links between sentiment & trading metrics       |
| **Momentum Signal**           | Uses change in sentiment over time as predictor |

---

#  **Important Visualizations Included**

* Sentiment over time
* Number of trades vs sentiment
* PnL distribution across sentiment regimes
* Correlation heatmap
* Rolling sentiment charts
* Trade volume analysis
* Boxplots for detecting outliers
* Scatter plots to show relationships

---

#  **Summary of Insights**

Here’s a clean table summarizing the main findings:

| Insight Area           | Finding                                                          |
| ---------------------- | ---------------------------------------------------------------- |
| **Trade Activity**     | Higher during Greed; lowest during Fear                          |
| **Profitability**      | More stable on Neutral/Greed days                                |
| **Risk Behavior**      | Traders take higher size on Greed days                           |
| **Fear Days**          | Most volatile PnL → unpredictable behavior                       |
| **Sentiment Momentum** | Improving sentiment often aligns with higher profit              |
| **Overall**            | Sentiment strongly influences trader behavior, not always profit |

---

#  **Why This Matters**

Understanding how **market mood impacts trader behavior** helps in building:

* Smarter trading strategies
* Risk-controlled systems
* Sentiment-aware models
* Market timing tools

This assignment demonstrates the ability to combine **data science + finance + behavioral analysis** — a strong skill set for trading teams.

---

#  **Technologies Used**

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab
* Git + GitHub

---

#  **Author**

** Muskan Motwani**



