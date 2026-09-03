# ShopLine

> A practical offline Android application for fast product-based calculations and counter billing.

ShopLine is a lightweight Android application designed to simplify everyday counter calculations for shops where products are sold by weight.

The project started as a simple calculator and has evolved into a working product and billing foundation with product management, weight/price calculations, bill handling, and Excel/CSV data import and export.

**Current Status:** Working Version 1.0 — Actively Under Development

---

## 📱 Overview

ShopLine is designed around a simple goal:

**Make repetitive counter calculations faster, easier, and less error-prone.**

Instead of manually calculating the price for a given amount or weight, the user can select a product, use its stored selling rate, calculate the required quantity or price, and add the result directly to the current bill.

The application is designed to work **offline**, with product information stored locally on the device.

---

## ✨ Current Features

### 🧮 Quick Calculator

- Select a stored product
- Automatically display the product's selling rate
- Calculate ₹ → grams
- Calculate grams → ₹
- Enter the required amount or weight
- Instantly calculate the corresponding quantity or price
- Add calculated items directly to the bill

### 🛒 Product Management

Products can currently contain:

- Product code
- Product name
- Category
- Unit
- Selling rate
- Optional cost rate
- Automatically calculated rate information

Products can also be:

- Added
- Edited
- Deleted
- Searched by product name or code

### 🧾 Counter Billing

The current billing workflow supports:

- Adding multiple products to a bill
- Product-wise input and calculated weight
- Product-wise price
- Automatic bill total
- Entering the amount received from the customer
- Automatic change calculation
- Removing individual items
- Clearing the current bill

### 📊 Product Data Import / Export

ShopLine currently supports product data exchange through:

- Excel (.xlsx) import
- Excel (.xlsx) export
- CSV (.csv) import
- CSV (.csv) export

This makes it easier to work with an existing product list instead of entering every product manually.

### 📵 Offline Operation

ShopLine is designed to work without an internet connection for its core calculator and product functionality.

Product information is stored locally on the device.

---

## 🎯 Example Workflow

A typical counter transaction can work like this:

1. Select a product.
2. View its stored selling rate.
3. Enter either:
   - an amount in ₹ to calculate the required grams, or
   - a weight in grams to calculate the price.
4. Add the item to the current bill.
5. Add additional products if required.
6. Enter the customer's received amount.
7. ShopLine calculates the total and change automatically.

### Example

If a product is priced at **₹1,100/kg** and the customer takes **100 grams**:

**100 grams = ₹110**

If the customer gives **₹500**:

**Change = ₹390**

---

## 🖥️ Application

### Quick Calculator & Current Bill

The main screen combines product selection, weight/price calculation, and the current bill into one counter-friendly workflow.

### Product Management

Products can be searched, edited, deleted, or added with information such as product code, name, category, unit, selling rate, and optional cost rate.

### Import / Export

Product data can be imported from or exported to Excel and CSV files.

---

## 🏗️ Project Status

ShopLine is currently a **working Version 1.0 foundation**.

The application is **not considered the final product**.

The current version focuses on establishing the core calculation, product-management, data-handling, and billing workflow before expanding into additional business functionality.

Development will continue incrementally, with new features being added and tested while preserving the reliability of the existing workflow.

---

## 🚀 Planned Development

Future versions may expand ShopLine into a more complete shop-management application.

Potential areas of development include:

- Improved billing workflow
- Better product and inventory management
- Purchase and stock tracking
- Sales history
- Daily and monthly reports
- Profit and margin analysis
- Customer management
- Supplier management
- More flexible units and measurements
- Enhanced product search and selection
- Backup and restore
- Data management improvements
- Improved user experience
- Additional shop/business workflows

> Planned features are not necessarily available in the current version.

---

## 🔢 Calculation Logic

For weight-based products, the basic calculation is based on the stored selling rate.

### Price from Weight

`Price = (Selling Rate per kg × Weight in grams) ÷ 1000`

### Weight from Price

`Weight in grams = (Amount × 1000) ÷ Selling Rate per kg`

### Customer Change

`Change = Amount Received − Bill Total`

These calculations allow the same product rate to be used for different customer quantities.

---

## 💾 Data Handling

The current application is designed around local/offline product data.

Supported product data exchange formats:

| Format | Import | Export |
|---|:---:|:---:|
| Excel (.xlsx) | ✅ | ✅ |
| CSV (.csv) | ✅ | ✅ |

This allows product information to be transferred between ShopLine and commonly used spreadsheet-based workflows.

---

## 🛠️ Development

ShopLine is an Android application developed as a practical software project.

The project focuses on:

- Android application development
- UI/UX design
- Business logic
- Weight and price calculations
- Local data handling
- Product management
- Billing logic
- File-based data import/export
- Iterative feature development

The project is being developed incrementally from a working foundation rather than as a single finished release.

---

## 📌 Version 1.0

The current working version includes:

- Product management
- Product search
- Weight/price calculations
- ₹ → grams calculation
- Grams → ₹ calculation
- Current bill
- Total calculation
- Received amount
- Change calculation
- Excel import/export
- CSV import/export
- Offline product storage

---

## 🔒 Project Scope

ShopLine is currently a personal development and portfolio project.

The application is being developed with real-world shop and counter use cases in mind.

The current version should be considered an evolving software project rather than a production-ready enterprise POS system.

---

## 📷 Screenshots

Screenshots of the application will be added to this README as the project develops.

The planned showcase will include:

- Quick Calculator
- Current Bill
- Product Management
- Add Product
- Excel/CSV Import and Export

---

## 🗺️ Roadmap

### Version 1.0 — Current Foundation

- Product management
- Weight/price calculator
- Counter billing
- Offline product data
- Excel/CSV data exchange

### Future Versions

- Advanced billing
- Inventory and stock management
- Purchase tracking
- Sales history
- Reports
- Profit and margin analysis
- Customer management
- Supplier management
- Backup and restore
- Additional shop-management features

The roadmap may change as the application evolves and new requirements are identified.

---

## 🤝 Development Philosophy

ShopLine is being built around a practical principle:

> **Build useful features around real problems, keep the workflow simple, and improve the application step by step.**

The goal is not simply to create another calculator application, but to gradually develop a useful digital tool for everyday shop operations.

---

## 👨‍💻 Project

**ShopLine**

**Current Stage:** Working Version 1.0 — Ongoing Development

Built as a practical Android software project with a focus on real-world business workflows.
