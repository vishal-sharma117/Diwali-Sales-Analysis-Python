# Diwali-Sales-Analysis-Python
Exploratory data analysis of Diwali sales using Python (Google Colab) and CSV data to find customer &amp; sales insights.
# Diwali Sales Analysis – Python & Google Colab

## 📌 Project Overview
This project analyzes **Diwali Sales Data** using **Python in Google Colab**.  
The objective is to identify **high-value customer segments**, understand **spending patterns**, and evaluate **top-performing product categories** during the Diwali season.

The analysis focuses on:
- Customer demographics (age, gender, marital status, state, zone, occupation)
- Order and revenue distribution
- Product category performance
- Customer segmentation for better targeting

---

## 📂 Files in this Repository

| File Name                     | Description                                   |
|-------------------------------|-----------------------------------------------|
| `Diwali_Sales_Analysis.ipynb` | Main Google Colab notebook (Python code)     |
| `Diwali_Sales_Data.csv`       | Raw Diwali sales dataset (CSV file)           |
| `README.md`                   | Project documentation                         |

---

## 🔗 Open Notebook in Google Colab

Click below to directly open the notebook in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/17QyYfb2pp_5ji0BqnMZmePf0bar5XIKK#scrollTo=HkUaOg-U8bXM)

---

## 🧾 Dataset Details

**File:** `Diwali_Sales_Data.csv`  
Important columns include:

- `User_ID` – Unique customer ID  
- `Cust_name` – Customer name  
- `Gender` – Male/Female  
- `Age`, `Age Group` – Customer’s age and age bracket  
- `Marital_Status` – Married or Unmarried  
- `State` – Customer’s state  
- `Zone` – Region (North/South/East/West)  
- `Occupation` – Customer’s job category  
- `Product_ID` – Unique product identifier  
- `Product_Category` – Product category  
- `Orders` – Number of orders placed  
- `Amount` – Total purchase amount  

---

## 🛠 Technologies Used

- **Python (Google Colab)**  
- **Pandas** – Data cleaning and processing  
- **NumPy** – Numerical operations  
- **Matplotlib / Seaborn** – Data visualization  
- **Jupyter/Colab Notebook** – Interactive environment  

---

## 📊 Analysis Performed in Notebook

The notebook includes the following steps:

### 1. **Data Import**
- Loading CSV using `pandas.read_csv()`

### 2. **Data Cleaning**
- Removing unnecessary columns  
- Handling missing values  
- Converting data types (e.g., `Amount` to numeric)

### 3. **Understanding Dataset**
- Checking unique values for demographic attributes  
- Identifying data distributions

### 4. **Exploratory Data Analysis (EDA)**
- Gender-wise purchase trends  
- Age group vs total amount  
- Marital status vs spending levels  
- State-wise and zone-wise sales comparison  
- Occupation-based spending behavior  
- Product category-wise performance

### 5. **Visualizations**
- Bar charts  
- Count plots  
- Histograms  
- Boxplots  
- Category comparisons  

### 6. **Business Insights**
- Identification of high-spending customer groups  
- Ranking of top-performing states  
- Key product categories generating higher revenue  
- Recommendations for Diwali marketing strategy  

---

## 🎯 Example Insights

These are the types of insights derived from the analysis:

- Working-age groups tend to generate the highest revenue  
- Gender-based spending patterns often show significant differences  
- A few states contribute the majority of sales  
- Certain occupations show consistently higher purchasing power  
- Auto/Electronics categories may perform better during festive seasons  

*(Exact values depend on the dataset results in the notebook.)*

---

## ▶ How to Run This Project

1. **Download the repository**  
   - Download `Diwali_Sales_Analysis.ipynb` and `Diwali_Sales_Data.csv`

2. **Open the notebook in Google Colab**  
   - Open Colab → `File → Upload notebook`  
   - Select the downloaded `.ipynb` file  
   - Or click the **Open in Colab** button above

3. **Upload the CSV file**  
   - Use `files.upload()` in Colab  
   - Select `Diwali_Sales_Data.csv`

4. **Run all cells**  
   - Go to `Runtime → Run all`  
   - Wait for all visualizations to generate

5. **Review insights and charts**  
   - Scroll through the notebook to analyze outputs  

---

## 📂 Recommended Folder Structure

```text
📁 Diwali-Sales-Analysis-Python
 ├── 📄 Diwali_Sales_Analysis.ipynb
 ├── 📄 Diwali_Sales_Data.csv
 └── 📄 README.md

