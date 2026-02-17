# Comes To Life - Landing Page

A stunning standalone landing page showcasing the "Comes To Life" Ancient Egypt interactive experience. This project features a beautiful Egyptian-themed design with custom animations, effects, and a premium aesthetic.

## Features

- 🎨 **Egyptian Design System** - Custom color palette with gold, lapis lazuli, turquoise, and papyrus tones
- ✨ **Animated Effects** - Dust particles and hieroglyph background animations
- 🎭 **Premium UI Components** - Custom Egyptian-styled buttons and cards
- 📱 **Responsive Design** - Fully responsive layout for all devices
- 🌟 **Smooth Animations** - Framer Motion powered scroll animations
- 🎯 **SEO Optimized** - Complete meta tags and semantic HTML

## Tech Stack

- **React 18** - Modern React with hooks
- **TypeScript** - Type-safe development
- **Vite** - Lightning-fast build tool
- **Tailwind CSS** - Utility-first CSS framework
- **Framer Motion** - Animation library
- **Lucide React** - Beautiful icon library

## Getting Started

### Installation

```bash
npm install
```

### Development

Start the development server:

```bash
npm run dev
```

The site will be available at `http://localhost:5173`

### Build

Create a production build:

```bash
npm run build
```

### Preview

Preview the production build:

```bash
npm run preview
```

## Project Structure

```
landing-page/
├── src/
│   ├── assets/          # Images and static assets
│   ├── components/
│   │   ├── ui/          # UI components (EgyptianButton, EgyptianCard)
│   │   └── effects/     # Visual effects (DustParticles, HieroglyphBackground)
│   ├── lib/             # Utility functions
│   ├── App.tsx          # Main landing page component
│   ├── main.tsx         # Application entry point
│   └── index.css        # Global styles and design system
├── index.html           # HTML template
├── tailwind.config.ts   # Tailwind configuration
└── package.json         # Dependencies and scripts
```

## Design System

### Colors

- **Gold** - Primary color for headings and accents
- **Lapis Lazuli** - Deep blue for backgrounds
- **Turquoise** - Accent color for highlights
- **Papyrus** - Light beige for contrast
- **Sandstone** - Warm earth tones

### Typography

- **Display Font**: Cinzel - Used for headings and titles
- **Body Font**: Cormorant Garamond - Used for body text

### Animations

- Glow pulse effect on hieroglyphs
- Floating dust particles
- Scroll-triggered fade-in animations
- Hover effects on interactive elements

## Customization

You can customize the design by modifying:

- **Colors**: Edit CSS variables in `src/index.css`
- **Fonts**: Update font imports in `src/index.css`
- **Content**: Modify text and images in `src/App.tsx`
- **Animations**: Adjust Framer Motion settings in components

## License

This project is part of the "Comes To Life" digital heritage experience.
