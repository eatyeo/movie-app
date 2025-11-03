# Movie Finder App
A simple and modern movie browsing web application built with **React** and powered by **The Movie Database (TMDB) API**.  
It displays a curated list of popular movies and lets users search for titles quickly and easily—all with a clean UI and smooth user experience.

---

## Features
- Browse currently **popular movies**
- **Search** for movies by title
- Displays movie poster, rating, language, and release year
- **Responsive UI** with Tailwind CSS styling
- Loading spinner and friendly error handling states

---

## Tech Stack

| Technology | Usage |
|-----------|--------|
| React | Frontend UI framework |
| Tailwind CSS | Styling and layout |
| TMDB API | Movie data and images |
| Vite | Development environment & build tool |

---

## Setup & Installation
### 1. Clone the Repository
```bash
git clone https://github.com/eatyeo/movie-finder-app.git
cd movie-finder-app

### 2. Install Dependencies
npm install

### 3. Add Your TMDB API Key
Create a `.env` file in the root of the project and add:
VITE_TMDB_API_KEY=YOUR_TMDB_API_READ_ACCESS_TOKEN

Use the TMDB Read Access Token (Bearer token), not the simple API key.
Get it from: https://www.themoviedb.org/settings/api

### 4. Run the Development Server
npm run dev
Open in your browser:
http://localhost:___/

---

## Project Structure
src/
  components/
    MovieCard.jsx
    Search.jsx
    Spinner.jsx
  App.jsx
  index.css

---

## Acknowledgements
Movie data provided by The Movie Database (TMDB) — https://www.themoviedb.org/