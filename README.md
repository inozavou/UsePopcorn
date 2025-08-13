# usePopcorn

A React-based movie search and watchlist application that uses the OMDb API to fetch movie data.
Users can search for movies, view details, rate them, and maintain a personal watched list.

# Features

- Search Movies – Search any movie by title (powered by OMDb API).
- View Movie Details – See movie poster, release date, runtime, plot, actors, director, and IMDb rating.
- Rate Movies – Give your own star rating before adding to the watched list.
- Watched List – Maintain a list of watched movies with your ratings and movie stats.
- Summary Stats – Displays average IMDb rating, average user rating, total watch time.
- Dynamic UI – Automatically updates as you search, select, and rate movies.
- Keyboard Shortcut – Press Escape to close movie details.

# Project Structure

```bash

src/
├── App.js            # Main app logic and state
├── StarRating.js     # Component for interactive star ratings
├── App.css           # Styling
└── index.js          # Entry point
⚙️ Installation
Clone the repository:
```

```bash

git clone https://github.com/your-username/usepopcorn.git
cd usepopcorn
Install dependencies:
```

# Usage

- Type at least 3 characters in the search bar to fetch matching movies.
- Click on a movie to view details.
- Use the star rating to rate the movie and click "Add to list" to save it.
- The watched list shows your ratings and allows deletion of any entry.
- Clear the selection by pressing Escape or clicking the back arrow.

# Tech Stack

- React – UI and state management
- OMDb API – Movie data
- CSS – Styling
