# 🛍️ Custom WooCommerce Catalog Page (Without Plugins)

This project is a **custom-built WooCommerce-style catalog page** developed entirely with **PHP and WordPress**, **without using any plugins** for importing or displaying products.

It fulfills the assignment requirements to create a **catalog page** that dynamically imports products from a **CSV file** and displays them with sorting, filtering, and infinite scroll — replicating the functionality and layout of the [Blue Nile Wedding Rings Catalog](https://www.bluenile.com/wedding-rings/all-wedding-rings?hasNoStones=yes).

---

## ⚙️ Features

- **📦 CSV-Based Product Import**  
  Imports all products (name, price, image, category, etc.) directly from a CSV file using a custom PHP function — no plugins required.

- **🛍️ Dynamic Catalog Page**  
  Displays all imported products in a grid layout, styled similarly to the Blue Nile catalog.

- **💰 Price Filter**  
  Enables filtering of products within a specific price range.

- **↕️ Sorting Options**  
  Allows sorting by:
  - Price: Low to High  
  - Price: High to Low  
  - Most Popular

- **👫 Category & Gender Filters**  
  Includes filters for sub-category and gender (Men/Women).

- **🔄 Infinite Scroll**  
  Loads 12 products initially and automatically loads more as the user scrolls down.

- **📄 Product Details Page**  
  Each product links to a **custom product details page**, dynamically loaded from the same CSV file.

- **🚫 No Plugin Usage**  
  The entire functionality is implemented manually using PHP, HTML, CSS, and JavaScript — without WooCommerce or any external WordPress plugins.

- **⚡ AJAX Integration**  
  AJAX is used for smooth interactions like wishlist management and infinite scrolling.

---

## 🧠 Technologies Used

- **WordPress (Custom Template Development)**
- **PHP**
- **HTML5 / CSS3**
- **JavaScript (AJAX)**
- **CSV File Handling**

---

## 📁 Project Structure

/theme-root
│
├── templates/
│ ├── shop-page.php # Main catalog page template
│ └── product-details.php # Custom product details page
│
├── assets/
│ ├── csv/products.csv # Product data source
│ ├── images/ # Product images
│ ├── js/custom-shop.js # AJAX and dynamic interactions
│ └── css/style.css # Custom styling
│
└── functions.php # CSV loading and integration


---

## 🧾 How to Use

1. Upload the theme to your **WordPress** installation or hosting environment.  
2. Place the `products.csv` file inside the `/assets/csv/` folder.  
3. Assign the **“Shop Page”** template to a WordPress page.  
4. The catalog will automatically render products dynamically from the CSV data.

---

## 🌈 Additional Enhancements

- Added hover effects on product images for better UX.  
- Used `.webp` images for improved loading speed.  
- Fixed CSS grid alignment and responsiveness.  
- Performed unit testing for catalog and scroll loading behavior.

---

## ✅ Assignment Requirements Covered

- CSV import feature (no manual product addition)  
- Single catalog page resembling Blue Nile layout  
- Price, category, and gender filters  
- Sorting options (Low–High, High–Low, Popularity)  
- Infinite scrolling  
- No use of WooCommerce or third-party plugins

---

## 🌐 Live Demo

🔗 **Hosted Link** [https://keyideas-wedding.iceiy.com/](https://keyideas-wedding.iceiy.com/?)

---

## 🎥 Submission Details

- Assignment: *Build a Catalog Page using WooCommerce / WordPress (No Plugins)*  
- Includes: Backend CSV import, single catalog page, filters, sorting, and infinite scrolling.  
- Bonus: Additional UI enhancements and optimized media usage.

---

### 👨‍💻 Developed By
**Atul Maurya**
