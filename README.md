# 🛒 Amazon Sales Dashboard (Power BI)

This Power BI project presents an interactive **Amazon Sales Dashboard** built to analyze and visualize product performance, delivery status, and sales distribution across different cities and states in India.

> 📌 **Co-authors**: Siddhesh Panhalkar & Shubham Ghule

---

## 📊 Key Features

- **Overview Page**  
  - Total Sales (`67M`) and Total Orders (`293K`)
  - Sales breakdown by **City** and **State**
  - Monthly **Sales Units Trendline**
  - Filter products by name or category

- **Product-Level Insights**  
  - Interactive filtering by product categories
  - Detailed product and delivery status information

- **Dynamic Metrics**  
  - Toggle between **Sales** and **Units**
  - Real-time visual updates based on slicers, filters

---

## 🧱 Data Model

The dashboard integrates multiple tables to form a star schema:

- **Amazon**: Core transactional data (ASIN, Category, Sales, Courier Status, etc.)
- **amazon-fashion**: Product-level attributes like brand, category, color, etc.
- **Dilvery_Status**: Delivery stages and statuses
- **Sale_Option**: Additional sales context and images

Relationships are set using keys like `ASIN` to maintain referential integrity.

---

## 🚀 How to Use

1. Download the `.pbix` file from this repository.
2. Open it in **Power BI Desktop**.
3. Explore the dashboard by interacting with slicers, filters, and charts.

---

## 📁 File Structure

```
📦 Amazon-Dashboard
 ┣ 📄 Amazon_Dashboard.pbix
 ┗ 📄 README.md
```

---

## 🙌 Authors

- **Siddhesh Panhalkar**  
  Graduate Assistant | Data Science  
  📫[LinkedIn](www.linkedin.com/in/siddhesh-panhalkar)
  
- **Shubham Subhash Ghule**  
  Graduate Assistant | Data Science                         
  📫[LinkedIn](http://www.linkedin.com/in/contact-shubham-ghule)


---

## 📌 Note

This dashboard was created purely for academic and portfolio purposes using sample data. It does not represent real Amazon operational metrics.

---

## ⭐ GitHub Portfolio Tip

If you like this dashboard or found it useful:
- Star this repo ⭐
- Fork it and build your own version!
