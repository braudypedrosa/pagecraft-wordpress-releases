Pagecraft WordPress 0.2.17

Faster editor opening

- The editor is now kept by the browser between opens. It used to be downloaded in full every time; after the first open it loads from the browser's own copy, and a new release replaces it automatically.

Undoing a replacement

- The "Last replacement" line and "Undo replacement" now show whether or not Pagecraft Cloud is connected.
- After a redo, the line shows when the site was first replaced.
- Only the five most recent recovery records are kept.

Smaller fixes

- The entries export opens in Excel with accented names intact.
- Notices from other plugins appear above the Pagecraft screen instead of inside its header.
- Theme Builder says when templates are in the Trash and links to where they can be restored.
- Translation templates are included for the Builder, Importer and Theme.

Release validation requires hosted WordPress desktop/mobile acceptance for the packaged artifacts; local fixture and CI testing alone do not certify production hosting.
