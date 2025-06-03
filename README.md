# Airbnb Listing Success Analysis

This project explores what makes an Airbnb listing successful by analyzing data from Stockholm, Sweden and Sydney, Australia. Using statistical modeling, sentiment analysis, and feature engineering, we identified patterns in listing attributes and guest reviews that correlate with higher engagement and review volume.

📎 **[View Final Presentation](https://docs.google.com/presentation/d/1wlBCm0O346PdRUMouf3RqVSRVr2Ti6lLwWI5b_cYmJc/edit?usp=sharing)**

## 📌 Project Goals

- Predict listing performance using review count as a proxy for guest interest.
- Identify which features, amenities, and host attributes contribute most to success.
- Analyze guest sentiment to understand how tone aligns with ratings.
- Compare cultural and market differences between two global cities.

## 🧰 Tools & Technologies

- **Python**: pandas, NumPy, scikit-learn, seaborn, NLTK
- **Alteryx**: Data joins, handling nulls, transforming categorical fields
- **Tableau**: Dashboards and visual exploration
- **Excel**: Quick summaries and model output checks
- **Jupyter Notebook**: Modeling pipeline and documentation

## 🔎 Approach

1. **Data Cleaning & Merging**  
   Combined listings, reviews, and calendar datasets. Cleaned missing values and standardized fields for modeling.

2. **Feature Engineering**  
   Created dummy variables for host status, amenities, neighborhoods, and property types. Normalized numerical fields.

3. **Modeling Techniques**  
   - **Lasso Regression**: Regularized model to isolate meaningful predictors  
   - **Random Forest**: Captured non-linear relationships  
   - **SelectKBest**: Ranked variable importance based on statistical tests

4. **Sentiment Analysis**  
   Used NLTK and TextBlob to score polarity and subjectivity of guest reviews. Mapped sentiment trends to star ratings.

5. **Cross-City Comparison**  
   Compared top predictors of success in Stockholm vs. Sydney to uncover geographic patterns.

## 💡 Key Findings

- **Superhost status** was a strong predictor of high review volume across both cities.
- In **Stockholm**, guests valued practical amenities: washing machines, dishwashers, and kitchens stood out.
- In **Sydney**, comfort and experience-oriented features like pools and stylish decor were more influential.
- **Positive sentiment** in reviews closely tracked with higher ratings. Common keywords in top reviews included _clean_, _cozy_, and _comfortable_; low-rated listings often included _dirty_, _cramped_, or _noisy_.

## 📊 Outcomes

By combining structured data modeling with unstructured review text, this project highlights how hosts can tailor listings to maximize guest satisfaction and engagement. It also demonstrates the value of aligning data science techniques with real-world business questions in the short-term rental market.

---
