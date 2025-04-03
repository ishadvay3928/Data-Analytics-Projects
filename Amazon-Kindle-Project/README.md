# Amazon Kindle Sales Analysis  

### **Project Overview**  
This project analyzes Amazon Kindle book sales data to uncover trends in customer ratings, pricing, and book performance. Using **Python and Power BI**, the analysis identifies factors affecting Kindle book sales and customer preferences.  

### Dataset Information  
- **Dataset Name**: `cleaned_kindle_data.csv`  
- **Source**: Extracted raw file from Kaggle and cleaned for analysis.  
- **Key Features**:
  - `product_id`: Unique ID of the book
  - `Title`: Name of the book.
  - `Author`: Book's author.
  - `soldby`: Publisher of the book
  - `category_id`: ID of category 
  - `Price`: Price in USD.  
  - `Rating`: Average customer rating (1-5).  
  - `Reviews`: Total customer reviews.  
  - `category_name`: Genre or type of book.
  - `isKindleUnlimited`: contains respective boolean answer (True/False)   
  - `isBestSeller`: contains respective boolean answer (True/False)   
  - `isEditorsPick`:  contains respective boolean answer (True/False)  
  - `isGoodReadsChoice `: contains respective boolean answer (True/False)  
  - `Publication Year`: Year of release.  

---

##  Analysis Steps  

### **1. Data Preprocessing**  
- Removed outliners, duplicates, missing values and Whitespaces.  
- Standardized numerical and categorical features.  

### **2. Exploratory Data Analysis (EDA)**  
- **Rating Distribution**: Understanding customer preferences.  
- **Price vs. Ratings**: How pricing impacts ratings and reviews.
- **Top Books**: displayed Top 10 most rated and reviewed books.
- **Average rating and price per category**: Displayed Top categories based on average rating and price.
- **percentage of Bestsellers, Editors' Picks, and Goodreads Choice**: Percentage of Books fall under each Boolean Label 
- **time Series Analysis**: plot increase in Publications with respect to Time.
- **Top Publishers**:  plot top publishers with high publications

### **3. Data Visualization & Dashboard**  
- **Matplotlib & Seaborn**: Used for static data visualizations.  
- **Power BI Dashboard** (`Amazon_kindle_Dashboard.pbix`):  
  - Interactive visual analytics for deeper insights.  

---

## Key Findings & Insights  
   - The Data Analysis reveals that Kindle books generally have high ratings *(4.0-5.0)*, with *Foriegn language and Comics* leading in ratings.
   - There is no strong correlation between price and rating.
   - **Higher-rated books** tend to have lower prices, suggesting customers prefer affordable books.
   - There is more Non-Kindle Unlimited books in comparison to Kindle Unlimited.
   - Majority of books are labeled as Editor's Pick *(66.2%)* and rest small percentage fall under BestSeller and GoodReads Choice Categories.
   - The number of books published has *increased* over time.  

---

## Technologies Used  
- **Python**: `Pandas, NumPy, Matplotlib, Seaborn`  
- **Power BI**: `Amazon_kindle_Dashboard.pbix`  
- **Jupyter Notebook**: `Amazon_Kindle_Sale_Project.ipynb`  
- **CSV Processing**: `cleaned_kindle_data.csv`  

---

## How to Run the Project  

1. **Clone the Repository**  
```bash
git clone https://github.com/ishadvay3928/Amazon-Kindle-Sales-Analysis.git
cd Amazon-Kindle-Sales-Analysis
```

2. **Install Dependencies**  
```bash
pip install pandas numpy matplotlib seaborn
```

3. **Run the Jupyter Notebook**  
- Open `Amazon_Kindle_Sale_Project.ipynb` and run all cells for analysis.  

4. **Power BI Dashboard**  
- Open `Amazon_kindle_Dashboard.pbix` in Power BI to explore interactive insights.

---

## Future Improvements  
   - Implement **machine learning models** to predict best-selling books.
   - Expand dataset with more Kindle book sales records.
   - Perform **sentiment analysis** on book reviews.  

---
## Contributing

Contributions are welcome! Please submit a pull request or open an issue to suggest improvements or report bugs.

---
## Contact  

**Developed by:** Isha Chaudhary

**Contact:** ishadvay3928@gmail.com

**LinkedIn:** https://www.linkedin.com/in/ishachaudhary18/
