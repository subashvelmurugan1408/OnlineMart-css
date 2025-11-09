
# 🛒 Online Mart

An **Online Mart** website built using **HTML** with both **external CSS** and **internal CSS** for styling.
This project demonstrates how to design a simple and responsive e-commerce landing page where users can browse featured products and learn more about the store.

---

## 🌟 Features

* 🏠 **Homepage** with navigation bar and hero section
* 🛍️ **Product listing** section with cards and hover effects
* 📞 **Contact Us** section with form styling
* 🎨 Uses **external CSS file** for overall layout and **internal CSS** for specific element customization
* 📱 **Responsive design** for different screen sizes

---

## 🧩 Project Structure

```
Online-Mart/
│
├── index.html
├── css/
│   └── style.css
├── images/
│   ├── logo.png
│   ├── banner.jpg
│   └── products/
│       ├── product1.jpg
│       ├── product2.jpg
│       └── product3.jpg
└── README.md
```

---

## 💻 Technologies Used

* **HTML5** – structure and layout
* **CSS3** – styling and responsiveness

  * **External CSS:** for general layout and styling
  * **Internal CSS:** for specific components or overrides

---

## 🧱 How to Run the Project

1. **Clone or Download** this repository:

   ```bash
   git clone https://github.com/yourusername/online-mart.git
   ```
2. Open the project folder.
3. Open the `index.html` file in your web browser.

---

## 🪄 Example Code Snippets

### **index.html**

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Online Mart</title>

  <!-- External CSS -->
  <link rel="stylesheet" href="css/style.css" />

  <!-- Internal CSS -->
  <style>
    .highlight {
      color: #ff6f00;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <header>
    <h1 class="highlight">Welcome to Online Mart</h1>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#products">Products</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="products">
    <h2>Our Products</h2>
    <div class="product-card">
      <img src="images/products/product1.jpg" alt="Product 1">
      <h3>Fresh Apples</h3>
      <p>$2.99 / kg</p>
    </div>
  </section>

  <footer>
    <p>© 2025 Online Mart. All rights reserved.</p>
  </footer>
</body>
</html>
```

---

### **css/style.css**

```css
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f9f9f9;
}

header {
  background-color: #2d2f36;
  color: white;
  padding: 15px 0;
  text-align: center;
}

nav ul {
  list-style: none;
  padding: 0;
}

nav ul li {
  display: inline-block;
  margin: 0 15px;
}

nav ul li a {
  color: white;
  text-decoration: none;
}

.product-card {
  display: inline-block;
  background: white;
  margin: 15px;
  padding: 10px;
  border-radius: 8px;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
  transition: transform 0.3s ease;
}

.product-card:hover {
  transform: translateY(-5px);
}
```

---

## 📸 Screenshots

| Homepage                                | Product Section                             |
| --------------------------------------- | ------------------------------------------- |
| ![Homepage](images/screenshot-home.png) | ![Products](images/screenshot-products.png) |

---

## 🧑‍💻 Author

**Your Name**
📧 [your.email@example.com](mailto:your.email@example.com)
🌐 [GitHub Profile](https://github.com/yourusername)

---

## 📜 License

This project is licensed under the **MIT License** — feel free to use and modify it.

---

Would you like me to include a **responsive design section** (like media queries) in the CSS and mention it in the README too?
