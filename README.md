# FitTrack Pro

A zero-dependency, offline-first Pomodoro and task-tracking web app built with HTML5, CSS3 and Vanilla JavaScript.

## Run the app

1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. Start adding tasks or run a focus session.

No package manager, build step, server, API key, database or account is required. The app uses browser `localStorage`.

## Features

- Overview dashboard with active-task count, completion rate, streak and focus time.
- Create, edit, complete and delete tasks.
- Task categories, priorities, due dates, notes and colour labels.
- Search, category filters and sorting.
- Focus, short-break and long-break Pomodoro modes.
- Configurable timer durations and long-break interval.
- Weekly charts and category breakdown.
- Light and dark themes.
- JSON backup and restore; CSV task export.
- Sample tasks and a clear-demo control.
- Responsive mobile navigation.
- Offline local persistence.

## Customization

Edit the `APP_CONFIG` object at the top of `app.js` to change the app name, tagline, support email, date format, theme colours, demo data and free-tier settings.

## Data and privacy

App records are stored in the current browser profile under `fittrack_pro_v1`. Clearing browser storage can remove them. Export a JSON backup regularly. The included app does not require an account or send task data to a server.

## Monetization notes

The free-tier limit, upgrade modal and advertising hooks are front-end placeholders. No payment gateway, subscription service, ad network, user account system or server-side entitlement check is included.

## Deployment

This is a static web app. Keep `index.html`, `style.css` and `app.js` together when deploying to GitHub Pages or another static host.

## License

No open-source license is granted by default. All rights remain with the copyright holder unless a separate license is added.
