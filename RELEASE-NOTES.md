Pagecraft WordPress 0.2.12

Page caches after an update

- After Pagecraft Builder, Theme or Importer is updated, Pagecraft now clears page caches once. Before this, a cached site kept serving pages that pointed at the previous release's files until the cache expired or was purged by hand.
- Works with LiteSpeed Cache, Cache Enabler, WP Rocket, W3 Total Cache, WP Super Cache and SiteGround Optimizer. Hosts with their own cache can listen for the `pagecraft_clear_page_caches` action.

Release validation requires hosted WordPress desktop/mobile acceptance for the packaged artifacts; local fixture and CI testing alone do not certify production hosting.
