# Walmart---Confidence-Interval-and-CLT-Jul-2024-

# Walmart: Confidence Interval and Central Limit Theorem (CLT)

## 🏪 About Walmart  
Walmart is an American multinational retail corporation that operates a chain of supercenters, discount department stores, and grocery stores across the United States. With over **100 million customers worldwide**, Walmart aims to understand consumer behavior and optimize sales strategies.

## 📌 Business Problem  
The **Walmart Inc. Management team** seeks to analyze customer purchase behavior—specifically **purchase amount**—against demographic factors like **gender, age, and marital status**.  
The key question: **Do women spend more on Black Friday than men?**  
With an assumed **50 million male and 50 million female customers**, Walmart aims to leverage insights to make better business decisions.

## 📊 Dataset  
The dataset consists of **transactional data from Black Friday sales** at Walmart stores.  

### Features:  
- **User_ID** - Unique identifier for each user  
- **Product_ID** - Unique identifier for each product  
- **Gender** - Sex of the user (`Male` or `Female`)  
- **Age** - Age groups in bins (`0-17`, `18-25`, `26-35`, `36-50`, `51+`)  
- **Occupation** - Encoded occupation category  
- **City_Category** - Walmart store location (`A`, `B`, `C`)  
- **StayInCurrentCityYears** - Duration of stay in current city  
- **Marital_Status** - `0` (Single) or `1` (Married)  
- **ProductCategory** - Encoded product category  
- **Purchase** - Purchase amount  

## 📈 Methodology  

### 1️⃣ Data Exploration  
- Imported dataset and performed **basic data analysis** (structure, characteristics, and data types).  
- Detected **missing values & outliers** using box plots, `describe()` method, and null value checks.  

### 2️⃣ Key Data Insights  
- **Gender-based spending analysis**: Compared average spending per transaction between males and females.  
- **Confidence Interval Calculation**: Estimated a **range within which the true population mean purchase amount lies** for male and female customers.  
- **Central Limit Theorem (CLT) Analysis**: Observed how sample size affects distribution and interval width (90%, 95%, and 99% confidence levels).  
- **Comparison of spending habits** based on **marital status and age groups**.  

### 3️⃣ Visual Analysis  
- **Univariate Analysis**: Histogram, count plots, box plots.  
- **Bivariate Analysis**: Heatmaps, pair plots, and comparative box plots.  

### 4️⃣ Business Impact & Recommendations  
📌 **Key Takeaways:**  
- Evaluated whether **male and female spending confidence intervals overlap**, guiding gender-targeted marketing.  
- Assessed **spending variations across age groups** (e.g., highest spenders: **26-35 years old**).  
- Compared spending patterns of **single vs. married customers**.  

📢 **Strategic Recommendations:**  
✔️ **City-Specific Initiatives**: Focus on City_Category 'B' where spending is higher.  
✔️ **Age-Based Marketing**: Target **26-35-year-olds** via personalized promotions & social media campaigns.  
✔️ **Influencer Marketing**: Use **social media influencers** to attract younger buyers.  
✔️ **Occupation-Based Promotions**: Customize offers for **Occupation '4'**, a key customer segment.  
✔️ **Loyalty Programs**: Encourage long-term city residents to boost customer retention.  
✔️ **Gender-Specific Offers**: Develop marketing strategies **targeted at males** based on spending patterns.  


## 🚀 Tools & Technologies  
- **Python**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy.stats`  
- **Statistics**: Confidence Intervals, Central Limit Theorem (CLT), Hypothesis Testing  
- **Visualization**: Boxplots, Histograms, Heatmaps  

---

### 🎯 Conclusion  
This analysis provides Walmart with **data-driven insights** to enhance customer segmentation, pricing strategies, and targeted marketing efforts. By leveraging **statistical inference techniques**, Walmart can optimize promotions and **maximize Black Friday sales**.  

🔗 **Explore the full analysis in the Jupyter Notebooks!** 🚀
