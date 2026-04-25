# Project Guidelines

## Code Style
- Use vanilla HTML5, CSS3, and JavaScript without frameworks
- Follow modern CSS practices: CSS variables for theming, clamp() for responsive units
- Use IIFE pattern for JavaScript modules
- Maintain Spanish language for UI text and comments

## Architecture
- Single-file HTML application with embedded JSON data
- Client-side search functionality with debounced input and Unicode normalization for accents
- Responsive design optimized for mobile devices

## Build and Test
- No build process required; edit HTML directly and test in browser
- No automated tests; manual testing by opening the file in a web browser

## Conventions
- Brand colors: primary #8B1538, dark #6B0F2A
- Data format: 2D array [[name, date], ...] embedded in script tag
- Search requires minimum 3 characters, debounced at 300ms
- Virtual pagination: load 100 items initially, "Load More" for additional results