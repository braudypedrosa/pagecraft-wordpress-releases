Pagecraft WordPress 0.2.13

Pages rebuilt in WordPress keep what the import gave them

- Images keep their smaller sizes. Saving a page or template, or running "Update site output", used to drop the link between an image and its media library item, so every screen downloaded the full-size file.
- Breadcrumbs keep their "Home" crumb. WordPress rebuilds one page at a time and could not see the home page; it now uses the trail that came with the import.
- A site that was just imported is no longer listed as "Update available" on Status. Pages are flagged once their output changes without a rebuild.

Pages rebuilt before this release get their image sizes back the next time they are rebuilt or saved.

Release validation requires hosted WordPress desktop/mobile acceptance for the packaged artifacts; local fixture and CI testing alone do not certify production hosting.
