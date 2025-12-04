# Product Designer Portfolio - Responsive Hero Section

A stunning, fully responsive hero section for a product designer portfolio built with HTML, Tailwind CSS v4, and vanilla JavaScript. Features an impressive glassmorphism mobile menu and smooth animations throughout.

## ✨ Features

- 🎨 **Modern Glassmorphism Design** - Beautiful glass effect on mobile sidebar with backdrop blur
- 🌓 **Dark/Light Mode Toggle** - Dual theme toggles (desktop & mobile) with localStorage persistence
- 📱 **Impressive Mobile Menu** - Slide-in sidebar with gradient overlays and staggered animations
- 🎯 **Active Navigation States** - Visual indicators showing current page
- 💫 **Premium Animations** - Smooth transitions, hover effects, and interactive elements
- 🔄 **Download Button** - Animated CV download button with shimmer and arrow slide effects
- 📐 **Fully Responsive** - Optimized for all screen sizes (320px to 1728px+)
- ⚡ **Performance Optimized** - Lightweight and fast-loading

## 🛠️ Technologies Used

- HTML5 - Semantic markup
- Tailwind CSS v4 - Utility-first styling
- Vanilla JavaScript - No frameworks, pure JS
- Font Awesome - Icon library
- Google Fonts - Poppins, Montserrat, Anton

## 🚀 Installation

1. Clone the repository:

```bash
git clone https://github.com/Usama-Codez/Responsive-Page.git
cd Responsive-Page
```

2. Navigate to the src directory:

```bash
cd src
```

3. Install dependencies:

```bash
npm install
```

4. Build the CSS:

```bash
npx tailwindcss -i ./input.css -o ./output.css
```

5. Open `index.html` in your browser or use a local server

## 💻 Development

To watch for CSS changes during development:

```bash
cd src
npx tailwindcss -i ./input.css -o ./output.css --watch
```

## 📁 Project Structure

```
Responsive-Page/
├── src/
│   ├── index.html           # Main HTML file
│   ├── input.css            # Tailwind source CSS with custom styles
│   ├── output.css           # Compiled CSS (auto-generated)
│   ├── script.js            # JavaScript for interactivity
│   ├── tailwind.config.js   # Tailwind configuration
│   ├── package.json         # Dependencies
│   ├── assets/
│   │   └── images/          # Logo, icons, hero image, social icons
│   └── design/              # Design references
├── vercel.json              # Vercel deployment config
├── .gitignore
└── README.md
```

## 🎨 Key Features Breakdown

### Mobile Navigation Menu

- **Glassmorphism effect** with 60-70% transparency
- **Backdrop blur** for depth and modern aesthetic
- **Gradient overlays** with subtle radial effects
- **Staggered animations** - Links fade in sequentially (0.1s delays)
- **Gradient indicators** - Pink-to-yellow lines expand on hover/active
- **Text gradient effects** - Active links show gradient coloring
- **Smooth transitions** - 700ms ease-in-out for sidebar, 300-500ms for elements
- **Rotation animations** - Close button rotates 180° on hover

### Dark/Light Theme

- Dual theme toggles (desktop header & mobile sidebar)
- Sun/moon icon transitions
- Synchronized theme switching
- localStorage persistence across sessions
- Smooth color transitions for all elements

### Download CV Button

- **Shimmer effect** - Light sweeps across button on hover
- **Arrow animation** - Icon slides right on hover
- **Scale transform** - Button grows slightly (1.02x)
- **Gap animation** - Spacing increases between text and icon
- **Enhanced glow** - Shadow expands from 8px to 16px

### Responsive Design Breakpoints

- Mobile: 320px - 767px
- Tablet: 768px - 1023px
- Desktop: 1024px - 1279px
- Large Desktop: 1280px - 1535px
- XL Desktop: 1536px - 1727px
- XXL Desktop: 1728px+

## 🎭 Animations & Interactions

- **Social Icons**: Translate up 8px on hover
- **Nav Links**: Underline expands from left to right
- **Mobile Menu**: Slides in from right with 700ms duration
- **Toggle Button**: Rotates and scales on menu open
- **Active States**: Gradient colors and visible indicators
- **Download Button**: Multi-layered animation (shimmer + scale + gap + glow)

## 🌐 Deployment

### Deploy to Vercel

```bash
npm i -g vercel
vercel
```

### Deploy to Netlify

```bash
npm i -g netlify-cli
netlify deploy
```

Or drag and drop to [Netlify Drop](https://app.netlify.com/drop).

## 🌍 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📝 Customization

### Fonts

The project uses three Google Fonts:

- **Anton** - Hero headings (PRODUCT DESIGNER)
- **Poppins** - Brand name
- **Montserrat** - Navigation and body text

### Colors

- Primary Dark: `#292929`
- Primary Purple: `#925ff0`
- Gradient: `#fa709a` to `#fee140`
- Backgrounds: White/Black with transparency

### Update Theme Colors

Edit `src/input.css` and modify the color values in custom classes.

### Modify Breakpoints

Edit `src/tailwind.config.js` to adjust responsive breakpoints.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

## 👨‍💻 Author

**Usama Akram**

- GitHub: [@Usama-Codez](https://github.com/Usama-Codez)
- Website: [usamaakram.netlify.app](https://usamaakram.netlify.app)

## 📄 License

MIT
