# Design System & Documentation

## Imported HTML Links
These are the external resources linked in the `index.html` file.

- **`<link rel="preconnect" href="https://fonts.googleapis.com">`**: Preconnects to the Google Fonts server to speed up font loading.
- **`<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>`**: Preconnects to the font file server (cross-origin) to further optimize loading.
- **`<link href="https://fonts.googleapis.com/css2?family=Inter&display=swap" rel="stylesheet">`**: Loads the specific fonts used: 'Inter' and 'Playfair Display'.

## Root Variables (CSS)
These variables are defined in the `:root` selector in `assets/style.css` and are used throughout the site for consistency.

### Colors
- **`--bg-color: #F3F1EB`**: Cream/Beige background. Used for the main body background.
- **`--text-color: #1A1A1A`**: Dark gray/black. Used for primary text.
- **`--accent-color: #D4E7C5`**: Soft Green. Used for buttons and accents.
- **`--accent-dark: #99B080`**: Darker Green. Used for hover states or emphasis.
- **`--white: #FFFFFF`**: Pure White. Used for card backgrounds or contrast.
- **`--border-color: #E5E5E5`**: Light Gray. Used for borders and dividers.

### Fonts
- **`--font-main: 'Inter', sans-serif`**: The primary font family for body text and UI elements.
- **`--font-display: 'Playfair Display', serif`**: The display font family used for headings and titles.

### Spacing & Layout
- **`--container-padding: 1.5rem`**: Standard padding for the main container to ensure content doesn't touch the edges.
- **`--max-width: 1200px`**: The maximum width of the content container to maintain readability on large screens.
