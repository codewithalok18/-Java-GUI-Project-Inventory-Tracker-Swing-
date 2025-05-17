# Inventory Tracker (Java Swing GUI)

This is a **desktop-based Inventory Tracker** application developed using **Java Swing**. It allows users to manage a list of products using a user-friendly graphical interface with features like adding, viewing, searching, and saving product data.

---

## 🎯 Features

- ✅ Add new products (ID, Name, Quantity)
- 📄 View all products in a table (JTable)
- 🔍 Search for a product by its ID
- 💾 Save product data to file
- 💡 Auto-load products on startup (if file exists)
- 🛠️ Built using proper layout managers like `BorderLayout` and `GridLayout`
- 💥 Includes exception handling for invalid input

---

## 🗂️ Project Structure

InventoryTracker/
├── Product.java # Product data model (Serializable)
├── InventoryTracker.java # Main GUI application
├── products.dat # Saved product data file (created after saving)
└── README.md # This file

 Sample GUI Output
🧾 Main Window

+-------------------------------------------------------+
|                Inventory Tracker                      |
+-------------------------------------------------------+

[ Add Product ]
Product ID:       [   101        ]
Product Name:     [ Keyboard     ]
Quantity:         [   20         ]
[ Add Product ] [ Save Products ]

[ Product Table ]
--------------------------------------------------------
|  ID  |     Name     | Quantity |
|------|--------------|----------|
| 101  | Keyboard     |   20     |
| 102  | Mouse        |   35     |
--------------------------------------------------------

[ Search by Product ID: ____ ] [ Search ] [ View All ]

Author
GitHub: codewithalok18
