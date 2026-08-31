# Third-party notices

This release candidate adds the following audited-reference v2 dependencies.
They remain governed by their authors' licenses; this file is not a relicensing
claim.

| Package | Version | License | Use |
|---|---:|---|---|
| `canonicalize` | 4.0.0 | Apache-2.0 | RFC 8785 JSON canonicalization |
| `ssri` | 13.0.1 | ISC | SHA-256 integrity generation and verification |
| `jsondiffpatch` | 0.7.6 | MIT | Safe post-mismatch diagnostics only |
| `fast-check` | 4.9.0 | MIT | Reproducible property tests |
| `zod` | 3.25.76 | MIT | Structural validation for v2 packages and requests |

Upstream projects:

- `canonicalize`: <https://github.com/erdtman/canonicalize>
- `ssri`: <https://github.com/npm/ssri>
- `jsondiffpatch`: <https://github.com/benjamine/jsondiffpatch>
- `fast-check`: <https://github.com/dubzzz/fast-check/tree/main/packages/fast-check>
- `zod`: <https://github.com/colinhacks/zod>

The ARFR v2 implementation was imported from experimental final commit
`16226bde0bcdc3753ee5582995fda79f537d0d39`, implementation commit
`619cde67f20c4fba1a9ee29a272cdcec4d593eb1`, and original committed source
`d1ebf6b0b594d0b56eec9372dbaa2d4a3ae3019f`. No GPL/AGPL implementation,
credentials, environment files, hosted-project configuration, private data, or
disposable fixture rows were imported.
