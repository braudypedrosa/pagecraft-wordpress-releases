Pagecraft WordPress 0.2.9

Faster editor opening

- The editor no longer waits for a check of where every image is used before it appears. That check reads every page, template and revision on the site, so it grew slower as a site was used. It now runs when the media library opens, which is the only place it is needed.
- Until it finishes, no image can be deleted from the editor. WordPress still checks on the server before any delete.

Pages list

- Pagecraft pages show "— Pagecraft" after their title in WordPress Pages, the way WordPress marks the front page.
- "Add New with Pagecraft" sits beside "Add Page".

Release validation requires hosted WordPress desktop/mobile acceptance for the packaged artifacts; local fixture and CI testing alone do not certify production hosting.
