# 🛒 BigBasket Market Basket Analysis using Apriori

This project performs **Market Basket Analysis** on BigBasket's transactional data using the **Apriori algorithm** to discover product association rules. These insights can help in **cross-selling, marketing, and inventory decisions**.

---

## 📁 Files

- `Apriori Association Rule Learning.ipynb` – Python script to run Apriori
- `BigBasket.csv` – Transaction dataset (each row is one transaction)
- `README.md` – Project documentation

---

## 📌 Objective

To identify **frequent itemsets** and generate **association rules** from BigBasket customer purchase data that can:
- Improve **product placement**
- Enable **bundling and offers**
- Increase **average cart value**
- Reduce **inventory mismatches**

---

## 📊 Technologies Used

- Python  
- Libraries: `pandas`, `numpy`, `matplotlib`, `apyori`

---

## ⚙️ How to Run

### 1. Clone this repo:
```bash
git clone https://github.com/Asif-17/bigbasket-market-basket-analysis.git
cd bigbasket-market-basket-analysis
```

### 2. Install dependencies:
```bash
pip install pandas numpy matplotlib apyori
```

### 3. Run the script:
```bash
python Apriori Association Rule Learning.ipynb
```

---

## 📈 Sample Output

- Top 10 product pairs with highest **lift**
- Example:
  ```
  milk → bread | Support: 0.005, Confidence: 0.25, Lift: 3.1
  ```

---

## ✅ Results

- Found frequent itemsets of 2 products bought together.
- Highest lift indicates strongest buying relationship.
- Data can drive **data-informed product bundling strategies**.

---

## 📌 Future Scope

- Extend to FP-Growth algorithm for better performance
- Real-time product recommendation system
- Dashboard using Streamlit or Flask for business use
- Use collaborative filtering for personalization

---

## 🔗 References

- [`apyori`](https://pypi.org/project/apyori/) – Apriori Python library
- [Market Basket Analysis](https://en.wikipedia.org/wiki/Association_rule_learning)
- BigBasket (synthetic/public dataset)

---

> 🔧 Developed as part of an AICTE capstone project by [Syed Mohammad Asif Amaan].
