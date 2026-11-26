Pagecraft WordPress 0.2.15

Lighter pages after a rebuild

- A page rebuilt in WordPress no longer downloads the same base styles twice. The header and footer shipped their own copy of styles the page's stylesheet already starts with; that copy is now skipped, saving about 30 KB of CSS per page.
- Nothing changes visually. Pages with different base styles, and pages without a Pagecraft stylesheet of their own such as the 404 page, load exactly as before.

Release validation requires hosted WordPress desktop/mobile acceptance for the packaged artifacts; local fixture and CI testing alone do not certify production hosting.
