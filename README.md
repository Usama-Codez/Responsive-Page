# Responsive Dashboard

A fully responsive dashboard page built with HTML, Tailwind CSS, and vanilla JavaScript.

## Features

- ✨ Fully responsive design (mobile, tablet, desktop)
- 🌓 Dark/Light mode toggle with localStorage persistence
- 📱 Mobile-friendly sidebar navigation
- 🎨 Active state management for navigation links
- 💨 Smooth transitions and animations
- 🎯 Modern UI with Tailwind CSS

## Technologies Used

- HTML5
- Tailwind CSS v4
- Vanilla JavaScript
- No frameworks required

## Installation

1. Clone the repository
2. Install dependencies:

```bash
npm install
```

3. Build the CSS:

```bash
npm run build:css
```

4. Open `index.html` in your browser or use a local server

## Development

To watch for CSS changes during development:

```bash
npm run watch:css
```

## Deployment

### Deploy to Vercel

1. Install Vercel CLI:

```bash
npm i -g vercel
```

2. Deploy:

```bash
vercel
```

### Deploy to Netlify

1. Install Netlify CLI:

```bash
npm i -g netlify-cli
```

2. Deploy:

```bash
netlify deploy
```

Or simply drag and drop your project folder to [Netlify Drop](https://app.netlify.com/drop).

## Project Structure

```
├── index.html          # Main HTML file
├── src/
│   ├── input.css       # Tailwind source CSS
│   ├── output.css      # Compiled CSS (generated)
│   └── script.js       # JavaScript functionality
├── images/             # Image assets
├── design/             # Design references
└── package.json        # Dependencies
```

## Features Implementation

### Dark Mode

- Toggle between light and dark themes
- Persistent theme selection using localStorage
- Dynamic icon switching based on theme

### Responsive Sidebar

- Fixed sidebar on desktop (lg breakpoint)
- Slide-in sidebar on mobile with overlay
- Active state highlighting for current page

### Navigation

- Smooth transitions
- Hover effects
- Mobile-friendly touch interactions

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

MIT
