Changelog
=========

0.0.11
------

- Stop using base64 fonts, dumb idea to begin with.
- Tidy up font sizes in headers.

0.0.10
------

- Bug fixes in template styles.

0.0.9
-----

- Huge overhaul of theme... Too much to list, check out the documentation.

0.0.8
-----

- Added better templates for `tags` and `categories`.

0.0.7
-----

- Fixed RSS and Atom having the wrong types.

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
