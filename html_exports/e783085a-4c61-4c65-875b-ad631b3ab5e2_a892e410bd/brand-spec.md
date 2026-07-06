# iPhone 16 Pro Launch Deck Visual System

Source: Apple press release PDF supplied by the user.

## Tokens

```css
:root {
  --bg: oklch(8% 0.012 260);
  --surface: oklch(14% 0.012 260);
  --fg: oklch(96% 0.004 255);
  --muted: oklch(72% 0.014 255);
  --border: oklch(29% 0.012 255);
  --accent: oklch(70% 0.13 235);

  --font-display: -apple-system, BlinkMacSystemFont, "SF Pro Display", "Helvetica Neue", Arial, sans-serif;
  --font-body: -apple-system, BlinkMacSystemFont, "SF Pro Text", "Helvetica Neue", Arial, sans-serif;
  --font-mono: "SF Mono", ui-monospace, Menlo, Consolas, monospace;
}
```

## Layout Posture

- Use a dark product-stage canvas with white/titanium typography and very thin borders.
- Keep radii large only on device silhouettes; most panels use crisp 8-12px radii.
- Use the accent sparingly for Apple Intelligence, Camera Control, and focus states.
- Build product imagery as editable CSS/SVG silhouettes, rings, chips, and timeline marks.
- Prefer large hero objects and short editorial captions over dense paragraphs.
