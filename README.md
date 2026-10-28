# CineScope — Movie Discovery App

CineScope is a full-stack movie discovery application built with React, Node.js, Express, and MongoDB. Users can discover movies, search titles, filter results, view movie details, and manage a wishlist.

## Features

- 🎬 Movie discovery and search
- 🔎 Genre filtering and sorting
- 📄 Pagination
- 🎥 Movie details
- ❤️ Persistent wishlist
- 📱 Responsive UI
- ⚡ Server-side caching
- 🛡️ Error handling and API abstraction

## Tech Stack

- **Frontend:** React, Vite, Tailwind CSS, Axios, React Router
- **Backend:** Node.js, Express.js
- **Database:** MongoDB, Mongoose
- **API:** Watchmode
## API Endpoint

| Method | Endpoint                 | Description          |
| ------ | ------------------------ | -------------------- |
| GET    | `/api/movies/discover`   | Discover movies      |
| GET    | `/api/movies/search`     | Search movies        |
| GET    | `/api/movies/genres`     | Get genres           |
| GET    | `/api/movies/:id`        | Movie details        |
| GET    | `/api/wishlist`          | Get wishlist         |
| POST   | `/api/wishlist`          | Add to wishlist      |
| DELETE | `/api/wishlist/:movieId` | Remove from wishlist |

## AI Usage

## AI Usage

AI tools were used only as a supporting reference during development. The application was designed, implemented, reviewed, and tested by me.

## Data Source

Movie and streaming information is provided by the Watchmode API. CineScope is an independent project and is not affiliated with or endorsed by Watchmode.

## Developer
Esha Rawal













        |
               +---- Wishlist
