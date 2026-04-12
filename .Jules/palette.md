## 2024-05-24 - Add a11y title to third-party widget iframes
**Learning:** Third-party embedded widgets (like the AirNavRadar live flight tracking map) often lack descriptive `title` attributes on their `iframe` tags, which are required for screen reader accessibility to describe the content. This is a common pattern for embedded map/widget components.
**Action:** Always verify if embedded `iframe` tags have a clear, descriptive `title` attribute in the user's primary language (e.g., pt-BR). Add one if missing to improve accessibility for screen readers.
