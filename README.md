# The Impact of Showcasing Clothing Items on a Model in terms of Influencing Consumer Behavior

---

## 📝 Project Overview
In the fast-paced retail and fashion landscape, visual presentation plays a crucial role in influencing consumer behavior. 
This project investigates whether showcasing clothing on models significantly impacts consumer purchase intentions, 
with a specific focus on **Zara**, a global fashion leader.  

### 🔍 Research Question:
Does dressing models in clothing enhance consumer purchase desire?  

### 💡 Hypothesis:
Clothing displayed on models can increase consumer purchase intent and potentially boost sales for the brand.  

---

## 🚀 Methodology
To test our hypothesis, we conducted an online survey using **Qualtrics**, targeting 129 respondents with diverse demographics. The survey design included:  

- **Control Group:** Shown clothing items without a model.  
- **Treatment Group:** Shown the same clothing items on a model.  
- **Question Design:**  
  - **Top Wear:** Vest, Hoodie, T-shirt  
  - **Bottom Wear:** Skirt, Shorts, Pants  
- **Demographics Captured:** Gender, Age, Industry, Shopping Cost, Country  
- **Data Cleaning:** Used the `melt` function to transform the dataset into a row-based format, enabling more efficient analysis.  

---

## 📊 Data Analysis and Insights
After data cleaning, we conducted Exploratory Data Analysis (EDA) to assess demographic distribution and response patterns.  

### Key Findings:
- **Demographics:**  
  - 60% of respondents were female.  
  - 97% of respondents were under 30 years old.  
  - Respondents predominantly belonged to the technology, education, and student sectors, with major representation from Taiwan, the USA, and India.  

- **Impact of Visual Presentation:**  
  - The **Average Treatment Effect (ATE)** of **0.154** indicates that displaying clothes on models significantly enhances purchase intent.  
  - **Conditional Average Treatment Effect (CATE):** Bottom wear had a stronger positive effect than top wear, suggesting consumers find it harder to visualize bottoms without a model.  
  - Higher spending groups (monthly shopping expenses > $500) were more positively influenced, indicating that fashion-conscious consumers are particularly affected by model presentations.  
  - Regionally, the effect was most significant in Taiwan (ATE: 0.17), followed by the USA (ATE: 0.13) and India (ATE: 0.12).  
  - **Statistical Power Analysis:** The calculated power (0.9999) confirms the reliability of the observed effect.  

### Statistical Validation:
- Regression analysis confirmed the significance of the treatment effect.  
- Randomization checks validated the balanced distribution between control and treatment groups (p-value: 0.874).  

---

## ⚠️ Challenges and Limitations:
- **Sampling Bias:** Predominantly young (22-30) and female (60%) respondents may limit generalizability.  
- **Limited Coverage:** Focus on top and bottom wear does not fully capture diverse fashion preferences.  
- **Geographical Bias:** High representation from Taiwan may skew regional insights.  
- **Survey Design:** Limited variety in survey questions may restrict nuanced analysis.  

---

## 🗺️ Conclusion:
The study confirms that displaying clothing on models positively influences consumer purchase decisions, 
particularly for bottom wear and among higher-spending fashion-conscious demographics. 
These insights can guide fashion retailers like **Zara** in crafting more effective visual marketing strategies. 
Future research should aim to expand the demographic diversity and include a wider range of clothing items for comprehensive analysis.  

---

## 🛠️ Technologies Used:
- **Survey Tool:** Qualtrics  
- **Data Analysis:** Python (Pandas, NumPy), Jupyter Notebook  
- **Statistical Analysis:** Regression, ATE, CATE, Statistical Power Analysis  
- **Visualization:** Matplotlib, Seaborn  
- **Data Cleaning:** Pandas (melt function)  
