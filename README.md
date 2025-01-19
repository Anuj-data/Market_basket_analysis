# **🛒 Market Basket Analysis Using Apriori Algorithm**

**🔍 Discovering Hidden Product Relationships for Business Growth**

---

## **📄 Project Description**
This project implements **Market Basket Analysis** using the **Apriori algorithm** to analyze retail transaction data. By identifying frequent product combinations, the analysis provides actionable business insights, including product placement, bundling strategies, and cross-selling opportunities.

---

## **🎯 Objective**
- 📊 Understand customer purchasing behavior.
- 🛍️ Identify strong product relationships for improving sales strategies.
- 💡 Generate actionable recommendations for business growth.

---

## **🚀 Project Workflow**

### **1️⃣ Data Collection**
- **Dataset:** Retail transactions data containing customer purchases.
- **Key Features:**
  - 🆔 `Customer ID`
  - 🛒 `Product Name`
  - 📅 `Transaction Date`
  - 🔢 `Quantity`

---

### **2️⃣ Data Preprocessing**
- 🧹 Removed unnecessary columns.
- ⚙️ Handled missing values.
- 🔄 Converted data into a transaction matrix format suitable for analysis.

---

### **3️⃣ Implementation of Apriori Algorithm**
- 📈 Extracted frequent itemsets based on minimum support.
- 🔗 Generated association rules using metrics:
  - **Support:** 📊 Frequency of itemsets.
  - **Confidence:** ✅ Likelihood of consequent given antecedent.
  - **Lift:** 🚀 Strength of the rule.

---

### **📊 Visualization**
- 📊 Bar charts created to visualize the top product pairs based on lift values.
- 🔍 Visualized significant item relationships to highlight actionable insights.

---

### **💡 Business Insights**
- 🛒 **Product Placement:** Place yogurt near whole milk and vegetables for higher sales.
- 🤝 **Bundling Strategies:** Promote bundles of rolls/buns and dairy products.
- 🔗 **Cross-Selling:** Suggest related items like yogurt when customers buy whole milk.
- 🎯 **Targeted Marketing:** Personalize offers based on frequent product combinations.

---

## **🔑 Key Findings**

| **🛒 Antecedents**       | **🔗 Consequents**               | **📊 Support** | **✅ Confidence** | **🚀 Lift**  |
|--------------------------|----------------------------------|----------------|-------------------|--------------|
| Yogurt                  | Whole Milk, Other Vegetables    | 0.0718         | 0.2539            | 1.3264       |
| Whole Milk, Other Vegetables | Yogurt                     | 0.0718         | 0.3753            | 1.3264       |
| Whole Milk, Rolls/Buns  | Yogurt                         | 0.0659         | 0.3693            | 1.3049       |
| Yogurt                  | Whole Milk, Rolls/Buns          | 0.0659         | 0.2330            | 1.3049       |
| Whole Milk              | Yogurt, Other Vegetables        | 0.0718         | 0.1568            | 1.3030       |

---

## **💻 Technologies Used**
- **Programming Language:** 🐍 Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Mlxtend
- **Tools:** Jupyter Notebook

---

## **⚙️ How to Run the Project**

1. **📥 Clone the repository:**
   ```bash
   git clone https://github.com/Anuj-data/market-basket-analysis.git
   cd market-basket-analysis


 ## 📦 Install Required Libraries
To install the necessary libraries for this project, run the following command in your terminal:

```bash
pip install pandas numpy matplotlib seaborn mlxtend

```

## 📂 Run the Jupyter Notebook

To open and run the Jupyter Notebook, use the following command:

```bash
jupyter notebook
```

## 📑 Open and Execute

Open and execute the notebook file:

`Market_Basket_Analysis.ipynb`

---

## 📜 Project Deliverables

- ✅ **Cleaned and preprocessed dataset.**
- 📝 **Jupyter Notebook with Apriori implementation.**
- 📊 **Visualizations of top product combinations.**
- 💡 **Business insights and recommendations.**

---

## 👤 Author

**Anuj Negi**

- **GitHub:** 🌐 [Anuj-data](https://github.com/Anuj-data)
- **LinkedIn:** 🌐 [Anuj Negi](https://linkedin.com/in/anuj-negi-8a032830b)
- **Portfolio:** 🌐 [Anuj's Portfolio](https://anujnegi-portfolio.netlify.app/)

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

