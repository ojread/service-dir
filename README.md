# Service directory

Aims:

- Separate dynamic content and fixed pages.
- Content behaves like database tables/records and can be referenced.
- Content doesn't necessarily get rendered to its own page.
- Index pages can loop through content for dynamic views.
- Pages can be generated based on content, for instance each blog category or month needs an archive page.
- Nested folders, site sections, index pages, child pages.


## Nested folders

This isn't supported by the CMS so we need a creative solution. We can have a relation field to specify a parent record.

Is a single site section collection good enough or are more specific ones more useful. This is like a taxonomy and one won't fit all content types.