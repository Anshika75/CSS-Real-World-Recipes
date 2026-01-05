# Gradient Border

Creates colorful gradient borders around elements using CSS pseudo-elements and mask properties.

## Technique

Uses a `::before` pseudo-element with a gradient background and CSS mask to create the border effect. The mask "cuts out" the center, leaving only the border visible.

## Key CSS Properties

- `position: relative` - On parent for absolute positioning context
- `::before` pseudo-element - Creates the gradient layer
- `background: linear-gradient()` - The gradient colors
- `-webkit-mask` and `mask-composite` - Creates the border effect
- `padding: 2px` on mask - Controls border thickness

## Customization

- Change gradient colors in `linear-gradient()`
- Adjust border thickness by changing `padding` value
- Modify `border-radius` for different shapes
- Change gradient direction (135deg, 90deg, etc.)

## Use Cases

- Premium feature cards
- Call-to-action sections
- Pricing tables
- Profile cards
- Highlighted content blocks

## Browser Support

Good - Works in all modern browsers. Older browsers will show a solid border fallback.
