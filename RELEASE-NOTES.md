Pagecraft WordPress 0.2.14

Safer imports, forms and private content

- Imported pages now apply consistent safety checks to embedded resources and authored styles while preserving supported HTTPS embeds and forms.
- Invalid public form requests are discarded before storage. Retained spam has its own request limit, retention window and storage cap.
- Connecting Pagecraft Cloud is tied to the WordPress administrator and browser session that started it.
- Delegated Pagecraft access respects WordPress page permissions, protected-page metadata stays private and invalid parent-page choices are rejected.
- A page that only uses a video lightbox now loads the runtime it needs.

Release validation requires hosted WordPress desktop/mobile acceptance for the packaged artifacts; local fixture and CI testing alone do not certify production hosting.
