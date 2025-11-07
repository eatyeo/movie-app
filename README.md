# Movie Finder App
A modern and lightweight movie discovery web app built with **React**, powered by **The Movie Database (TMDB)**, and enhanced with **Appwrite** for storing trending search data.

Users can browse popular titles, search for movies in real-time (with **debounced input** to reduce API calls), and view trending movies based on the **most-searched exact matches** across the app. The UI is clean, responsive, and fast.

## Features
- Browse currently **popular** movies
- **Search** for movies by title with optimized debounced input
- Displays movie poster, rating, language, and release year
- **Trending section** powered by Appwrite (ranks movies by exact-match search frequency)
- Responsive UI with **Tailwind CSS**
- Loading indicators + error handling for smooth UX

## Tech Stack
- React
- Tailwind CSS
- TMDB API
- Appwrite
- Vite

## Installation
### 1. Clone the Repository
```bash
git clone https://github.com/eatyeo/movie-app.git
cd movie-app
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Add Your TMDB API Key
Create a `.env` file in the root of the project and add:
```bash
VITE_TMDB_API_KEY=YOUR_TMDB_READ_ACCESS_TOKEN
VITE_APPWRITE_ENDPOINT=YOUR_APPWRITE_ENDPOINT
VITE_APPWRITE_PROJECT_ID=YOUR_APPWRITE_PROJECT_ID
VITE_APPWRITE_DATABASE_ID=YOUR_APPWRITE_DATABASE_ID
VITE_APPWRITE_TABLE_ID=YOUR_APPWRITE_TABLE_ID
```
- Use the TMDB Read Access Token (Bearer token), not the simple API key.
- Get it from: https://www.themoviedb.org/settings/api

### 4. Run the Development Server
```bash
npm run dev
```
- Open in your browser:
- `http://localhost:<your-port>`

Install my-project with npm

```bash
  npm install my-project
  cd my-project
```

## Acknowledgements
- Movie data provided by The Movie Database (TMDB) — https://www.themoviedb.org/