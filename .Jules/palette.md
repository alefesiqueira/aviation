## 2024-05-18 - Missing Iframe Title Accessibility
**Learning:** Iframes require a `title` attribute to provide context to screen reader users about the embedded content, especially for complex widgets like live flight maps where the visual context is not inherently available to assistive technologies.
**Action:** Always ensure any added or modified `iframe` tags include a descriptive `title` attribute matching the embedded content context (e.g., pt-BR "Mapa de rastreamento de voos ao vivo do AirNavRadar").
