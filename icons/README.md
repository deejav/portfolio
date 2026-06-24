# SVG Icons

Drop your custom SVG files in this folder.

## Recommended format
- Use lowercase kebab-case names, e.g. `hubspot.svg`, `slack.svg`, `woocommerce.svg`.
- Keep icon canvas at `24x24` or `32x32` for consistent sizing.
- Prefer `fill="none"` and `stroke="currentColor"` for easy color control via CSS.

## How to use in `index.html`
```html
<span class="tool-icon" aria-hidden="true">
  <img src="icons/hubspot.svg" alt="" loading="lazy" decoding="async">
</span>
```

If you want, I can switch your current inline tool icons to load from files in this folder.
