# Extracting Insights from Amazon Beauty Product Reviews

## 📘 Project Overview
This project analyzes **Amazon Beauty product reviews** to uncover insights about customer satisfaction, trust, and engagement.  
Using **Exploratory Data Analysis (EDA)** and **Sentiment Analysis**, we examine how factors like **ratings, review length, and helpful votes** reflect customer opinions and product perception.

---

## Objectives
- Clean and merge Amazon product metadata and review datasets.  
- Explore rating trends and repeat purchase behavior across categories.  
- Analyze **sentiment alignment** between text reviews and star ratings.  
- Examine how **review length and verified purchases** impact helpfulness.  
- Generate actionable insights to help brands improve customer satisfaction.

---

##  Key Insights
- Sentiment scores increase with star ratings — confirming emotional alignment.  
- Verified and detailed reviews gain higher helpful votes, showing greater trust.  
- Customers love 4★+ products with strong positive tone, while 2★− reviews show frustration.  
- Longer reviews (200–500+ words) are considered more **credible and helpful**.  

---

##  Data Cleaning Summary
- Removed corrupted JSON lines and unnecessary columns (`images`, `videos`, `categories`).  
- Filtered invalid prices and missing fields.  
- Converted timestamps to readable dates.  
- Merged datasets using `parent_asin` key.  
- Standardized columns and handled empty lists in `features`.

---

##  Tools & Libraries
- **Python**: pandas, numpy, matplotlib, seaborn  
- **Text Analysis**: NLTK (VADER Sentiment Analyzer)  
- **Data Source**: Amazon Beauty Reviews & Metadata JSONL files

---

## Visualizations
1. Average Sentiment Score by Rating  
2. Average Helpful Votes by Review Length  
3. Liked vs Hated Products (4★+ vs 2★− Sentiment Comparison)  
4. Verified vs Unverified Review Helpfulness

---

##  Team Contributions
- **Danish Azmi** – Recommendation system & LLM integration  
- **Steffi** – Product purchase pattern analysis  
- **Mahesh** – EDA & Sentiment Analysis  
- **Hanchao** – Rating distribution and correlation insights  

---

##  Conclusion
The study shows that **sentiment and rating strongly correlate**, and **long, verified reviews** build greater trust among buyers. These findings help brands better understand customer emotions and improve product quality and communication strategies.

---
