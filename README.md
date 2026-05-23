# WildHunt Project Web

WildHunt is a web application built with React and Vite.  
The project represents a hunting-themed website with pages for home, shop, map/location selection, contact, login, and signup.

---

# Overview

This project is a full-stack web application structure composed of:

- React frontend
- Vite development environment
- React Router navigation
- Leaflet map integration
- Login and signup UI
- Shop page
- Contact page
- Node.js / Express backend structure

---

# Features

- Home page layout
- Navigation header
- Shop page with product cards
- Category filtering
- Search input
- Login modal
- Signup form
- Contact form
- Interactive map with location selection
- Frontend routing using React Router
- Backend setup using Express and MongoDB dependencies

---

# Technologies Used

## Frontend

- React
- Vite
- React Router DOM
- React Leaflet
- Leaflet
- Mapbox GL
- FontAwesome
- CSS

## Backend

- Node.js
- Express.js
- MongoDB
- Mongoose
- CORS
- dotenv
- Nodemon

---

# Project Structure

```bash
WildHunt_Project_Web/
│
├── backend/
│   ├── config.js
│   ├── index.js
│   ├── package.json
│   └── package-lock.json
│
└── frontend/
    └── WildHunt/
        ├── Images/
        ├── public/
        ├── src/
        │   ├── App.jsx
        │   ├── main.jsx
        │   ├── header.jsx
        │   ├── Header.css
        │   ├── Login.jsx
        │   ├── login.css
        │   ├── signup.jsx
        │   ├── signup.css
        │   ├── shop.jsx
        │   ├── Shop.css
        │   ├── map.jsx
        │   ├── map.css
        │   ├── contact.jsx
        │   ├── contact.css
        │   ├── SearchBar.jsx
        │   ├── SearchBar.css
        │   ├── Modal.jsx
        │   └── Modal.css
        │
        ├── index.html
        ├── package.json
        ├── vite.config.js
        └── README.md
```

---

# Main Pages

## Home Page

The home page contains the main website layout, header, and search section.

## Shop Page

The shop page displays product cards and includes:

- Product name
- Product price
- Product image
- Add to cart button
- Category filtering
- Search functionality

## Map Page

The map page uses React Leaflet to display an interactive map.

Users can click on the map to select a location.  
The selected latitude and longitude are displayed on the page.

## Login and Signup

The project includes:

- Login form
- Signup form
- Modal display for authentication UI

## Contact Page

The contact page includes:

- Email information
- Phone information
- Contact form
- Message section

---

# Installation

## Clone the Repository

```bash
git clone https://github.com/Khalil-Boukhalil/WildHunt_Project_Web.git
cd WildHunt_Project_Web
```

---

# Frontend Setup

Go to the frontend folder:

```bash
cd frontend/WildHunt
```

Install dependencies:

```bash
npm install
```

Run the development server:

```bash
npm run dev
```

The frontend will usually run on:

```bash
http://localhost:5173
```

---

# Backend Setup

Go to the backend folder:

```bash
cd backend
```

Install dependencies:

```bash
npm install
```

Run the backend server:

```bash
npm start
```

---

# Available Frontend Scripts

Inside `frontend/WildHunt`:

```bash
npm run dev
```

Start the development server.

```bash
npm run build
```

Build the project for production.

```bash
npm run preview
```

Preview the production build.

```bash
npm run lint
```

Run ESLint checks.

---

# Available Backend Scripts

Inside `backend`:

```bash
npm start
```

Start the backend using Nodemon.

---

# Application Workflow

```text
User opens website
        ↓
Navigates using header
        ↓
Views shop, contact, map, or login/signup
        ↓
Selects products or location
        ↓
Frontend can later connect to backend APIs
        ↓
Backend can store data in MongoDB
```

---





---

# Author

Khalil Bou Khalil


# License

This project is intended for educational purposes.
