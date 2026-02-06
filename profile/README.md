# Sono

Sono is a music platform built around **local music playback**.

The main project is the mobile app.
Everything else exists to support it.

---

## Main Project

### sono-mobile
Flutter mobile app for local music playback.
This is the primary Sono project and the main focus of development.

Stable, beta, and nightly builds are handled via branches.

---

## Other Projects

### sono-web
Vue.js web app for authenticated Sono features.

### sono-site
Public website and landing page.

### sono-api
FastAPI backend used by the mobile and web apps.

### on_audio_query
Forked from the original [on_audio_query](https://pub.dev/packages/on_audio_query) to extend features for sono-mobile.

### sono_refresh
A custom pull-to-refresh indicator with logo animation.

### artist-image-service
Service to scrape and save images from Deezer to display artist images in sono-mobile.

### version-service
Update service for sono-mobile to keep the app up to date.

### kworb-listeners-scraper
Scrapes Spotify data from kworb.net and stores it in PostgreSQL.

---

## Branches and Releases

Most repositories use:

- `main` – stable
- `beta` – testing
- `nightly` – experimental

Beta and nightly mobile builds use a different app icon to avoid confusion.

---

## Status

Sono is under active development.
Things may change.

https://sono.wtf
