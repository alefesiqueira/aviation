## 2026-04-10 - Iframe Accessibility
**Learning:** Iframes embedding external widgets lack inherent context for screen readers, meaning users navigating via assistive technologies do not know what the embedded content is without a clear, descriptive `title` attribute in the app's primary language (pt-BR).
**Action:** Always include a descriptive `title` attribute in the primary language (pt-BR) on all `iframe` elements to ensure screen reader users have proper context before interacting with the embedded content.
