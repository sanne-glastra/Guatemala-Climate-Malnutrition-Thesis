# Climate Change and Malnutrition in Guatemala (2000–2017)

![Status](https://img.shields.io/badge/Status-Published_(Honors_Thesis)-success)
![Method](https://img.shields.io/badge/Methods-Multivariate%20Regression%20%7C%20Random%20Forest-orange)
![Focus](https://img.shields.io/badge/Focus-Global%20Health%20%7C%20Econometrics-blue)

## 📌 Project Overview
**Undergraduate Honors Thesis in Quantitative Sciences**

This study explores the intersection of climate change and public health in Guatemala, a country with one of the highest rates of chronic malnutrition (stunting) in the world. By integrating 18 years of climate and health data, this project quantifies how temperature and precipitation anomalies drive malnutrition outcomes, independent of socioeconomic factors.

## ❓ Research Questions
1.  **Relevance:** Are climate indicators a relevant predictor for malnutrition in Guatemala?
2.  **Regional Disparity:** Is there a differential impact of climate on malnutrition between the **Highlands** and the **Lowlands**?
3.  **Risk Ranking:** What are the most important climatic vs. non-climatic factors predicting malnutrition?

## 📂 Data Sources (2000–2017)
The analysis integrated high-dimensional datasets from distinct sources:
* **Health Outcomes:** Stunting (Height-for-Age), Wasting (Weight-for-Height), and Underweight status from **DHS Surveys** & IHME.
* **Climate Data:**
    * **Temperature:** World Bank Climate Change Knowledge Portal
    * **Drought:** FLDAS/USGS Soil Moisture content ($m^3/m^3$) used as a proxy for agricultural drought.
* **Controls:** Socioeconomic indices including maternal education, wealth index, and sanitation access from **DHS Surveys**. 

## 🛠️ Methodology
The study employed a two-stage statistical framework:
1.  **Multivariate Regression:** Used to test the statistical significance of climate variables on malnutrition while controlling for confounders.
2.  **Interaction Modeling:** Specifically tested for differential effects in the "Highlands" region vs. "Lowlands."
3.  **Random Forest Analysis:** Utilized to rank the *relative importance* of predictors (e.g., "Is temperature more important than poverty?").

## 🔍 Key Findings

### 1. Drought & Stunting (The Highlands Link)
* **The Finding:** A reduction in annual soil moisture (drought) coincides with a statistically and practically significant increase in stunting prevalence, with a 1% decrease in annual soil moisture coinciding with a 1.3% increase in stunting prevalance. This relationship was found to be **significantly stronger in the Highlands** compared to the Lowlands. 
* **Indicator Sensitivity:** The study confirms that **long-term drought indicators** (Annual Soil Moisture) are better predictors of malnutrition than seasonal indicators. 

### 2. Temperature & "Frost" Effects
* **The Finding:** A decrease in growing season and annual temperature coincided with an *increase* in stunting in the Highlands. 

### 3. Ranking Risk Factors (Random Forest)
* **Socioeconomics Context:** While climate is a driver, the Random Forest model highlighted that socioeconomic factors remain dominant. **Maternal Height** was the top predictor for stunting, and **Poor Wealth Index** was critical for underweight status. 
* **Underweight Nuance:** Climate had a low effect size for underweight malnutrition, suggesting that economic factors (wealth/poverty) are more immediate drivers for weight outcomes than climate shocks. 

## 💡 Overall Conclusion
Of the many complex drivers of malnutrition in Guatemala, **drought is a critical determinant**, particularly for **chronic malnutrition (stunting) in the Highlands**. However, climate acts within a broader structure of inequality: socioeconomic interventions addressing poverty and maternal health remain essential alongside climate adaptation strategies.

## 📄 Full Thesis
[Read the Complete Honors Thesis (PDF)](Climate_Malnutrition_Guatemala_Thesis.pdf)
