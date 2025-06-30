# 📊 Sales Data Analysis using Pandas

This project analyzes a dataset of **50,000+ sales records** using Python and Pandas to extract meaningful business insights, visualize patterns, and make strategic recommendations.

---

## 🧠 Objective

To perform data analysis on sales records and answer questions like:
- Which regions and countries are most profitable?
- What products are top-performing?
- How does sales priority affect performance?
- Are there any trends across shipping modes or over time?

---

## 🛠️ Tools Used

- **Python 3.10+**
- **Pandas**, **Matplotlib**, **Seaborn**
- **Jupyter Notebook** / **Google Colab**

---

## 🔍 Key Analysis Performed

- Grouped data by `Region`, `Country`, `Item Type`, `Sales Channel`, and `Order Priority`
- Calculated total revenue, units sold, and profit using `.groupby()` and `.sum()`
- Generated charts: Bar plots, Line charts, Heatmaps
- Highlighted top & bottom performers
- Bonus: Explored time trends & shipping performance

---

## 📈 Sample Visuals

- Profit by Region  
- Product Sales Comparison  
- Time Series of Monthly Sales  
- Priority vs Profit Heatmap  

---

## 📌 Insights Example

> - Sub-Saharan Africa generated the highest profit.
> - Baby Food and Meat products consistently lead sales.
> - Government channel outperformed Online for high-priority orders.
> - Faster shipping led to higher repeat order values.

---

## 🎯 Business Recommendations

- Focus sales efforts on top regions (e.g., Sub-Saharan Africa, Europe)
- Prioritize restocking of best-selling items
- Optimize shipping for high-value items
- Discontinue or re-market consistently underperforming products

---

## ▶️ How to Run

1. Clone this repo
2. Create a virtual environment:
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # or .venv\Scripts\activate on Windows
   ```
3. Install Dependencies
   - Using `pip`
   ```bash
   pip install jupyterlab notebook pandas matplotlib seaborn
   ```
   - Using `uv`
   ```bash
   uv add jupyterlab notebook pandas matplotlib seaborn
   ```
4. Launch the Notebook
   ```bash
   jupyter notebook
   ```
> __N.B.__ The dataset is present at `sales.csv` file inside `data` folder.

Built with ❤️ by __Subham Sen__