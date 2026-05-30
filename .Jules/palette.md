## 2024-05-18 - Improve Iframe Accessibility
**Learning:** Iframes embedding external widgets, like maps, often lack descriptive titles, which are crucial for screen reader users to understand the context of the embedded content. Furthermore, deprecated iframe attributes (frameborder, scrolling) should be replaced with modern CSS/Tailwind utility classes.
**Action:** Always ensure that iframes have a descriptive `title` attribute (in the primary language of the application, e.g., pt-BR) and modernize styling attributes using the existing CSS framework (like Tailwind).
