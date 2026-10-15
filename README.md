# Roam travel app scaffold

Roam is a responsive, multi-page front-end scaffold based on [spec.md](spec.md). Each module is a separate HTML page with shared styles and behavior.

## Open the app

Open `src/index.html` in a modern browser. The app does not require a build step or package installation. Google Maps, photos, and web fonts require an internet connection.

## Pages

- `src/index.html` - destination discovery and community highlights
- `src/trips.html` - planned and completed trips
- `src/planner.html` - create a trip
- `src/map.html` - Google Maps view and directions
- `src/community.html` - travel tips, suggestions, and comments
- `src/journal.html` - completed-trip photo uploads
- `src/profile.html` - traveler profile and public memories
- `src/notifications.html` - invitations and activity updates

## Deploy to Vercel

Import the repository into Vercel with the repository root as the project root. The included `vercel.json` publishes `src/` as the static output directory. No framework preset, build command, or install command is required; use the `Other` preset if Vercel asks you to choose one.

## Demo behavior

Trip creation, comments, helpful-suggestion marks, and journal uploads are stored in browser local storage. There is no authentication, server, shared database, moderation service, or production photo storage yet. The map uses a Google Maps embed and a directions URL; production place search and itinerary data should be connected to the backend and any required Google Maps Platform APIs and key restrictions.