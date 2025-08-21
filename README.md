# Diwali Sales Analysis

## 📌 Project Overview
This project analyzes Diwali sales data using Python and Jupyter Notebook. The main objective is to gain insights into customer purchasing behavior, product performance, and overall sales trends during the Diwali festival season.

The repository consists of:
- **Diwali Sales Data.csv** → Raw dataset containing transaction records.
- **Diwali_Sales_Analysis.ipynb** → Jupyter Notebook with data cleaning, analysis, and visualization.
- **README.md** → Project documentation.

---

## 📂 Dataset Description
The dataset `Diwali Sales Data.csv` contains customer purchase details. Some key columns include:
- **User_ID** → Unique identifier for each customer  
- **Cust_name** → Customer name  
- **Product_ID** → Unique identifier for products  
- **Product_Category** → Category of purchased products  
- **Gender** → Gender of customer  
- **Age Group** → Customer age bracket  
- **State** → Customer location  
- **Occupation** → Customer occupation  
- **Marital_Status** → Marital status of customer  
- **Orders** → Number of orders placed  
- **Amount** → Total purchase amount  

---

## 🧹 Data Cleaning
Steps performed in the notebook:
1. Removed null or missing values.  
2. Standardized column names for consistency.  
3. Converted numerical data types where required.  
4. Filtered irrelevant data entries.  

---

## 📊 Exploratory Data Analysis (EDA)
Key insights generated from the analysis:

- **Customer Demographics:**  
  - Majority of buyers were **female customers**.  
  - Age group **26-35 years** had the highest number of purchases.  

- **Geographical Trends:**  
  - Top purchasing states included **Uttar Pradesh, Maharashtra, and Karnataka**.  

- **Occupation Analysis:**  
  - Customers from **IT, Healthcare, and Aviation sectors** contributed significantly.  

- **Sales Insights:**  
  - High sales observed in categories such as **Clothing & Apparel, Food, and Electronics**.  
  - Customers with **married status** contributed more to sales compared to unmarried.  

---

## 📈 Visualizations
The notebook includes several plots using **Matplotlib** and **Seaborn**:
- Bar charts for gender distribution  
- Age group analysis  
- State-wise sales contribution  
- Occupation vs purchase amount  
- Product category performance  

---

## 🛠️ Tech Stack
- **Python Libraries:** Pandas, NumPy, Matplotlib, Seaborn  
- **Tools:** Jupyter Notebook  

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone <repo_link>
   cd Python_Diwali_Sales_Analysis-main
   
2. Create a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate   # On Mac/Linux
    venv\Scripts\activate      # On Windows

3. Install dependencies:
    ```bash
    pip install -r requirements.txt

4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook Diwali_Sales_Analysis.ipynb

  ## 📌 Conclusion
The Diwali Sales Analysis provides valuable insights into customer behavior and business performance during the festive season:

- **Demographics:** Majority of buyers were **female customers**, especially in the **26-35 years** age group.  
- **Geography:** States like **Uttar Pradesh, Maharashtra, and Karnataka** contributed the highest sales.  
- **Occupation:** Customers from **IT, Healthcare, and Aviation sectors** were top contributors.  
- **Product Categories:** High demand was observed in **Clothing & Apparel, Food, and Electronics**.  
- **Marital Status:** **Married customers** showed a higher purchase tendency compared to unmarried customers.  

✅ These insights can help businesses design **targeted marketing campaigns, optimize inventory management, and improve customer engagement strategies** during festive sales.
## 🤝 Contribution
Contributions are always welcome!  

If you'd like to contribute:  
1. Fork the repository  
2. Create a new branch (`git checkout -b feature-name`)  
3. Make your changes and commit (`git commit -m "Add new feature"`)  
4. Push to the branch (`git push origin feature-name`)  
5. Open a Pull Request  

---

## 📜 License
This project is licensed under the **MIT License**.  

You are free to use, modify, and distribute this project with proper attribution.  
See the [LICENSE](LICENSE) file for more details.


