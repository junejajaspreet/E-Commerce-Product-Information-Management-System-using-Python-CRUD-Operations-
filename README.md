# 🛒 E-Commerce Product Information Management System (CRUD with Python)

This project implements a basic **Product Information Management System** using Python for e-commerce platforms. It supports **CRUD operations** (Create, Read, Update, Delete) for handling product sales data, details, and descriptions using local files such as CSV, JSON, and TXT.

---

## 🚀 Problem Statement

E-commerce businesses require efficient and accurate management of product information to drive sales and improve user experience. Manual entry often leads to errors, inconsistency, and inefficiency. To solve this, the project automates the management of:

- **Sales Data** (CSV)
- **Product Details** (JSON)
- **Product Descriptions** (TXT)

---

## 📁 Folder Structure

main_folder/
├── sales_data.csv # Sales numbers for 14 days per SKU
├── product_details/ # JSON files per SKU
│ └── details_<Product_SKU>.json
└── product_description/ # TXT files per SKU
└── description_<Product_SKU>.txt


---

## 🔧 Features (CRUD)

### ✅ Create
Adds new product:
- Sales Data
- Product Details
- Product Description

```python
create()

**Read**
Displays a product’s complete information using SKU.
read()

**Update**
Updates product data (e.g., price, specs, description).
update()

**Delete**
Removes all data related to a product by SKU.
delete()
