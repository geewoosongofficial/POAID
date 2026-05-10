# POAID

**Personal Operations API Integration Dashboard**

A full-stack API integration dashboard that uses React, FastAPI, SQLite, the GitHub REST API, and Open-Meteo to aggregate developer activity, weather, tasks, notes, settings, and API health into one interface.

## Project Goal

The goal of this project is to build a polished personal dashboard that demonstrates full-stack development, API integration, backend architecture, persistence, error handling, and documentation. This project is designed to be a Solution Architect-style resume project, not just a simple coding app.

## Planned Tech Stack

- **Frontend:** React, HTML, CSS, JavaScript
- **Backend:** Python, FastAPI
- **Database:** SQLite
- **External APIs:** GitHub REST API, Open-Meteo API
- **Deployment:** Vercel or Netlify for frontend, Render or Railway for backend
- **Documentation:** README, architecture docs, diagrams, tradeoff notes

## Planned Features

- GitHub activity dashboard
- Weather data panel
- Tasks and notes section
- Saved settings
- API health/status panel
- Error handling for failed API requests
- Cached API results for reliability
- Architecture and data flow documentation

## Architecture Overview

This project uses a React frontend as the user interface, a FastAPI backend as the integration layer, SQLite for saved settings and local data, and external APIs such as GitHub REST API and Open-Meteo for live data. The backend controls API calls, error handling, data cleanup, caching, and database access before sending clean JSON responses to the frontend.

## Summer Timeline

- **Week 1:** Project setup, repo structure, README, and scope
- **Week 2:** FastAPI backend foundation
- **Week 3:** GitHub API integration
- **Week 4:** Weather API integration
- **Week 5:** Basic frontend and backend connection
- **Week 6-7:** React dashboard
- **Week 8-9:** SQLite, tasks, notes, and settings
- **Week 10-11:** Error handling, API status, and caching
- **Week 12:** Deployment
- **Week 13-14:** Architecture documentation and resume polish

## Current Status

Project setup in progress.
