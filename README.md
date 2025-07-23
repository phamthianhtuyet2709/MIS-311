# Project 1: Analyzing Shoe Prices by Brand and Size

## Context and Objective

This project explores how brand and shoe size influence product pricing in the footwear market. The dataset contains 200 shoe products, each with brand, color, size, and price information. The objective is to uncover patterns that can help retailers make informed decisions regarding pricing strategy and inventory planning.

---

## Key Variables

- **Price**: Retail price of the shoe (in USD) – the main variable of interest.
- **Brand**: The brand of each shoe, representing different market positioning.
- **Size**: Shoe size in US sizing system (float).
- **Color**: The color of the product (not used in this analysis).

---

## 📊 Analysis & Visualizations

### 1. Average Price by Brand

<img width="453" height="293" alt="image" src="https://github.com/user-attachments/assets/f99d5451-8542-48ff-b0a8-d76ed7aa0bc5" />

**Figure 1**: Bar chart showing the average shoe price for each brand.

- **PUMA**, **LaBriza**, and **Umbro** are the most expensive brands, with average prices above $260.
- **Crocs** is the most frequent brand (74 items) but has a mid-range average price (~$199).
- The result indicates that brand price strategy is not always linked to product count or popularity.

---

### 2. Average Price by Shoe Size

<img width="357" height="205" alt="image" src="https://github.com/user-attachments/assets/b3388fb1-107e-4ea8-8158-b1ef4da46343" />

**Figure 2**: Line chart displaying average price based on shoe size.

- Size **12.5** and **13.0** have the lowest average prices (~$144–$149), despite being larger sizes.
- Prices fluctuate irregularly across sizes, with no clear upward or downward trend.
- This suggests that shoe size alone does not consistently drive pricing.

---

## 🔍 Key Insights

- **Insight 1 – Price vs. Brand Popularity**:  
  Although **Crocs** appears most frequently in the dataset, its average price is significantly lower than that of **PUMA** or **LaBriza**, which appear only a few times. This suggests that popularity and frequency in the market do not necessarily imply premium pricing.

- **Insight 2 – Inconsistent Size-Based Pricing**:  
  The analysis shows that larger shoe sizes (e.g., 12.5, 13) are not more expensive. In fact, they tend to have **lower prices**. Price differences are more likely driven by other factors (e.g., brand or design) rather than size alone.

---

## Data Cleaning Summary

- Removed 3 duplicate entries from the dataset.
- Verified all prices are positive and within logical ranges.
- Checked that shoe sizes fall between 3.0 and 14.0; 2 invalid entries were removed.
- No missing values found.

---

## Conclusion and Implications

This analysis reveals that:
- **Branding plays a significant role** in price strategy, often more than product frequency.
- **Shoe size is not a reliable indicator** for pricing tiers.
Retailers should focus on **brand perception** and **product positioning** rather than size-driven price adjustments.
