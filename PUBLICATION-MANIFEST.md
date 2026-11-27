# Publication preview manifest

Preview: `research-preview-0.1`

Prepared: 2026-11-27

Status: **Release manifest for corrected public pre-release `research-v0.1`**

## Payload identities

| Path | Bytes | SHA-256 |
| --- | ---: | --- |
| `assets/github-preview.css` | 2012 | `830def46bb646ebed332813dedb8ac94496abe19cd00678ba3c85105aedc22f0` |
| `CITATION.md` | 634 | `518b06100a17440e0bd167a8b3114b345285e231ecb64082a2cd7b2fa0c26cee` |
| `evidence-and-claims.html` | 5159 | `e73bb12c9416ff271fbdd0061e3b14cb5927fe880df28213e52e00d04abd6ee9` |
| `EVIDENCE-AND-CLAIMS.md` | 4218 | `8dbe7c6d46343171c9ac4362261fa6c11156c5ce856558c86bc74206c85a1974` |
| `figures/connected-evidence.svg` | 2207 | `7d8c5447157319632599b5ff380565a1abf3dbdd91875f078bc53f9ab9bb8339` |
| `figures/evidence-lifecycle.svg` | 3341 | `bfd63e0e227fc95e2ac657929d25fb7e26d3d9c6bc7d22a9d6cbe494aa28a583` |
| `index.html` | 5430 | `3af5087de33a74df699485522ce87858d33a2229aa0ce2e5be79c383eb09626f` |
| `paper/what-haip-is.html` | 22163 | `6dd8e0980285f480bb20cc6d501789ed69a37942883ef3f563ab8d661ab0646c` |
| `paper/what-haip-is.md` | 19676 | `072dafd552883e172e8a404a2eda80027d696990f6f5dfbe97ebe15e526e33e4` |
| `PRE-RELEASE.md` | 1942 | `b9a2d8b97131017fa308a1d52cacf1618364d787beb193efc8d87937dad477fb` |
| `README.md` | 4416 | `e4fee4878967312881f7b4c4b7c1ae6522362b4a6e73b0a809f66dff3167b638` |
| `rights.html` | 1822 | `54fbef4cac2c97d5e9e57b650fdc2c4e020c12b62ea966929b91e6984e49a168` |
| `RIGHTS.md` | 1381 | `9ab69aae00ed1e8b0b34ddb09eee9b26d7fd2a53a25d1c84623b319ec510a955` |

The hashes above identify the exact corrected outbound file set. The annotated
tag and GitHub release record identify its public commit. The HTML files are
generated local previews of the Markdown content.

## Validation receipt

- Targeted sensitive-content scan: **PASS** across all 14 candidate files; no
  targeted private path, unapproved personal identifier, credential, key,
  token, or private-LAN-address pattern matched. The approved public author and
  GitHub account identities are intentionally present.
- Relative Markdown and HTML links: **PASS**, all local targets resolved.
- SVG XML parsing: **PASS** for both figures.
- Mermaid and prior stray-text scan: **PASS**; no Mermaid block or previously
  reported semicolon-prefixed diagram artifact appears in the candidate.
- Public source check: **PASS** for all five cited sources on November 26, 2026.
  The Agent libOS identifier resolved through public search after a direct-open
  retrieval failure.
- Isolated browser render attempt 1: **FAIL** on the first case,
  `index-desktop`. Chrome exited with code `-2147483645` before producing a
  screenshot. The five dependent cases were **NOT_RUN**.
- Isolated browser render attempt 2, explicitly owner-authorized: **FAIL** on
  the first case, `index-desktop`. Edge exited with code `0` but did not create
  the requested screenshot at the bound output path. The five dependent cases
  were again **NOT_RUN**. No third browser attempt was used.
- Authorship and rights notice: **SELECTED** as Anthony Mackulin, all rights
  reserved, with no public reuse or patent license.
- Destination and visibility: **SELECTED** as public `MackuliN/Research` after
  the owner received the public-disclosure warning.
- Private staging and exact payload review: **PASS**; superseded candidates are
  omitted from the corrected public history.
- First full-size native GitHub figure inspection: **FAIL** for
  `figures/evidence-lifecycle.svg`; the `Witnessed` and `Failed` nodes
  overlapped. The finding was preserved and the node geometry was corrected.
- Corrected native GitHub rendering: **PASS** for the repository README,
  manuscript, and both SVG figures. The outcome nodes are separated, the
  status list renders correctly, and the earlier stray diagram text is absent.
- Final privacy and security scan: **PASS** across the 14-file candidate. No
  credential, secret, private path or URI, private network or device identifier,
  hostname, personal contact detail, raw log, proprietary source, active HTML
  content, hidden Unicode control, or remotely loaded asset was found. The
  approved author name and GitHub account are the only personal identifiers.
- External-link review: **PASS** for the five cited public sources; the links
  use ordinary source URLs without tracking query parameters.
- Public-history metadata boundary: the corrected public repository is limited
  to one clean-root publication commit, with no personal email in the intended
  public identity.
- Exact corrected-payload replacement authorization: **GRANTED** for the public
  repository, annotated tag `research-v0.1`, and GitHub pre-release record on
  November 27, 2026.

## Outbound boundary

This manifest identifies the exact corrected payload approved for publication
as `research-v0.1`. It does not authorize later mutation or another release.
`PUBLICATION-MANIFEST.md` is deliberately not included in its own payload
identity table because a file cannot contain a stable hash of itself.
