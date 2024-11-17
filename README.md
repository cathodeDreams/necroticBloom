# Necrotic Bloom

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Version](https://img.shields.io/badge/version-1.0.0-green.svg)
![WCAG](https://img.shields.io/badge/WCAG-AA%2FAAA-success)

> A Versatile Color System for Modern Interfaces

This color system emerged from exploring the intersection of organic and synthetic aesthetics. It provides a flexible foundation for creating interfaces that feel both familiar and slightly alien - equally at home in professional applications or more experimental designs.

## Core Palette

### Foundation Colors

| Color Name    | Hex Code | Description |
|--------------|----------|-------------|
| Fungal Black | `#1A1B1C` | Deep neutral black with organic undertones |
| Bio Lavender | `#E6D7F3` | Soft purple with ethereal qualities |
| Viral Mint   | `#C4E3D4` | Muted green with clinical undertones |
| Tissue Pink  | `#FFE5EC` | Delicate organic pink |
| Spore Gray   | `#9BA0A3` | Neutral gray with subtle warmth |
| Neon Moss    | `#4B9900` | Vibrant organic accent |

### Dark Mode Variants

| Color Name    | Hex Code | Description |
|--------------|----------|-------------|
| Deep Void    | `#0D0E0E` | Darker background variant |
| Dark Lavender| `#9B87AB` | Muted purple for dark contexts |
| Shadow Mint  | `#7A9B89` | Desaturated green for dark contexts |
| Dark Spore   | `#4D5052` | Deep gray for dark contexts |

### Light Mode Variants

| Color Name    | Hex Code | Description |
|--------------|----------|-------------|
| Light Void   | `#E5E7E8` | Light background variant |
| Light Lavender| `#F5EBFD` | Higher contrast purple |
| Light Mint   | `#E8F5EE` | Higher contrast green |
| Light Spore  | `#E5E7E8` | Light gray variant |

## Usage

### Theme Construction

```css
/* Light Theme Example */
:root {
    --bg-color: var(--light-void);
    --text-color: var(--fungal-black);
    --link-color: var(--dark-spore);
    --accent-color: var(--spore-gray);
    --border-color: var(--dark-spore);
}

/* Dark Theme Example */
[data-theme="dark"] {
    --bg-color: var(--dark-void);
    --text-color: var(--dark-lavender);
    --link-color: var(--shadow-mint);
    --accent-color: var(--dark-spore);
    --border-color: var(--dark-spore);
}
```

### Accessibility Guidelines

- All color combinations meet WCAG AA standards for text
- Dark mode colors are calibrated for reduced eye strain
- Light mode ensures sufficient contrast while maintaining theme
- Accent colors reserved for interactive elements and highlights

### Recommended Applications

- Web Applications
- Documentation Sites
- Developer Tools
- Content Management Systems
- Portfolio Sites
- Technical Blogs

## Alternative Variations

The palette can be adapted for different contexts while maintaining its core characteristics:

### Clinical Variant
- Emphasize the mint and lavender tones
- Increase use of white space
- Reduce border opacity

### Technical Variant
- Lean into the darker tones
- Use more pronounced borders
- Emphasize monospace typography

### Organic Variant
- Emphasize pink and moss tones
- Use softer borders
- Incorporate more gradient transitions

## Implementation Notes

- Use opacity variations for hierarchy
- Consider reduced motion preferences
- Maintain consistent contrast ratios
- Test in various lighting conditions
- Ensure color is not the sole indicator of state

## Browser Support

- Modern browsers (Chrome, Firefox, Safari, Edge)
- Graceful fallback for older browsers
- CSS Custom Properties (variables) required

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

## License

This color system is MIT licensed. Feel free to use it in personal or commercial projects.