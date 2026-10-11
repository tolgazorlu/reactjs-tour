# React Tour

A React app that fetches a list of tour packages and lets you browse, expand details, and remove tours you're not interested in.

## About
A front-end practice project consuming a public tours API to render cards with "read more" and "not interested" interactions. Built July 2021.

## Features
- Fetch tours from a public API on load
- Loading state while data is fetched
- Expand/collapse tour description ("read more" / "show less")
- Remove a tour from the list ("not interested")
- Empty-state message with a refresh button

## Tech stack
- React 17
- Create React App

## Project structure
```
src/
  App.js      fetches tours and renders the list/loading/empty states
  Tours.js    maps tours to Tour cards
  Tour.js     single tour card with read-more/remove
  Loading.js  loading indicator
```

## Getting started
```bash
npm install
npm start
```
Data is fetched from `https://course-api.com/react-tours-project`, no API key required.

## Status
Learning project, not maintained.

## License
MIT
