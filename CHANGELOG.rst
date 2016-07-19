Changelog
=========

0.0.12
------

`Compare changes
<https://github.com/kura/eevee/compare/0.0.11...0.0.12>`__

- Updated share colours to be from the Material Design palette.
- Added some automatic colouring of links/icons for AUTHOR_CARD
- Added ability to disable comments and author_card for a specific page or
  article using ``:author_card: False`` and ``:comments: False`` respectively.

0.0.11
------

`Compare changes
<https://github.com/kura/eevee/compare/0.0.10...0.0.11>`__

- Stop using base64 fonts, dumb idea to begin with.
- Tidy up font sizes in headers.

0.0.10
------

`Compare changes
<https://github.com/kura/eevee/compare/0.0.9...0.0.10>`__

- Bug fixes in template styles.

0.0.9
-----

`Compare changes
<https://github.com/kura/eevee/compare/0.0.8...0.0.9>`__

- Huge overhaul of theme... Too much to list, check out the documentation.

0.0.8
-----

`Compare changes
<https://github.com/kura/eevee/compare/0.0.7...0.0.8>`__

- Added better templates for `tags` and `categories`.

0.0.7
-----

`Compare changes
<https://github.com/kura/eevee/compare/0.0.6...0.0.7>`__

- Fixed RSS and Atom having the wrong types.

0.0.6
-----


`Compare changes
<https://github.com/kura/eevee/compare/0.0.5...0.0.6>`__

- Updated archive templates so they aren't terrible.
- archive will automatically links to year and month archives if
  ``YEAR_ARCHIVE_SAVE_AS`` or ``MONTH_ARCHIVE_SAVE_AS`` are set.
- partial_archives template now works as expected instead of showing every
  article.
- Added archive to header and footer menus.

0.0.5
-----

`Compare changes
<https://github.com/kura/eevee/compare/0.0.4...0.0.5>`__

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
