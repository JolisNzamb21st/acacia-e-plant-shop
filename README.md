# Acacia E-Plant Shopping Apllication

A modern e-commerce plant shop built with **React** and **Redux Toolkit**.  
This application allows users to browse categorized plants, add items to a shopping cart, and manage cart state dynamically.

>  *“Where beauty blossoms at home!”*

---

##  Features

-  Browse plants grouped by category
-  Add items to cart
-  Real-time cart quantity badge update
-  Prevent duplicate item additions
-  Conditional rendering between product list and cart view
-  Centralized state management using Redux Toolkit
-  Dynamic quantity calculation using `reduce()`
-  Modern card-based UI design
-  Hover animations for product cards
-  Disabled "Add to Cart" button when item already exists
-  Fully responsive layout (Desktop, Tablet, Mobile)
-  Component-based architecture using functional components
-  React Hooks (`useState`, `useSelector`, `useDispatch`)

---

## 🛠️ Tech Stack

- **React.js**
- **Redux Toolkit**
- **React-Redux**
- **CSS3 (Custom Styling)**
- **Functional Components & React Hooks**

---

## 📂 Project Structure

```
src/
│
├── components/
│   ├── ProductList.js
│   ├── CartItem.js
│   ├── CartSlice.js
│
├── ProductList.css
├── store.js
└── App.js

```

---

##  State Management

The application uses **Redux Toolkit** for centralized cart state management.

### Cart Logic Includes:

- Add item to cart
- Track item quantity
- Calculate total number of items
- Add subtotal for each item
- Disable “Add to Cart” button when item already exists
- Render dynamic cart badge

---

##  UI Highlights

- Grid-based product layout
- Category sections 
- Embedded cart badge 
- Card hover animation
- Disabled button styling
- Responsive layout:
  - 3 columns (Desktop)
  - 2 columns (Tablet)
  - 1 column (Mobile)

---

## 🔧 Installation & Setup

Clone the forked repository:

```bash
git clone https://github.com/your-username/acacia-e-plant-shop.git
```

Navigate into the project folder:

```bash
cd acacia-e-plant-shop
```

Install dependencies:

```bash
npm install
```

Start development server:

```bash
npm run dev/preview
```

The app runs at:

```
http://localhost:5173
```

---

##  Learning Objectives

This project demonstrates:

- Component-based architecture
- Props handling
- Conditional rendering
- Redux global state management
- UI responsiveness
- Clean CSS organization
- Real-world e-commerce logic implementation

---

##  Future Improvements

- 🔐 User authentication
- 💳 Checkout system
- 🧾 Order summary page
- 🌙 Dark mode
- 🔍 Search & filtering
- 🗂 Pagination
- 🛍 Product details page
- ☁️ Deployment (Git pages/Vercel / Netlify)
