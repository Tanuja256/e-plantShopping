# Paradise Nursery Shopping Application

## Project Name: Paradise Nursery

Welcome to **Paradise Nursery** – where green meets serenity! Paradise Nursery is an online houseplant e-commerce web application developed with **React** and **Redux Toolkit**. It allows plant enthusiasts to explore categorized houseplants, learn about their unique benefits, manage their shopping cart, and smoothly navigate through their shopping experience.

---

## 🌿 Features

- **Welcoming Landing Page**: Beautiful greenhouse background with company introduction, mission statement, and a "Get Started" call-to-action button.
- **Categorized Plant Catalog**: Browse over 18 unique houseplants organized into distinct categories:
  - *Air Purifying Plants*
  - *Aromatic Fragrant Plants*
  - *Insect Repellent Plants*
  - *Medicinal Plants*
  - *Low Maintenance Plants*
- **Plant Details**: Each plant card displays a high-quality thumbnail image, name, description, and price.
- **Dynamic Redux Shopping Cart**:
  - Add plants to the cart directly from the catalog.
  - "Add to Cart" button automatically disables with an "Added to Cart" label once added.
  - Dynamic navbar cart icon with real-time total item count badge.
  - Increment and decrement item quantities within the cart.
  - Automatically remove items or delete items directly with the delete button.
  - Real-time calculation of individual item subtotal and overall cart total.
- **Responsive Navigation**: Persistent navigation bar allowing seamless movement between Home, Plant Catalog, and Shopping Cart.
- **Checkout & Continue Shopping**: Easy return to catalog and placeholder checkout modal.

---

## 🛠️ Tech Stack

- **React 18** (Vite)
- **Redux Toolkit** & **React-Redux**
- **JavaScript (ES6+)**
- **CSS3** (Responsive design, animations, and custom styling)

---

## 📁 Project Structure

```text
e-plantShopping/
├── public/
├── src/
│   ├── assets/
│   ├── AboutUs.css         # Styling for About Us section
│   ├── AboutUs.jsx         # Company background, mission, and overview
│   ├── App.css             # Landing page background and layout styles
│   ├── App.jsx             # Main landing page with "Get Started" toggle
│   ├── CartItem.css        # Shopping cart page styling
│   ├── CartItem.jsx        # Shopping cart view with item controls and totals
│   ├── CartSlice.jsx       # Redux Toolkit slice managing cart state
│   ├── ProductList.css     # Product listing and navbar styles
│   ├── ProductList.jsx     # Houseplant catalog grouped by categories
│   ├── store.js            # Redux store configuration
│   ├── index.css           # Global CSS reset
│   └── main.jsx            # Application entry point with Redux Provider
├── package.json
└── README.md
```

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/Tanuja256/e-plantShopping.git
cd e-plantShopping
```

### 2. Install dependencies
```bash
npm install
```

### 3. Start development server
```bash
npm run dev
```

### 4. Build for production
```bash
npm run build
```

---

## 📄 License

This project is licensed under the MIT License.
