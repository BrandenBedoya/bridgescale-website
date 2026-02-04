# BridgeScale Advisors Website

Corporate capital solutions website built with Tailwind CSS.

## Optimizations Applied

### 1. **Custom Theme Configuration**
- Extracted all hardcoded colors to custom CSS variables in `@theme`
- Brand colors centralized: `brand-navy`, `brand-gold`, `brand-orange`, etc.
- Custom shadows: `shadow-gold-glow`

### 2. **Component Classes**
Created reusable component classes in [input.css](input.css):
- `.btn-primary` - Primary call-to-action button
- `.btn-secondary` - Secondary gold button
- `.btn-outline` - Outlined button style
- `.feature-card` - Feature card with hover effects
- `.icon-box` - Icon container with hover transitions
- `.icon` - SVG icon styling
- `.feature-badge` - Badge component with icon

### 3. **HTML Optimization**
- Replaced repetitive utility classes with semantic component classes
- Reduced HTML file sizes and improved maintainability
- Consistent styling across both English and Spanish versions

### 4. **Build Process**
Added npm scripts for development and production:
```bash
npm run dev         # Watch mode for development
npm run build       # Minified production build
npm run build:prod  # Production build with NODE_ENV
```

### 5. **Performance Benefits**
- Minified CSS output (70KB)
- Reduced class repetition in HTML
- Faster style changes via centralized theme
- Better browser caching with component classes

## Development

Start the development server with watch mode:
```bash
npm run dev
```

Build for production:
```bash
npm run build
```

## File Structure
```
├── index.html          # English homepage
├── espanol.html        # Spanish homepage
├── input.css           # Source CSS with custom components
├── output.css          # Generated Tailwind CSS
├── tailwind.config.js  # Tailwind configuration
└── package.json        # Build scripts
```

Landing page for business financing startup "BridgeScale Advisors"
