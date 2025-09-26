# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a personal romantic web application called "m-f" (presumably initials) consisting of multiple interconnected HTML pages that create an interactive romantic experience. The project is a static website with multiple themed pages, each with unique visual effects and animations.

## Architecture and Structure

### Core Application Structure
- **Static HTML Pages**: Self-contained HTML files with embedded CSS and JavaScript
- **Main Entry Point**: `index.html` serves as the central hub with navigation to all other pages
- **Multi-page Architecture**: Each page is a complete standalone experience with its own theme and animations

### Page Structure and Themes
1. **index.html** - Main landing page with romantic message, music player, and navigation to all other pages
2. **premios.html** - Awards/prizes page with flip card interactions for reading competition rewards
3. **cumple-mes.html** - Harry Potter themed monthly anniversary page featuring the "Espejo de Oessed" (Mirror of Erised)
4. **examen-grado.html** - Motivational page for graduate exam support with particle effects
5. **practica-laboral.html** - Congratulations page for passing the exam and starting professional practice

### Technical Implementation
- **CSS Framework**: Tailwind CSS via CDN for styling
- **Fonts**: Google Fonts (Dancing Script, Montserrat, Poppins, Cinzel, etc.)
- **Animations**: Custom CSS keyframe animations for particles, floating elements, and visual effects
- **Audio**: HTML5 audio element with local file `fondo.mp3` for background music
- **Interactivity**: Vanilla JavaScript for effects like click animations, card flipping, and particle systems

### Common Design Patterns
- **Particle Systems**: Floating animated elements across all pages for atmospheric effects
- **Gradient Backgrounds**: Dynamic animated gradients using CSS keyframes
- **Glass Morphism**: Backdrop-filter blur effects with semi-transparent elements
- **Custom Animations**: Fade-in-up animations with staggered delays for content reveals
- **Interactive Elements**: Click effects that spawn floating emojis/hearts

## Development Notes

### File Dependencies
- All pages depend on Tailwind CSS CDN
- `index.html` requires `fondo.mp3` audio file in the root directory
- Each page uses Google Fonts with specific font families

### No Build Process
- This is a pure static website with no build tools, package managers, or dependencies to install
- No package.json, no npm commands, no bundling process
- All code is contained within the HTML files themselves

### Deployment
- Can be served directly from any static web server
- All assets are either embedded or loaded from CDN
- The only local asset is the `fondo.mp3` audio file

### Styling Approach
- Extensive use of Tailwind utility classes
- Custom CSS animations and effects defined in `<style>` tags
- Responsive design using Tailwind's responsive prefixes
- Heavy use of CSS gradients and backdrop-filter for visual appeal

### Browser Compatibility
- Uses modern CSS features like backdrop-filter, CSS gradients, and transforms
- Requires modern browser support for HTML5 audio and advanced CSS animations
- JavaScript uses ES6+ features like const/let, arrow functions, and template literals

## Content and Theming

The website appears to be a deeply personal romantic project with content in Spanish, featuring:
- Romantic messages and declarations of love
- Celebration of academic achievements and milestones
- Harry Potter themed content (Mirror of Erised reference)
- Interactive reward system for reading competitions
- Motivational content for academic/professional development

This appears to be a personal gift/tribute website rather than a commercial application.