## 2024-03-01 - Add Title to External Widget Iframes
**Learning:** Iframes used for embedding external widgets (like live maps or trackers) must include a descriptive `title` attribute for screen readers. Without it, users relying on assistive technology hear the raw URL or "frame", providing no context about the widget's content. The title should be in the primary language of the application (e.g., pt-BR).
**Action:** Always add a clear, localized `title` attribute describing the content and purpose of any embedded iframe widget to ensure screen reader users understand its context.
