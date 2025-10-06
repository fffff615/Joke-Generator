# Joke Generator

Simple browser app that pulls light-hearted jokes from the Official Joke API. Click the button to fetch a new setup and punchline every time—no page reloads required.

## Features

- Fetches random jokes on demand from `official-joke-api.appspot.com`.
- Clean, centered layout with responsive styling.
- Loading and error messaging so the UI stays friendly even if the API hiccups.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) 18+ installed locally.

### Installation

```bash
npm install
```

### Run the preview server

```bash
npm start
```

This launches a local static server (via `npx serve`) on port 3000. Open http://localhost:3000 to use the app.

## Formatting

Run Prettier across the project whenever you make changes:

```bash
npm run format
```

## Project Structure

- `index.html` – Home page with the interactive joke generator.
- `style.css` – Styling shared across the pages.
- `jokes.html` – Placeholder page for future expansion.

## License

This project is distributed under the ISC License. See `package.json` for attribution details.
