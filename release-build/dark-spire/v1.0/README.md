# Dark Spire v1.0 — public release payload

Reassembly: `cat parts/part_{00..08}.bin > DarkSpire_Korean_v1.0_PATCH.zip`

Archive size **5,044,506 bytes**; SHA-256 **b903abbbd28ea2be0a92605d16bb7a02734dae5926c7c31e7b5744ec4c642028**.

Exactly 9 binary parts, in ascending numerical order. GitHub Actions verifies the assembled ZIP, all six member names and the contained BPS SHA-256 before creating release `dark-spire-korean--v1.0`. ROMs and saved states must not appear in the package. This directory intentionally contains only release payload fragments and the validation metadata.

## Current official release

The 9 parts above preserve the **initial** archive exactly for provenance. The currently downloadable v1.0 GitHub Release ZIP has been repackaged to omit contributor-name lines in README_KO.txt and 배포문_KO.txt, with updated SHA256SUMS.txt. Its size is **5,061,189 bytes** and SHA-256 is **`aeeae7ae15b6fbba935bebed09e3118721a554a910444369c4824c3ec3d8273a`**. The BPS, Windows patcher executable, and PATCH.bat payloads are byte-for-byte unchanged. The initial archive fragments are not the current downloadable release ZIP.
