## Movie App (React + Vite)

A small movie browsing app built with **React** and **Vite** that uses **TMDB (The Movie Database)** to:

- Show **popular movies**
- **Search** for movies
- **Save favorites** (persisted in `localStorage`)

### Features

- **Home** (`/`): popular movies + search
- **Favorites** (`/favorites`): view/remove your saved movies
- **Persistent favorites**: stored in the browser (no backend)

### Tech stack

- **React 18**
- **React Router**
- **Vite**
- **ESLint**
- **TMDB API**

### Getting started

Prereqs: **Node.js** (recommended: LTS) and **npm**

Install dependencies:

```bash
cd frontend
npm install
```

Add your TMDB API key:

- Open `frontend/src/services/api.js`
- Set `API_KEY` to your TMDB key

Run the dev server:

```bash
cd frontend
npm run dev
```

Build for production:

```bash
cd frontend
npm run build
```

Preview the production build locally:

```bash
cd frontend
npm run preview
```

### Project structure

```text
movie_react/
  frontend/              # React app (Vite)
    src/
      components/        # UI components (MovieCard, NavBar)
      contexts/          # Movie favorites context (localStorage)
      pages/             # Routes (Home, Favorites)
      services/          # TMDB API calls
      css/               # Styling
```

### Notes

- **TMDB attribution**: This product uses the TMDB API but is not endorsed or certified by TMDB.
