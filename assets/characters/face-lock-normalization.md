# Face-lock normalization worklog

Prepared on 7 August 2026 from the three source selections already accepted by the human.

## Deterministic crop coordinates

The crop removes only the dossier panel and unused frame area. No generative edit, inpainting, face restoration, retouching or identity change is allowed.

- Eleni source: `692f2de7ed5bafcc85e9a7cd7c8df1bca7322334301ec6ee7faa8d875c3b7894`
  - source dimensions: 1402×1122
  - crop box: `(420, 0) → (1318, 1122)`
  - derived dimensions: 898×1122
- Myrto source: `242d88641fbae057b006302c14d43be336bc7e040d67878546151dfe0ff33281`
  - source dimensions: 1536×1024
  - crop box: `(485, 0) → (1304, 1024)`
  - derived dimensions: 819×1024
- Thanasis source: `badafaf8660ce43326e3aab6cbe6f4b93cbec598484c2a2a57c4c3473cc11794`
  - source dimensions: 1536×1024
  - crop box: `(520, 0) → (1339, 1024)`
  - derived dimensions: 819×1024

## Binary status

The normalized PNGs have been prepared locally and visually checked. Binary repository upload is still pending; do not mark the parent task complete until both source cards and derived PNGs are present in the repository and their SHA-256 values are recorded in `assets/manifest.yaml`.
