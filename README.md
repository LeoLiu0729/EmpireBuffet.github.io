# Empire Buffet Website

This repository contains the marketing website for Empire Buffet in Greensboro, North Carolina. The project is a static site optimized for GitHub Pages and includes dedicated pages for the home experience, menu highlights, and contact information.

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/EmpireBuffet/EmpireBuffet.github.io.git
   cd EmpireBuffet.github.io
   ```
2. Open `index.html` in your preferred browser, or use a simple static server:
   ```bash
   python -m http.server 3000
   ```
3. Visit [http://localhost:3000](http://localhost:3000) to preview the site locally.

## Structure

```
.
├── assets/
│   └── css/
│       └── style.css      # Custom styling for the site
├── index.html             # Landing page with highlights, testimonials, and pricing
├── menu.html              # Detailed buffet categories and catering information
├── contact.html           # Contact details, reservation form, and map
└── Assignment3/           # Legacy assets retained for reference
```

## Deployment

Pushes to the `main` branch automatically update the live site when using GitHub Pages. Ensure that `index.html` remains at the repository root so it is served by default.

## License

Content © Empire Buffet. Images are sourced from Unsplash and remain © their respective photographers.
