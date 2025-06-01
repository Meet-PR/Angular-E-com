# 🍫 Ghirardelli-Like Chocolate Store Website

Welcome to the **Ghirardelli-Like Chocolate Store**! 🎉  
This is a static web application mimicking the layout and feel of the official Ghirardelli website. Built with **HTML**, **Bootstrap**, and **Font Awesome**, it's ideal for learning responsive design or using as a base for a real chocolate e-commerce project. 🛒

---

## 🌟 Features

- ✅ **Responsive Design** — Looks great on desktop, tablet, and mobile 📱💻
- ✅ **Bootstrap Carousel** — Sliding banner for featured promotions 🎠
- ✅ **Product Sections** — Explore best sellers, categories, Pick & Mix, and more 🍬
- ✅ **Font Awesome Icons** — Heart ❤️ icons to favorite products
- ✅ **Clean Footer** — Organized customer service and company info links 🖌️

---

## 📦 Prerequisites

Ensure you have the following installed:

- [Node.js (v14+)](https://nodejs.org/) 🟢
- npm (comes with Node.js) 📦
- A modern web browser (Chrome, Firefox, etc.) 🌐

---

## 🚀 Installation

```bash
# Clone the repository
git clone https://github.com/your-username/ghirardelli-like-store.git
cd ghirardelli-like-store

# Install all dependencies
npm install
```

---

## 📋 Dependencies

| Package              | Version     | Purpose                                 | Install Command                        |
|----------------------|-------------|------------------------------------------|----------------------------------------|
| `bootstrap`          | ^4.5.2      | Responsive layout & components          | `npm install bootstrap`                |
| `font-awesome`       | ^4.7.0      | Icons like ❤️ and 🛍️                     | `npm install font-awesome`             |
| `jquery`             | ^3.5.1      | Required for Bootstrap JS               | `npm install jquery`                   |
| `@popperjs/core`     | ^2.5.4      | Required for Bootstrap popovers/tooltips| `npm install @popperjs/core`           |

---

## 🧪 Dev Dependency

| Package        | Version     | Purpose                                     | Install Command                            |
|----------------|-------------|---------------------------------------------|--------------------------------------------|
| `http-server`  | ^14.1.1     | Serve static files locally for development | `npm install http-server --save-dev`       |

---

## 🖥️ Usage

### 1. 🔗 Link Dependencies in `index.html`

Add these inside the `<head>` tag:

```html
<link rel="stylesheet" href="node_modules/bootstrap/dist/css/bootstrap.min.css">
<link rel="stylesheet" href="node_modules/font-awesome/css/font-awesome.min.css">
```

Add these before `</body>`:

```html
<script src="node_modules/jquery/dist/jquery.slim.min.js"></script>
<script src="node_modules/@popperjs/core/dist/umd/popper.min.js"></script>
<script src="node_modules/bootstrap/dist/js/bootstrap.min.js"></script>
```

---

### 2. ▶️ Run Local Server

```bash
npx http-server . -p 8080
```

Visit [http://localhost:8080](http://localhost:8080) in your browser to see the chocolatey magic! ✨

---

## 📂 Project Structure

```
ghirardelli-like-store/
│
├── index.html          # Main HTML structure
├── node_modules/       # Installed packages
├── package.json        # npm config & dependencies
├── README.md           # This file!
└── assets/             # (Optional) Images or custom CSS
```

---

## 🖼️ Website Layout Overview

### 🎠 Carousel Section
- 3 sliding images with navigation arrows (Previous/Next)

### 🍫 Explore Best Sellers
- Premium chocolate products with prices and ❤️ icons

### 🛍️ Shop by Category
- Squares | Chocolate Bars | Baking | Hot Cocoa

### 🎁 Chocolate for Every Occasion
- Birthday Gifts, Thank You Gifts, Everyday Treats

### 🍬 Explore Ghirardelli Chocolate
- All Chocolate, Custom Mix, Bulk, Gifts, Sale

### 🛒 Shop Chocolate Bags
- 72%, 86%, Caramel, Sea Salt Almond & more

### 📈 Business Gifts
- Bulk gift options for corporate gifting (up to 400 recipients)

### 🧩 Pick & Mix
- Customize chocolate boxes (100, 200, 500 units, gift boxes/tins)

### 🏷️ Top Categories
- Bulk, Gifts, Pick & Mix, Bars, Baking

### 🍫 Experience Chocolate Squares
- Case packs of 480 units with different flavors

---

## 🖌️ Footer Sections

- **Customer Service**: Shipping, FAQs, Contact, Returns  
- **Business Customers**: Gift Line, Pro Products, Distributors  
- **Our Company**: About, Careers, Store Locator  
- **More Information**: Privacy, Cookies, Site Map  
- **Connect**: LinkedIn | Facebook | Instagram | YouTube  
- **Payments**: Visa | MasterCard  
- **Contact**:  
  📧 Email: CustomerService@example.com  
  ☎️ Phone: 1-888-402-6262  
- © 2025 Ghirardelli Chocolate Company

---

## 🛠️ Customization

- ✨ Add product images by updating `src=""` in `<img>` tags  
- ⚙️ Integrate Angular, React, or Vue to make data dynamic  
- 🎨 Create a custom stylesheet to override Bootstrap classes

---

## 📝 Notes

- This is a **static site** – no cart/checkout logic yet.
- Ideal base for backend integrations using Node.js, Firebase, or Express.
- All assets are loaded locally – works offline once setup.

---

## 🤝 Contributing

Want to add new features or improve layout? Fork and submit a PR! 🙌

```bash
# Step-by-step:
1. 🍴 Fork this repository
2. 🔀 Create a new branch: git checkout -b feature/your-feature
3. 💾 Commit your changes: git commit -m "Add your feature"
4. 📤 Push to GitHub: git push origin feature/your-feature
5. 🚀 Open a Pull Request
```

---

## 📜 License

This project is licensed under the **MIT License**.  
See [`LICENSE`](./LICENSE) for full details.

---

## 🙏 Acknowledgments

- Inspired by [Ghirardelli's official site](https://www.ghirardelli.com/) 🍫  
- Built with ❤️ using [Bootstrap](https://getbootstrap.com/) and [Font Awesome](https://fontawesome.com/)  
- Thanks to the open-source community for making web dev delicious! 🍬✨

---

> 🍫 **Happy coding, and stay sweet!**
