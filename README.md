# 🛍️ ShopZone — E-commerce Website

A clean, responsive, and fully functional E-commerce website built with **React**, **Tailwind CSS**, and powered by the **DummyJSON Product API**.
Includes complete product browsing features like category filtering, search, product details, and pagination — all with smooth routing and error handling.

🌐 **Live Demo**: [react-mini-project-ecom-website.vercel.app](https://react-mini-project-ecom-website.vercel.app/)

---

## 📸 Preview

> <img width="960" height="540" alt="image" src="https://github.com/user-attachments/assets/b363ad93-c7d4-457a-87c3-579d27ee3ee6" />


---

## 🚀 Features

* 🔍 Search products by name (via API)
* 📂 Browse by category
* 📄 Pagination to navigate large product lists
* 🛒 View full product details
* 🧱 Fully functional routing with React Router
* ❌ 404 Not Found page for invalid URLs
* ⚠️ Graceful error handling on all fetch operations
* 🎨 Clean, responsive UI with TailwindCSS
* 🧼 Minimal design using reusable components

---

## 💪 Tech Stack

| Technology    | Role                        |
| ------------- | --------------------------- |
| React         | Frontend framework          |
| JavaScript    | Core logic                  |
| Tailwind CSS  | Styling & responsive design |
| HTML/CSS      | Layout and base styles      |
| React Router  | Routing and navigation      |
| DummyJSON API | Fake REST API for products  |
| Vercel        | Deployment                  |

---

## 📁 Folder Structure

```
src/
├── assets/
│   └── image.png          # Product image
│
├── components/
│   ├── Header.jsx
│   ├── Footer.jsx
│   └── ProductCard.jsx
│
├── pages/
│   ├── HomePage.jsx
│   ├── ViewPage.jsx           # Single product view
│   ├── ViewCategoryPage.jsx   # Products by category
│   ├── ProfilePage.jsx
│   └── NotFoundPage.jsx
│
└── App.jsx
    main.jsx
```

---

## 📦 API Used

All product data is fetched from the free [DummyJSON Products API](https://dummyjson.com/).
Example search endpoint used:

```bash
https://dummyjson.com/products/search?q=phone
```

---

## 🧑‍💻 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/your-username/reactmini-project.git
cd reactmini-project
```

### 2. Install dependencies

```bash
npm install
```

### 3. Run the app

```bash
npm run dev
```

> App will start on `http://localhost:5173` (or your default Vite port)

---

## 🤛🏼 Author

Made with ❤️ by **Rajat**
Connect with me on [GitHub](https://github.com/007babayaga)

---

