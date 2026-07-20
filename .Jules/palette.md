
## 2026-07-20 - Iframe Accessibility and Styling
**Learning:** Third-party iframes often lack a descriptive `title` attribute, which is critical for screen reader users to understand the frame's content before interacting with it. Also, deprecated attributes like `frameborder="0"` should be replaced with modern CSS utility classes like `border-none`.
**Action:** Always add a localized, descriptive `title` attribute to iframes and replace legacy presentational attributes with CSS when embedding third-party widgets.
