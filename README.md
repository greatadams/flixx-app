# 🎬 Flixx – Movie & TV Discovery Web App

Live Demo: [https://flixx-app-bice.vercel.app/index.html](https://flixx-app-bice.vercel.app/index.html)

---

## 📌 Overview

Flixx is a responsive web application that allows users to browse popular movies and TV shows, search for specific titles, and view detailed information including ratings, genres, release dates, and production companies.

The app consumes data from the **TMDB (The Movie Database) API** and provides a clean, modern UI for discovering entertainment content.

---

## 🚀 Features

- Browse **popular movies** and **TV shows**
- "Now Playing" carousel using Swiper.js
- Search movies or TV shows by keyword
- Pagination for search results
- Movie & TV show detail pages
- Ratings, genres, overview, runtime, budget & revenue info
- External links to official movie pages
- Responsive design (mobile friendly)
- Loading spinner for API requests

---

## 🛠️ Tech Stack

- **JavaScript (ES6+)**
- **HTML5**
- **CSS3**
- **TMDB REST API**
- **Swiper.js** (carousel)
- Font Awesome (icons)

---

## 📂 Project Structure

```
flixx-app/
│
├── index.html
├── shows.html
├── search.html
├── movie-details.html
├── tv-details.html
│
├── css/
│   ├── style.css
│   └── spinner.css
│
├── js/
│   └── script.js
│
├── lib/
│   ├── swiper.js
│   ├── swiper.css
│   └── fontawesome.css
│
└── images/
```

---

## ⚙️ How It Works

- The app fetches data from the TMDB API using `fetch` and `async/await`
- Routing between pages is handled using query parameters (e.g. `movie-details.html?id=123`)
- Search results are paginated using API parameters
- Swiper.js is used for the "Now Playing" slider

---

## 🔐 API Key Note

This project uses the TMDB API. For production use, the API key should be stored in environment variables instead of directly in the source code.

---

## 📸 Screenshots (Optional)

You can add screenshots here later:

```
![Home Page](screenshots/home.png)
![Movie Details](screenshots/details.png)
```

---

## 📈 Future Improvements

- Convert to React for better state management
- Add user authentication
- Save favorites / watchlist
- Improve accessibility (ARIA labels)
- Add unit testing
- Hide API key using environment variables

---

## 👨‍💻 Author

Great Adamu
Computer Science Student – Brandon University
Full Stack Java Developer

LinkedIn: [https://www.linkedin.com/in/great-adamu/](https://www.linkedin.com/in/great-adamu/)

---

## 📜 License

This project is for educational and portfolio purposes.
