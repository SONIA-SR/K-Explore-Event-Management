# K Explore — Event Management Website
A responsive event discovery and registration website built with HTML5, CSS3 and vanilla JavaScript.

## Features
- Responsive landing page and event cards
- Search by event name, category, venue or description
- Category filters and event detail dialog
- Registration form with name, email and 10-digit phone validation
- Confirmation message and Local Storage registration records
- Dark/light theme toggle and responsive mobile navigation

## Run locally
No build tools or dependencies are required. Open `index.html` in a modern browser. Or run `python3 -m http.server 8000` in this folder and visit `http://localhost:8000`.

## Data note
The six event listings are illustrative sample content. Registrations are saved in the current browser's Local Storage under `kExploreRegistrations`. There is no backend, server-side database, email delivery or payment integration.

## Deploy
Push the folder to GitHub. For GitHub Pages, go to **Settings → Pages**, select the `main` branch and root folder, then save. Netlify and Vercel can also deploy this static project. Add your actual repository and deployed URLs here after publishing.

## Git commands
```bash
git init
git add .
git commit -m "Build K Explore event website"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/k-explore.git
git push -u origin main
```
