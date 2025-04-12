# Modern CSS Variables and Components Library

A comprehensive collection of CSS variables and reusable components for modern web development.

## Features

- 🎨 Multiple Theme Options (Light, Dark, Nature, Cyberpunk, Vintage)
- 📱 Responsive Design Variables
- 🎯 Component-Based Architecture
- ✨ Advanced Animations
- 🖼️ Media Handling
- 📝 Form Styles
- 🎭 UI Components
- 🌈 Gradients & Effects

## Usage

1. Import the desired theme file:
```html
<link rel="stylesheet" href="LIGHT-THEME.txt">
```

2. Import core components:
```html
<link rel="stylesheet" href="LAYOUT-COMPONENTS.txt">
<link rel="stylesheet" href="UI-COMPONENTS.txt">
```

3. Use variables in your CSS:
```css
/* Basic Usage */
.my-element {
    color: var(--primary-color);
    background: var(--background-color);
    border: 1px solid var(--border-color);
    border-radius: var(--border-radius);
    box-shadow: var(--box-shadow);
}

/* Using Theme Colors */
.card {
    background: var(--surface-color);
    border: 2px solid var(--primary-dark);
    color: var(--text-color);
}

/* Using Gradients */
.gradient-button {
    background: var(--gradient-primary);
    color: white;
    padding: var(--spacing-md);
    border: none;
    border-radius: var(--border-radius);
}

/* Glass Effect */
.glass-panel {
    background: var(--glass-bg);
    backdrop-filter: var(--glass-blur);
    border: 1px solid var(--glass-border);
    padding: var(--spacing-lg);
}
```

## Directory Structure

```
css-variables/
├── themes/
│   ├── LIGHT-THEME.txt
│   ├── DARK-MODERN.txt
│   ├── NATURE-THEME.txt
│   ├── CYBERPUNK-THEME.txt
│   └── VINTAGE-THEME.txt
├── components/
│   ├── LAYOUT-COMPONENTS.txt
│   ├── UI-COMPONENTS.txt
│   └── FORM-STYLES.txt
├── utils/
│   ├── ANIMATIONS.txt
│   ├── MEDIA-STYLES.txt
│   └── RESPONSIVE.txt
└── README.md
```

## License

MIT License - Feel free to use in personal and commercial projects.
