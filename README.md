# Anushka-K-Mini-Stock-Advisor-Assi01
Rule-Based Mini Stock Advisor using Python + R


# 📈 Rule-Based Mini Stock Advisor  
A simple rule-based (NO machine learning) stock advisor that generates *BUY / SELL / HOLD* signals based on daily percentage change logic. Python is used for data processing & rule evaluation, and R is used for generating plots.

---
## 🧠 Project Overview

### *⿡ Compute Daily Percentage Change*
percentage_change = ((closing_price - opening_price) / opening_price) * 100

### *⿢ BUY Rules*
A *BUY* signal is generated if ANY ONE is true:
- Today’s % change > *+2%* AND yesterday had positive change  
- Today AND yesterday both had a positive change

### *⿣ SELL Rules*
A *SELL* signal is generated if ANY ONE is true:
- Today’s % change < *–2%*  
- Today AND yesterday both had negative change

### *⿤ HOLD Rule*
A HOLD signal is assigned when:
- % change is between *–2% and +2%*, AND  
- No BUY/SELL rule is triggered

---

## 🐍 Python Script (stock_advisor.py)

The Python script:
- Creates or loads a 10-day dataset  
- Computes daily percentage change  
- Applies the rule-based system  
- Outputs BUY / SELL / HOLD for each day  

Run using:

---

## 📊 R Script (plots.R)

The R script generates:
- Bar plot (BUY / SELL / HOLD counts)
- Histogram (percentage change distribution)
- Scatter plot (Open vs Close)

🖼 Plot Preview (Embed PNG Files)
Make sure your images are inside plots/ folder.

### *Bar Graph*
![Bar Graph](https://github.com/anushka-kave/Data-analyst-Internship-Assignment-Mini-Stock-Advisor-/blob/e9ea31980fbd5dfc1ac6b7899ce963f5bb72f567/Bar%20Graph.png)


### *Histogram*
![Histogram](https://github.com/anushka-kave/Data-analyst-Internship-Assignment-Mini-Stock-Advisor-/blob/e9ea31980fbd5dfc1ac6b7899ce963f5bb72f567/Histogram.png)

### *Scatter Plot*
![Scatter Plot](https://github.com/anushka-kave/Data-analyst-Internship-Assignment-Mini-Stock-Advisor-/blob/e9ea31980fbd5dfc1ac6b7899ce963f5bb72f567/Scatter%20Plot.png)
