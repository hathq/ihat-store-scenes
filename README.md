# Declarative store Scenes

Package: `@hathq/ihat-store-scenes`, immutable development version **0.10.0**.

`storeScene(store, query)` produces the existing PP SceneProjection, bounded page metadata and exact install actions. The shared trusted renderer owns DOM, forms, accessibility, CSP and lifecycle. Packages cannot supply executable UI, HTML or CSS.

Scene source revisions describe a disposable catalog read model, not a semantic/control commit or a canonical source-retention lease. The current source catalog is reacquired and exact source/package digests are checked by Hatter before install. Empty input still requires an explicit Submit; rendering never installs.

No semantic, control, installation, credential or renderer authority is transferred
to iHat. Acceptance and remaining work are recorded in
`docs/architecture/ihat-online-architecture.json` at the Wonderland root.
