## 2026-03-31 - Added title to iframe widget
**Learning:** Embedded iframe widgets without a `title` attribute are a common accessibility issue, as screen readers will only announce "frame" without context, leaving visually impaired users unsure of the content.
**Action:** Always verify if embedded content (iframes) has a descriptive `title` attribute that explains its purpose.