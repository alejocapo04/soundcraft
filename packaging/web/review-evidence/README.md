# Native optional file-provider evidence

Source: `a17384dcf1183318893023974e219dd7b229e2de`. Workflow: `5ea2aa3711239b503e7c9bc72edca6028f2baee1`.

The local and external entries are synthetic fixtures. These captures validate the native UI separation, not real storage operations.

Rendered with the repository native offscreen renderer and pinned fonts. This is not browser/backend end-to-end evidence. No server, credentials or private files were used.

Run: https://github.com/alejocapo04/soundcraft/actions/runs/41281023900

- `local.png`: provider absent (default).
- `provider.png`: synthetic provider registered; device history remains separate.

The evidence lives on this review-only branch and is excluded from the feature PR. See provenance.json for input and image hashes.
