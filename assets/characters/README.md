# Character asset staging

Approved character identity assets are registered through `assets/manifest.yaml`.

The current deterministic face-lock task preserves each accepted selection card as source material and derives a clean portrait crop without generative alteration. The crop operation may remove dossier text and unused framing only; it must not alter identity, skin, hair, expression or clothing.

Binary source and derived files are added only when their SHA-256 values can be verified against the manifest.
