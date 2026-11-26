Pagecraft WordPress 0.2.10

Header and footer styles after "Update site output"

- Fixes headers losing their layout after "Update site output". Each updated template saved the shared base styles together with its own, and the footer's copy of the base styles then reset parts of the header.
- Templates now keep their own styles in a separate file that loads after every base style, the same way pages do.
- Templates saved the old way show "Update available" on Status. Run "Update site output" once after installing this release to repair them.

Release validation requires hosted WordPress desktop/mobile acceptance for the packaged artifacts; local fixture and CI testing alone do not certify production hosting.
