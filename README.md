# 🎬 MovieFinder Web Application

A sleek, responsive React application built with Vite that allows users to discover movies using The Movie Database (TMDB) API. Users can search for their favorite titles and curate a personal collection of "Favorites."

---

## 🌟 Features

### 🔍 Movie Search
* Real-time movie searching using TMDB API.
* Dynamic display of movie posters, titles, and release dates.
* Search results updated instantly based on user input.

### ❤️ Favorites Module
* **Add to Favorites:** Save movies to a personal list.
* **Remove from Favorites:** Easily manage your collection.
* **Persistent Storage:** Your favorites are saved even after refreshing the page (using Context and LocalStorage).

### 📱 User Interface
* **Home Page:** Browse trending movies and search for specific titles.
* **Favorites Page:** A dedicated view for your saved movies.
* **Responsive Design:** Optimized for both desktop and mobile viewing.
* **Navigation:** Seamless switching between views using React Router.

---

## 🚀 Tech Stack

* **Frontend:** React (Vite)
* **State Management:** React Context API
* **Routing:** React Router DOM
* **API:** The Movie Database (TMDB)
* **Styling:** Modular CSS

---

## 📁 Project Structure

```text
movie-searching-website/
├── public/              # Static assets (Vite logo)
├── src/
│   ├── assets/          # Icons and images
│   ├── components/      # MovieCard.jsx, NavBar.jsx
│   ├── contexts/        # MovieContext.jsx (State management)
│   ├── css/             # Styling (App.css, Home.css, etc.)
│   ├── pages/           # Home.jsx, Favorites.jsx
│   ├── services/        # api.js (TMDB API integration)
│   ├── App.jsx          # Main application logic
│   └── main.jsx         # Application entry point
├── .env                 # API keys and environment variables
└── package.json         # Project dependencies

```
Good code is like a good movie — simple, clear, and worth watching. 🎬✨
