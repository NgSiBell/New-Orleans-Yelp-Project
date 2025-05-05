# Yelp: Hidden Gems & Missed Revenue: Identifying Underrated Restaurants in New Orleans

**Python • JSON • Tableau**

---

## **Background**

Yelp is a global platform where users rate, review, and discover local businesses — especially restaurants. With tens of thousands of listings across major cities, it’s difficult to pinpoint what truly drives success or which businesses are being overlooked despite high quality.

This project explores the relationship between Yelp star ratings, review counts, and restaurant performance in New Orleans. Using real-world data, it surfaces trends that matter to both customers and potential investors — identifying overlooked, high-potential restaurants.

Key questions investigated:

- Can Yelp data reveal hidden high-performing restaurants?
- Are there patterns in customer satisfaction that predict success?
- Where are the most promising revenue opportunities by category or geography?

---

## Data Sources

- ***Yelp Open Dataset:*** The Yelp Open Dataset is a subset of Yelp data that is intended for educational use. It provides real-world data related to businesses including reviews, photos, check-ins, and attributes like hours, parking availability, and ambience.

---

## **Main Objectives / Business Questions**

Using a filtered dataset of New Orleans restaurants, this project answers three key business questions through a Tableau dashboard:

1. **Which restaurant categories generate the most revenue?**
2. **Where are the high-rated, low-visibility restaurants located?**
3. **How does revenue performance vary based on review volume and star rating?**

These insights expose marketing gaps and strategic opportunities for promotion, investment, or operational improvements.

---

## Workflow Overview

- Extracted and cleaned Yelp data for New Orleans using Python
- Conducted sentiment analysis on reviews to surface key themes
- Engineered revenue metrics from review volume and average spend
- Analyzed performance by restaurant category and business features
- Visualized findings in Tableau to identify hidden gems and revenue upside

---

### **Tools Used in This Project**

**Python (Jupyter Notebook):** For data cleaning, exploration, feature engineering, and sentiment analysis.

Key libraries used:

- `pandas` – Data manipulation
- `json` – Parsing Yelp’s nested files
- `TextBlob`, `wordcloud` – Sentiment scoring and keyword visualization
- `matplotlib`, `seaborn` – Data exploration and charting

**Tableau:** Built the executive dashboard to showcase:

- Revenue by category and geography
- Sentiment and review trends
- Maps of underrated restaurant clusters

**Jupyter Notebook:** Primary workspace for code, analysis, and storytelling.

---

## Key Insights

- **Financial Opportunity:** Restaurants with <150 reviews and high ratings often generate $70+ per review, outperforming more popular venues. Areas like Mid-City and Treme, especially in Creole, soul food, and health-forward categories, show strong revenue potential despite low visibility.
    - **Action:** Prioritize these neighborhoods and restaurant types for targeted promotion to unlock high-margin growth.
- **Visibility Gaps:** Highly rated restaurants in Treme, Bywater, and Broadmoor remain digitally underexposed. Despite 4.5+ star ratings, they rarely surface in Yelp searches due to low review counts.
    - **Action:** Use Yelp boosts, foodie roundups, or influencer spotlights to amplify presence in these overlooked areas.
- **Underleveraged Categories:** Restaurants offering vegan menus, brunch, pop-ups, or food trucks score high on sentiment but remain underrepresented in review volume and map visibility.
    - **Action:** Feature these trending business types in discovery campaigns like “Hidden Gems” or “Underrated Eats.”

---

## Strategic Recommendations

1. **Invest in High Sentiment / Low Visibility Restaurants:** Prioritize marketing for those with high revenue-per-review and positive customer emotion to maximize marketing ROI.
2. **Activate Community Advocates:** Tap into loyal customer bases by activating repeat reviewers as brand advocates
3. **Bridge the Location Gap:** Focus marketing efforts on overlooked neighborhoods with high hidden gem density.
4. **Elevate Niche Business Models:** Support food trucks, vegan spots, and brunch-only concepts that perform strongly on satisfaction but lag in awareness.

---

## Tableau Dashboard Visuals

![image](https://github.com/user-attachments/assets/e82ba127-1650-4bf8-b586-1881a9fb810c)

### **Top 15 Earning Restaurant Categories**

**Business Question:** *Which categories have the largest revenue gap between potential and performance?*

**What it shows:** Bar chart ranking categories by total estimated revenue, spotlighting dominant groups like Cajun/Creole and Seafood.

### **Map of Underrated Restaurants**

**Business Question:** *Where are high-rated but low-visibility restaurants located?*

**What it shows:** A map of New Orleans showing star rating (color) and revenue estimate (circle size), revealing clusters of high-potential but underexposed restaurants especially outside typical tourist areas.

### **Revenue Per Review**

**Business Question:** *How do overlooked restaurants compare to top performers in revenue per review?*

**What it shows:** A scatter plot comparing review volume to estimated revenue. Trendline shows positive correlation, but some low-visibility, high-rated restaurants overperform making them key candidates for marketing boosts.

---

## Skills Demonstrated

- Targeted data cleaning and transformation of Yelp JSON
- Sentiment analysis using NLP techniques to capture customer emotion
- Revenue estimation using engineered metrics
- Business feature and category analysis
- Executive dashboard design in Tableau
- Strategy-focused storytelling for decision-makers

---
## Conclusion

This project reveals that success on platforms like Yelp isn't just about star ratings: visibility, loyalty, and product alignment matter. By combining sentiment analysis, business attribute intelligence, and localized insights, we’ve uncovered a powerful opportunity: helping great restaurants get the attention and revenue that they deserve. These hidden gems are not just great restaurants, they are untapped strategic assets.
