## 2024-07-25 - Modernizing Iframe Attributes
**Learning:** Deprecated HTML attributes like `frameborder` reduce code quality and create maintenance overhead. Using standard CSS (like Tailwind utilities) for borders while retaining document-level attributes (like `marginwidth`) creates a cleaner separation of concerns and prevents visual regressions.
**Action:** Use `class="border-none"` instead of `frameborder="0"` when working with iframes, and ensure an accessible `title` attribute is present.
