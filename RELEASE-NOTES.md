Pagecraft WordPress 0.2.3

Updates from the WordPress Updates screen, a rebuilt admin, and form entries in WordPress

Updates
- Pagecraft Importer, Pagecraft Builder and the Pagecraft theme now appear on the WordPress Updates screen when a newer release is published. Each download is checked against the signed release feed (size and SHA-256) before WordPress installs it.
- The first release that carries this must be installed by hand once on each existing site. Later releases arrive through WordPress.

Admin
- Every Pagecraft admin screen is rebuilt in one layout: a dark bar with the screen menu, one header per screen, full-width tables, and row actions in a "⋯" menu.
- Results and warnings appear as notices in the bottom-right corner instead of banners at the top of the page.
- Overview lists what needs attention and the newest unread form entries.
- Site Settings contents line up with the screen header.

Form entries
- Pagecraft forms on a WordPress site now store their entries in WordPress, under Pagecraft > Submissions, with an inbox, spam folder, CSV export and an optional email on each new entry. Entries are not sent to Pagecraft Cloud.

Pagecraft Cloud import
- A site can be replaced by a different project. Colours, text styles and classes still used by pages that stay on the site are kept instead of blocking the replacement.
- Imported pages load their web fonts. If Google Fonts cannot be reached during an import, the result says so and the import can be run again.

Editor
- Pin editor 0.2.17-preview.20261125.148 with the new blocks and icons.
- The media library refreshes when it opens, and fonts used on the canvas load in the editor.
- Page SEO tags are published with the page, and live saves are named correctly.

Release validation requires hosted WordPress desktop/mobile acceptance for the packaged artifacts; local fixture and CI testing alone do not certify production hosting.
