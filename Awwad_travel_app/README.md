# 🌍 Awwad Travel App

A full-stack travel information web application built using **Node.js, Express, Vanilla JavaScript, SCSS, and Webpack**.  
Users can search for travel destinations, view city details, and interact with a dynamic interface powered by external APIs.

---

## 🔍 Deep Dive

This project uses a clean and scalable architecture combining both **client-side rendering** and a **Node.js backend**:

### 🎨 Frontend
- Built with **Vanilla JavaScript**
- SCSS styling compiled using **Webpack**
- Organized SCSS architecture (breakpoints, global styles)
- Views rendered dynamically from `views/`

### 🧠 Backend
- Node.js + Express server (`server/index.js`)
- API routes to fetch city data (`server/fetchCityInfo.js`)
- Integration with external travel APIs
- Follows modular service-based structure

### ⚙️ Build System (Webpack)
- `webpack.common.js` — Shared config
- `webpack.dev.js` — Development build (Hot reload, source maps)
- `webpack.prod.js` — Optimized production build (minified assets)

### 🧪 Testing
- Jest test suite:
  - `formHandler.test.js`
  - `server.test.js`

This architecture allows clean scaling, organized code, and smooth development workflows.

---

## 🧰 Technologies

### Frontend
- JavaScript (ES6)
- HTML / SCSS
- Webpack Bundler

### Backend
- Node.js
- Express.js

### Tools
- Jest (Testing)
- Babel
- Git & GitHub
- npm

---

## 🚀 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/ahmed-awwad00/Travel_app.git
cd Travel_app/Awwad_travel_app
