# Iara Forstreuter - Portfolio Website

A modern, interactive portfolio website for multidisciplinary designer Iara Forstreuter, based in Berlin.

## Features

- **Interactive Hero Section**: Animated network with drifting blue dots that respond to cursor movement
- **Responsive Design**: Fully optimized for desktop, tablet, and mobile devices
- **Smooth Animations**: Gradient animations in the portfolio section and continuous dot drift
- **Dark Theme**: Sophisticated dark background with white text and colorful network elements
- **Clean UI**: Minimalist design with grey borders and rounded corners

## Technologies Used

- HTML5
- CSS3 (with animations and responsive design)
- Vanilla JavaScript (no dependencies)
- SVG for interactive network visualization

## Structure

```
iara-portfolio.html  - Single-file portfolio website
```

## Features Breakdown

### Hero Section
- Dark background (#1a1a1a)
- Animated network of 80+ dots in blue, teal, and purple
- 35 light blue background dots that drift randomly
- 250+ connection lines between dots
- Interactive: dots repel from cursor within 150px radius
- Centered text with white heading and light grey description

### Portfolio Section
- Animated gradient background with shifting pastels
- 6 project cards with:
  - Rounded corners (12px)
  - Blackish grey borders (#2a2a2a)
  - Category tags with matching borders
  - Hover effects

### Navigation
- Sticky header with black top border
- Responsive design (nav links hide on mobile)

## Mobile Responsive

- Single-column layout on tablets and mobile
- Responsive typography using `clamp()`
- Touch-friendly spacing
- All interactive elements work on mobile

## Installation

Simply download the `iara-portfolio.html` file and open it in a web browser. No dependencies or build process required.

## Colors

- **Hero Background**: #1a1a1a (very dark grey/black)
- **Text**: #fff (white), #ccc (light grey)
- **Borders**: #2a2a2a (blackish grey), #000 (navigation)
- **Network**: Blues (#13c2c2, #4db8ac, #00bcd4), Purples (#9254de, #ba68c8, #ce93d8), Reds (#ff6b6b, #ff5252, #ff7f7f)

## Customization

All styles are contained within the HTML file's `<style>` tag. Easy to customize:
- Colors: Search and replace color hex values
- Fonts: Uses 'DM Serif Display' and 'Inter' from Google Fonts
- Text: Update content in the HTML body
- Network density: Modify the `nodes` array in the script section

## License

© 2024 Iara Forstreuter. All rights reserved.
