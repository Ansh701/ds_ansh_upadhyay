# 🪙 Crypto Market Risk & Sentiment Analysis

## 🎯 Goal  
This project analyzes how market fear & greed sentiment affects trading behavior, profit, and risk in the crypto market using data-driven methods.

---

## 📂 Project Structure

```
crypto-risk-sentiment-analysis/
│
├── data/                # Raw & cleaned datasets  
├── notebooks/           # Main analysis notebook(s)  
├── outputs/             # Charts, summary reports, and PDFs  
├── requirements.txt     # Required libraries  
└── README.md            # Project overview  
```

---

## 📊 Key Insights

- 💡 **Correlation between Fear & Greed Index and Profit**: -0.025  
- 💹 **Correlation between Fear & Greed Index and Volume**: -0.034  
- 📈 Traders earned higher average profits during **Extreme Fear** periods.  
- 📉 During **Extreme Greed**, trade counts increased, but profit per trade decreased.

---

## 🧠 Techniques Used

- Data cleaning & merging using **pandas**  
- Sentiment-based segmentation (**Fear vs. Greed**)  
- Correlation & risk analysis  
- Visualization using **matplotlib** / **seaborn**  
- Statistical summary reporting

---

## 📦 Outputs

| File                          | Description                                           |
|------------------------------|-------------------------------------------------------|
| `outputs/charts/*.png`       | Visualizations of sentiment vs. profit and volume     |
| `outputs/ds_report.pdf`      | Final data science report                             |
| `outputs/summary_table.csv`  | Aggregated results by sentiment classification        |
| `outputs/model_results.txt`  | Notes or observations                                 |

---

## ⚙️ Setup & Usage

1. **Install Dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

2. **Run the Notebook**  
   ```bash
   jupyter notebook notebooks/analysis.ipynb
   ```

3. **Generate Outputs**  
   Plots and the PDF report will be saved automatically inside the `outputs/` folder.

---

## 🧾 Requirements

Example `requirements.txt`:

```
pandas  
numpy  
matplotlib  
seaborn  
scipy  
```

---

## 🧩 Future Enhancements

- Add LSTM or regression model to predict next-day sentiment  
- Integrate live Fear & Greed Index API  
- Build an interactive dashboard using **Plotly** or **Streamlit**

---

## 👤 Author

**Ansh Upadhyay**
