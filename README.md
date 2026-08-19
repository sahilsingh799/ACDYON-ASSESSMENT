# Portronics Conch Theta C

A responsive product landing page for the Portronics Conch Theta C wired Type-C earphones. The page presents the product's audio features, latency benefits, and comparison with budget wireless TWS earphones in a polished single-page interface.

## Features

- Product hero section with call-to-action links to the live Amazon price
- Animated audio output visualizer with changing bar heights
- Product specification highlights for the drivers, microphone, and Type-C connection
- Wired earphone versus wireless TWS comparison table
- Persistent day/night theme switch using browser local storage
- Responsive layout for desktop, tablet, and mobile screens
- Inline vector artwork and glassmorphism-inspired visual surfaces

## Technology Stack

### Frontend

- **HTML5** for the page structure and semantic content
- **CSS3** for layout, responsive breakpoints, custom properties, gradients, blur effects, transitions, and styling
- **Vanilla JavaScript (ES6+)** for theme switching and the animated audio visualizer
- **Web Storage API (`localStorage`)** for remembering the selected theme
- **Inline SVG** embedded as a CSS background for the earphone illustration

### Typography

- **Plus Jakarta Sans** for the primary interface typography
- **JetBrains Mono** for technical labels and specification values
- Fonts are loaded from **Google Fonts**

### Development Setup

- No framework or JavaScript package manager is required
- No backend or external API is used
- The project is contained in a single `index.html` file

## Getting Started

1. Clone the repository:

	```bash
	git clone https://github.com/sahilsingh799/ACDYON-ASSESSMENT.git
	cd ACDYON-ASSESSMENT
	```

2. Open `index.html` directly in a browser.

For a local development server, use any static file server, for example:

```bash
npx serve .
```

## Project Structure

```text
ACDYON-ASSESSMENT/
├── index.html   # Complete product landing page
└── README.md    # Project documentation
```

## Browser Requirements

Use a modern browser with support for CSS custom properties, CSS backdrop filters, ES6 JavaScript, and the Web Storage API.