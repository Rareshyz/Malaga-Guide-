# Málaga Guide

A simple tourist guide website for **Málaga, Spain**, written in English with plain HTML and CSS. It helps visitors discover the city's best places and plan a trip of 1, 2 or 3 days.

## Pages

| Page | File | What it shows |
|------|------|---------------|
| **Home** | `index.html` | Full-screen hero image with the title *"Discover the beauty of Málaga"* and a short introduction |
| **Explore** | `explore.html` | Places to visit, presented as cards with an image on one side and a description on the other |
| **Trip ideas** | `tripideas.html` | Ready-made itineraries for 1 day, 2 days and 3 days in Málaga |

All pages share a fixed navigation bar (Home, Explore, Trip ideas) and the same stylesheet.

## Features

- Fixed navigation bar with a dropdown for the trip plans
- Full-screen hero section with a background image
- Card layout for the places in the Explore page
- CSS transitions and animations for a more lively interface
- Decorative content generated with the `::before` and `::after` pseudo-elements
- Responsive design: a single `@media` block adapts the layout to phones and tablets, and the navigation items stack vertically on small screens

## Built with

- **HTML5** – page structure and semantic content
- **CSS3** – layout, transitions, animations, pseudo-elements and media queries

No JavaScript and no external libraries are used.

## Project structure

```
Malaga-Guide/
├── index.html        # Home page
├── explore.html      # Places to visit
├── tripideas.html    # 1, 2 and 3-day itineraries
├── css_malaga.css    # Stylesheet shared by all pages
└── Images/           # Photos used on the website
```

## Run it locally

1. Clone the repository:
   ```bash
   git clone https://github.com/Rareshyz/Malaga-Guide-.git
   ```
2. Open the project folder.
3. Double-click `index.html` (or open it in any web browser).

No installation or build step is needed.

## What I learned

This project was built as part of my first year of Computer Science studies. It helped me practice structuring a multi-page website, styling it with CSS, making it responsive, and managing the project with Git and GitHub.

## Author

**Rareshyz** – [GitHub profile](https://github.com/Rareshyz)
