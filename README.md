# 🛒 Amazon Sales Dataset Analysis

This project involves analyzing Amazon product data to understand **pricing**, **ratings**, and **discount patterns**. Through data cleaning, visualization, and insight generation, it provides **strategic recommendations** to improve product visibility, optimize pricing, and boost sales performance.


## 📌 Summary

By exploring product attributes such as pricing, ratings, discount percentage, and category, this analysis uncovers valuable business insights to support decision-making in e-commerce optimization.

## 🧾 Dataset Features

**1.Product Name** : Define the product name

**2.Actual Price** : The show actual price of that product

**3.Discounted Price** : The show discount price of product 

**4.Discount Percentage** : percentage of discount

**5.Rating** : To show the rating of particular of that product

**6.Rating Count** : rating count of product

**7.category** : Catrgory of that product.i.e the product is belongs to which category.

## 🧰 Tools and Libraries Used

- **Pandas** – Data manipulation and analysis  
- **NumPy** – Mathematical operations  
- **Matplotlib & Seaborn** – Data visualization  
- **YData Profiling** – Auto-generated profile reports  
- **Jupyter Notebook** – Interactive analysis environment  


## 🔍 Steps of Exploratory Data Analysis (EDA)

### 1. 📥 Data Import  
- Loaded dataset using **pandas** in Jupyter Notebook.

### 2. 🧹 Data Cleaning  
- Removed symbols like `₹` and `,` from price columns.  
- Converted **discount_percentage**, **rating**, and **rating_count** to numeric formats.  
- Handled invalid entries (e.g., symbols like `|`) and missing/null values.  

### 3. 🔄 Data Transformation  
- Analyzed product performance using descriptive statistics.  
- Identified top-rated and most-reviewed products.

### 4. 📊 Data Visualization  
- Created insightful visualizations using bar charts, histograms, line plots, and scatter plots.  
- Examined relationships between **price**, **discount**, **rating**, and **review count**.

#### 🔗 Method Chaining 

To keep the data transformation process clean, readable, and efficient, **method chaining** was used for cleaning and preprocessing. This approach avoids intermediate variables and applies transformations in a step-by-step pipeline.

✅ Benefits of Method Chaining
- Clean and readable transformation pipeline
- Easier to debug and maintain
- Encourages functional-style data processing
- Ideal for notebooks and scripts where clarity is important

## 💡 Recommendations

### 📊 Discount Percentage Distribution
**📝 Observation**: Few or no products offer discounts >60%  
**✅ Recommendation**: Track customer response to these and use them to boost site traffic and move unsold stock.

### 💰 Price vs Rating
**📝 Observation**: Final price drops for highly rated products, which is counterintuitive  
**✅ Recommendation**: Consider raising prices slightly for high-rated, low-priced products where sales volume is strong — customers may still buy due to trust.

### 🔻 Discount vs Actual Price
**📝 Observation**: Customers shy away from high prices even with small discounts  
**✅ Recommendation**: Promote EMI options + moderate discounts (30–40%) to increase conversion of expensive items.

**📝 Observation**: High-priced items with low discounts can appear less attractive  
**✅ Recommendation**: Use product pages and ads to emphasize features, durability, warranties, or brand trust.

### 🧠 Behavioral & Segment-Based Pricing
**📝 Observation**: Over 110 products lie in the 50–60% discount band  
**✅ Recommendation**: Apply personalized discounts using customer behavior or loyalty data.







