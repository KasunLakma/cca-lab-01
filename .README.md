# CCA Lab Session 2802

A fundamental lab session to understand the basics of HTML, CSS, and JavaScript. This project demonstrates building a simple interactive webpage with modern web development practices.

## Project Overview

This is an educational web application that showcases core web technologies:

- **HTML5** - Semantic markup with accessibility features
- **CSS3** - Modern CSS using custom properties (variables), Grid, and Flexbox
- **JavaScript** - State-driven UI pattern with localStorage persistence

## Key Features

### Interactive Tabs
Three feature tabs that demonstrate state-driven rendering:
- **Speed** - Fast layout patterns and clean DOM updates
- **Quality** - Semantic HTML and accessible basics
- **Scale** - Patterns that translate to React/Next.js

### Pricing Toggle
- Monthly/Annual billing switch
- Three pricing tiers: Starter (free), Pro, and Team
- Prices update dynamically based on selected billing cycle

### Responsive Navigation
- Mobile-friendly hamburger menu
- Accessible navigation with ARIA attributes

### Live User Counter
- Displays active user count (simulated)
- Updates in real-time

### State Persistence
- User preferences saved to localStorage
- Remembers billing preference and active tab

## How to Use

### Running the Application

1. **Open in Browser**
   - Simply open `index.html` in any modern web browser
   - No build step or server required

2. **Using VS Code Live Server**
   - If using Visual Studio Code, install the "Live Server" extension
   - Right-click `index.html` and select "Open with Live Server"

### Interacting with the App

1. **Feature Tabs**
   - Click on "Speed", "Quality", or "Scale" tabs to view different content
   - Content is rendered dynamically based on selected tab

2. **Pricing**
   - Toggle between "Monthly" and "Annual" billing to see price changes
   - Your preference is saved for future visits

3. **Navigation**
   - Click the hamburger menu (☰) on mobile to reveal navigation links
   - Use the nav links to jump to Features, Pricing, or Sign up sections

4. **Get Started**
   - Click "Get Started" to navigate to the signup section

## Project Structure

```
cca-lab-01/
├── index.html    # Main HTML structure
├── app.js        # JavaScript logic and state management
├── styles.css    # CSS styling with custom properties
└── .README.md    # This file
```

## Technologies Used

| Technology | Purpose |
|------------|---------|
| HTML5 | Semantic structure and accessibility |
| CSS Custom Properties | Theme variables and reusable styles |
| CSS Grid & Flexbox | Modern layout techniques |
| Vanilla JavaScript | State management and DOM manipulation |
| localStorage | Client-side data persistence |

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

> Note: This is an educational project designed for learning fundamental web development concepts.