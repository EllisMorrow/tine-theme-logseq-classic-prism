# Adaptation notes

See ../NOTICE.md for the pinned upstream palette, license and changes. Both modes supply all 21 Tine Theme API 0.2 color roles. Upstream aliases are resolved to literal colors. Tine page-mark and inline-code keys differ from the proposed names in the discussion, so they are mapped to supported keys.

The dark selection background is #0a3d4b rather than upstream #338fff: the theme API does not expose a separate selection foreground. The light selection remains #e4f2ff. Typography, layout, opacity-derived text and interaction rules remain controlled by Tine.

The package is an editable JSON source artifact, distributed under AGPL-3.0-only with full license and notices. User-supplied screenshots are documentation of Tine's actual rendering, not a pixel-perfect reproduction claim.

See the [local check summary](local-check.md) for the exact tested combinations and manifest digest.
