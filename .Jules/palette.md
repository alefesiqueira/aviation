## 2024-05-18 - Iframe Accessibility and Styling
**Learning:** Iframes embedding external widgets must include a clear, descriptive `title` attribute in pt-BR for screen reader accessibility. Deprecated attributes (like `frameborder="0"`, `scrolling="no"`, `marginheight="0"`, `marginwidth="0"`) negatively impact modern standards.
**Action:** Always add a descriptive `title` attribute in the appropriate language (pt-BR) to iframes and replace deprecated layout attributes with modern utility classes (like `border-none`, `overflow-hidden`) using existing styling systems like Tailwind CSS.
