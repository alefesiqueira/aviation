## 2024-05-20 - Missing Iframe Titles in Embedded Widgets
**Learning:** Embedded widgets via iframes often lack `title` attributes, making them completely opaque to screen readers. This is a common accessibility issue for third-party embeds (like maps or radars) where the content inside the iframe is visually obvious but programmatically hidden.
**Action:** Always check iframes for descriptive `title` attributes, especially when integrating external widgets. Provide a localized, meaningful title to describe the widget's purpose.
