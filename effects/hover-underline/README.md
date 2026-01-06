# Hover Underline

Smooth animated underline effects for links and navigation items using pure CSS.

## Techniques

Multiple animation patterns using `::after` and `::before` pseudo-elements with width transitions.

## Variations

1. **From Left** - Underline grows from left to right
2. **From Center** - Underline expands from center outward
3. **Gradient** - Animated gradient underline
4. **Double Line** - Two lines grow from center

## Key CSS Properties

- `position: relative` - On link for positioning context
- `::after` / `::before` - Creates the underline elements
- `width: 0` to `width: 100%` - The animation
- `transition` - Smooth animation timing

## Customization

- Change underline color via `background`
- Adjust animation speed with `transition` duration
- Modify thickness by changing `height`
- Change starting position with `left` / `right`

## Use Cases

- Navigation menus
- Footer links
- Article text links
- Call-to-action links
- Breadcrumbs

## Accessibility

- Maintains link functionality
- Works with keyboard navigation
- Provides clear hover feedback

## Browser Support

Excellent - Works in all modern browsers
