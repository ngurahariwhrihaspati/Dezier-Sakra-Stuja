# Dezier Prototype

A responsive, interactive carousel prototype featuring a full-screen image carousel with a dynamic hamburger menu navigation. Built with vanilla JavaScript, Bootstrap, and custom CSS styling.

## 🎯 Features

- **Full-Screen Carousel** - Beautiful image carousel that fills the entire viewport
- **Interactive Navigation** - Slide through content with carousel controls and arrow buttons
- **Mobile-Friendly** - Touch swipe support for seamless mobile experience
- **Hamburger Menu** - Collapsible navigation menu that appears when needed
- **Responsive Design** - Optimized for all screen sizes and devices
- **Quick Action Buttons** - Positioned icon buttons for additional functionality
- **Persistent Menu State** - Menu position preference saved to local storage

## 📱 User Interface

The interface includes:

- **Carousel Slides** - Full-screen image displays with titles and descriptions
- **Slide Controls** - Arrow buttons to navigate between slides manually
- **Slide Indicators** - Dots showing current position and allowing direct slide selection
- **Hamburger Menu** (☰) - Click to open navigation menu with links to:
  - Home
  - Projects
  - About
  - Contact
- **Corner Buttons** - Quick access buttons positioned at top-left (D) and bottom-left (R)

## 🛠️ Technology Stack

- **HTML5** - Semantic markup structure
- **CSS3** (46.4%) - Custom styling with responsive design
- **JavaScript** (20.2%) - Interactive functionality
- **Bootstrap 3.3.7** - Grid system and UI components
- **jQuery 3.5.1** - DOM manipulation and carousel control

## 📂 Project Structure

```
Dezier-Sakra-Stuja/
├── index.html        # Main HTML file with carousel markup
├── styles.css        # Custom global styles
├── menu.css          # Menu and button styling
├── menu.js           # Menu and carousel interaction logic
├── projectA/         # Project folder A
├── projectB/         # Project folder B
└── README.md         # This file
```

## 🚀 Getting Started

1. **Clone or download** this repository
2. **Open `index.html`** in your web browser
3. **Interact** with the carousel:
   - Click arrows to navigate between slides
   - Click dots to jump to specific slides
   - Use the hamburger menu to access navigation links
   - On mobile, swipe left/right to change slides

## 💻 Customization

### Edit Carousel Content
Modify the slides in `index.html`:
- Change titles and descriptions in `.carousel-caption`
- Update background images by modifying CSS classes (`.bg1`, `.bg2`, `.bg3`)

### Update Navigation Links
Edit the menu items in `index.html` under the `<nav class="overlay-menu">` section

### Customize Styling
- `menu.css` - Menu appearance and animations
- `styles.css` - Global styles and carousel design

### Modify Interactions
Edit `menu.js` to adjust:
- Menu toggle behavior
- Carousel swipe sensitivity
- Button click handlers

## 🌐 Live Demo

View the live prototype: [Dezier Sakra Stuja](https://ngurahariwhrihaspati.github.io/Dezier-Sakra-Stuja/)

## 📝 Notes

- Built as a prototype for the "Sakra Stuja" location in Nyuhkuning, Ubud, Bali
- Uses Bootstrap 3.3.7 for foundational styling
- Includes touch gesture support for modern mobile devices
- Menu position preference is persisted using browser localStorage

## 📄 License

Not specified - Please add a license if you plan to share this publicly.

---

**Author:** ngurahariwhrihaspati  
**Last Updated:** May 2026