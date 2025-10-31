 API Grid Dashboard — 8 Mini Web Apps

An interactive HTML + JavaScript dashboard that demonstrates how to use fetch() and async/await to call real-world public APIs — all in a single, responsive grid layout.
Perfect for learning how to work with REST APIs, handle asynchronous data, and display dynamic content elegantly in the browser.

 Overview

This project contains 8 mini-apps built entirely with vanilla JavaScript, HTML5, and modern CSS — no frameworks, no build tools, just pure browser magic.
Each tile (or "cell") showcases how to connect to a different public API, handle responses, display data, and gracefully handle errors.

Features
#	Mini App	Description	API Used
1️⃣	🐶 Random Dog	Fetches random dog photos.	dog.ceo API

2️⃣	🐱 Random Cat	Fetches random cat images.	TheCatAPI

3️⃣	🌤️ Weather	Geocode a city name → fetch real-time weather.	Open-Meteo

4️⃣	💱 Currency Converter	Displays USD → EUR exchange rate.	exchangerate.host

5️⃣	🎬 Movie Trending	Fetch trending movies (requires TMDB API key).	The Movie Database

6️⃣	👩‍💻 GitHub User	Displays public GitHub user info.	GitHub API

7️⃣	😂 Random Joke	Fetches a safe random joke.	JokeAPI

8️⃣	🤡 Official Joke	Fetches a random joke (fallback).	Official Joke API
Tech Stack

HTML5 — Semantic, responsive structure

CSS3 — Custom dark theme with gradients and grid layout

JavaScript (ES6+) — Async/await, error handling, and API calls

No dependencies — Fully client-side

How to Run Locally:

Clone this repository

git clone https://github.com/your-username/api-grid-dashboard.git
cd api-grid-dashboard


Open the project

Simply open the file index.html in your browser.

No server required!

Explore the mini apps

Each card performs a live API request when you click its button.

Open DevTools → Network tab to inspect each API call.

Educational Concepts Demonstrated:

✅ Using fetch() for API requests
✅ Handling async / await and try...catch for clean error management
✅ Working with JSON responses
✅ Building a responsive CSS Grid layout
✅ Reusable DOM manipulation helpers
✅ Graceful loading and error states

API Keys:

Only the TMDB (Movies) cell requires an API key.
To enable it:

Register for a free TMDB API key at developer.themoviedb.org
.

Replace the placeholder in the script:

const TMDB_KEY = 'YOUR_TMDB_KEY_HERE';


Uncomment the code block inside the Movies section.

File Structure
api-grid-dashboard/
├── index.html        # All-in-one HTML, CSS, JS
└── README.md         # This documentation

Ideas for Expansion:

Add input fields for custom currencies or weather units

Include localStorage to save last API responses

Integrate your own API (e.g., news, quotes, trivia)

Convert to a modular React or Vue app

Screenshot (Optional):

(You can add a screenshot here for GitHub preview)

![API Grid Dashboard Screenshot](screenshot.png)
