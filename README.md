# FinkaMetals signature test (Jose Daniel only)

Sandbox repo, separate from the team's `email-signatures` repo. Nothing here touches the team.

Two variants of Jose Daniel's signature to compare on real devices:

- `jose-daniel-previous/` embedded data-URL SVG (worked in Apple Mail, blank in Gmail)
- `jose-daniel-new/` hosted PNG in `src` + hosted SVG in `srcset`

Live page: https://finkametals.github.io/email-signatures-test/

Assets in `/assets` are referenced by absolute URL, so this must stay deployed at that path for the *new* variant to render. The *previous* variant is self-contained and has no hosted dependency.
