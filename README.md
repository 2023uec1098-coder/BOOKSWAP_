# BookSwap_

College Book Exchange & Marketplace — interactive frontend prototype.

## Features
- Student Login / Create Account
- Per-user dashboard and browser-local account data
- Public academic-book marketplace
- Search and multi-filter discovery
- Book detail pages
- Save/Favourites
- Create and delete owned listings
- Sent and received exchange requests
- Request lifecycle: Pending → Accepted/Declined → Completed
- Private demo chat between users
- Notifications
- Student profile
- Responsive UI

## Demo accounts
- Sahil Meena — sahil@bookswap.demo / 1234
- Aarav Sharma — student@bookswap.demo / 1234

## Prototype architecture
The current GitHub Pages build is a browser-only prototype:
- UI: HTML5 + CSS3
- Application logic: JavaScript
- Persistence: browser localStorage/sessionStorage
- Hosting: GitHub Pages

Marketplace listings are shared in the browser to represent public listings. Private user data (favourites, activity and other account-scoped information) is stored under a user-specific storage namespace.

## Production next step
A production implementation can replace browser storage with:
- Node.js + Express.js REST APIs
- MongoDB
- Server-side authentication and password hashing
- Real multi-user synchronization
- Image upload/storage
- Real-time messaging and notifications

The prototype intentionally does not claim production-grade authentication or payment processing.
