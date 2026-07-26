# TripAdvisor Clone

A simple front-end replica of the TripAdvisor website built with HTML and CSS. This project demonstrates layout, navigation, card-based listings, and responsive design without JavaScript.

## Features

- **Header** — Logo, centered search bar, and quick links (Hotels, Flights, Restaurants)
- **Navigation menu** — Horizontal menu with hover and active states
- **Search section** — Destination search with price range and rating filters
- **Main content** — Three sections using a card grid layout:
  - Featured Destinations
  - Popular Hotels
  - Top-Rated Restaurants
- **Card layout** — Each listing includes an image, title, star rating, and description
- **Footer** — Multi-column links for About, Explore, and Support
- **Responsive design** — Adapts for desktop, tablet, and mobile screens

## Project Structure

```
Trip Advisor clone/
├── index.html    # Main HTML structure
├── style.css     # All styling and media queries
└── README.md     # Project documentation
```

## Getting Started

1. Clone or download this repository.
2. Open `index.html` in any modern web browser (Chrome, Firefox, Edge, Safari).
3. No build step or dependencies required.

> **Note:** Card images are loaded from Unsplash. An internet connection is needed for images to display.

## Technologies Used

- HTML5
- CSS3 (Flexbox, CSS Grid, Media Queries)

## Responsive Breakpoints

| Screen Size | Layout |
|-------------|--------|
| Desktop (> 900px) | 3-column card grid |
| Tablet (≤ 900px) | 2-column card grid |
| Mobile (≤ 600px) | Single-column layout, stacked search inputs |

## License

This project is for educational purposes only. TripAdvisor is a registered trademark of TripAdvisor, Inc.
