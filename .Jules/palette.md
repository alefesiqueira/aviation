## 2024-06-25 - Iframe Title Attributes
**Learning:** Iframes embedding external widgets must include a clear, descriptive `title` attribute for screen reader accessibility, as missing titles cause screen readers to read the source URL or skip the element entirely. Deprecated attributes like `frameborder` and `scrolling` should be replaced with equivalent modern CSS (e.g. `border-none`, `overflow-hidden`).
**Action:** Always verify iframes include descriptive `title` attributes and use CSS instead of deprecated HTML attributes.
