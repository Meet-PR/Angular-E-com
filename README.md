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
