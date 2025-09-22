# CSS Basics Project

This project focuses on implementing basic CSS styling and responsive web design principles to enhance HTML webpages.

## Project Structure

```
css_basic/
├── base.css          # Base CSS styles provided for the project
├── styles.css        # Custom CSS styles and layout implementation
├── index.html        # Main HTML page with responsive design
└── tweets.html       # Secondary HTML page with consistent styling
```

## Tasks Completed

### 0. Some early styling
- Created `css_basic` directory
- Copied `index.html` and `tweets.html` from previous project
- Created empty `styles.css` file
- Added base CSS styles to `base.css`
- Linked both CSS files in HTML `<head>` sections

### 1. Positioning with CSS Flexbox
Implemented a flexible layout using CSS Flexbox with the following structure:
```
Header
Main (Article + Aside)
Footer
```

**Key CSS Properties Applied:**
- `display: flex` for both `<body>` and `<main>` containers
- `flex-direction: column` for `<body>` (vertical stacking)
- `flex-direction: row` for `<main>` (horizontal layout)
- `flex: auto` for `<main>` to maintain automatic height/width
- `flex: 2` for `<article>` (takes ⅔ width)
- `flex: 1` for `<aside>` (takes ⅓ width)
- `overflow-y: auto` for both `<article>` and `<aside>` for scrollable content

### 2. Responsive web design
- Added `class="works_on_smartphone"` to `<body>` tag in `index.html`
- Implemented viewport meta tag for proper mobile rendering:
  ```html
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  ```
- Ensured layout degrades gracefully on smaller screens

### 3. Additional styling
- Added custom colors, backgrounds, and borders
- Enhanced styling within the `<article>` tag
- Implemented a logo using Unicode character in the header
- Added `.logo` class styling for proper logo presentation
- Maintained the Flexbox layout structure while adding aesthetic improvements

## Features

- **Responsive Design**: Adapts to different screen sizes
- **Flexbox Layout**: Modern CSS layout technique
- **Mobile-Friendly**: Optimized for smartphone viewing
- **Custom Styling**: Unique visual design while maintaining structure
- **Scrollable Content**: Articles and aside sections support scrolling

## Usage

1. Clone the repository
2. Open `index.html` in a web browser to view the main page
3. Open `tweets.html` to see the consistent styling applied
4. Resize the browser window to see the responsive design in action

## Files

- `base.css`: Contains foundational CSS rules provided for the project
- `styles.css`: Contains custom CSS including Flexbox layout and additional styling
- `index.html`: Main webpage with responsive design implementation
- `tweets.html`: Secondary webpage with consistent styling

## Technologies Used

- HTML5
- CSS3 (Flexbox)
- Responsive Web Design principles

This project demonstrates fundamental CSS concepts including layout positioning, responsive design, and aesthetic styling while maintaining clean, semantic HTML structure.