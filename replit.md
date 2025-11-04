# REST Countries App

## Overview
Application that fetches country data from the REST Countries API (https://restcountries.com) and displays information about countries based on their capital city.

## Features
- Search for countries by capital city name
- Display results in a formatted table showing:
  - Country Name
  - Capital
  - Population
  - Region
  - Subregion

## Technical Stack
- **Frontend**: HTML, CSS, JavaScript (vanilla)
- **Backend**: Node.js with Express
- **API**: REST Countries API v3.1
- **Port**: 5000

## Project Structure
```
.
├── server.js          # Express server
├── public/
│   ├── index.html     # Main HTML interface
│   ├── style.css      # Styling
│   └── app.js         # Client-side JavaScript for API calls
├── package.json       # Node.js dependencies
└── .gitignore        # Git ignore file
```

## Recent Changes
- 2025-11-04: Initial project setup
  - Created Express server on port 5000
  - Implemented country search by capital functionality
  - Added responsive UI with gradient design
  - Configured for Replit deployment

## User Preferences
- Language: Polish (UI text)
- Simple, clean interface with modern gradient design
- Mobile-responsive layout

## API Usage
The app uses the REST Countries API endpoint:
- `GET https://restcountries.com/v3.1/capital/{capital}`
- No authentication required
- Returns JSON data with country information

## Running the Application
- Development: `npm start`
- Server runs on `0.0.0.0:5000`
- Access via Replit's web preview
