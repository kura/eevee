Changelog
=========

0.0.6
-----

- Updated archive templates so they aren't terrible.
  - archive will automatically links to year and month archives if
    ``YEAR_ARCHIVE_SAVE_AS`` or ``MONTH_ARCHIVE_SAVE_AS`` are set.
- partial_archives template now works as expected instead of showing every
  article.
- Added archive to header and footer menus.


0.0.5
-----

- Template clean up, mostly making the HTML itself look prettier to edit.
- Added aria labels to elements to improve accessibility.
- Added structures to articles and pages, using `schema.org
  <https://schema.org/>`__ additional markup.

0.0.4
-----

- Accidentally messed up Disqus and variable names where not used, so comments
  didn't actually work properly...
- Load fonts from base64 in the CSS file.

0.0.3
-----

- Add ability to use muut instead of Disqus using ``MUUT_SITENAME`` variable.
- Make the share buttons nicer.
- Added "back to top" links.

0.0.2
-----

- Replace ``vh`` definitions with ``em`` for ribbon.
- Replace truetype fonts with woff2 and woff.

0.0.1
-----

- Eevee released
