# Town & Country Cafe Website

## Overview

A Flask-based website for Town & Country Cafe located in Madrid, Iowa. This is a single-page application showcasing the cafe's information, menu, and contact details with a warm, coffee shop aesthetic. The project uses a simple Flask backend serving a responsive frontend built with Bootstrap and custom CSS styling.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Single-page application** with smooth scrolling navigation between sections (Home, About, Menu, Contact)
- **Bootstrap 5.3.2 framework** for responsive grid system and components
- **Custom CSS styling** with coffee shop color scheme using CSS variables for consistent theming
- **Google Fonts integration** (Playfair Display for headings, Open Sans for body text) for typography
- **Font Awesome icons** for visual elements
- **Vanilla JavaScript** for interactive features like smooth scrolling, navbar effects, and active section highlighting

### Backend Architecture
- **Flask web framework** with minimal configuration
- **Environment-based configuration** for session secrets with fallback to development defaults
- **Single route structure** serving the main page at root URL
- **Template rendering** using Flask's Jinja2 templating engine
- **Static file serving** for CSS, JavaScript, and image assets

### Development Setup
- **Dual entry points** (app.py and main.py) for flexibility in deployment and development
- **Debug mode enabled** for development with host binding to 0.0.0.0 for container compatibility
- **Port 5000 configuration** as standard Flask development server

### UI/UX Design Patterns
- **Fixed navigation bar** with scroll effects and mobile-responsive hamburger menu
- **Color scheme** based on coffee/earth tones (browns, creams, warm whites)
- **Section-based layout** with smooth transitions between content areas
- **Mobile-first responsive design** using Bootstrap's grid system

## External Dependencies

### CSS Frameworks & Libraries
- **Bootstrap 5.3.2** - UI components and responsive grid system
- **Font Awesome 6.4.0** - Icon library for visual elements
- **Google Fonts** - Typography (Playfair Display, Open Sans)

### Python Packages
- **Flask** - Web framework for backend server
- **Standard Python libraries** - os module for environment variable handling

### Browser APIs
- **Vanilla JavaScript** - No external JS frameworks, uses native browser APIs for DOM manipulation and smooth scrolling
- **CSS3 features** - Custom properties (variables), gradients, backdrop filters