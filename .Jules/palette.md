## 2024-04-10 - Iframe Accessibility
**Learning:** Iframes embedding external widgets must include a clear, descriptive `title` attribute in pt-BR for screen reader accessibility. Without it, screen readers only announce "frame" or the iframe's source URL, which provides no context to users navigating via keyboard or assistive technologies.
**Action:** Always add a descriptive `title` attribute to `<iframe>` elements summarizing their content or purpose (e.g., `title="Mapa de rastreamento de voos ao vivo do AirNavRadar"`).
