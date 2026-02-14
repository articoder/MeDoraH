## 2026-02-14 - [Omeka Snippet Accessibility Patterns]
**Learning:** Landing page snippets designed for Omeka-S injection often lack fundamental accessibility features like <title> tags and "Skip to Content" links because they are treated as partials, yet they are sometimes served as standalone pages.
**Action:** Always check for <title> and "Skip to Content" links in Omeka-S landing page files, and ensure aria-labels for generic links include the visible text (WCAG 2.5.3).
