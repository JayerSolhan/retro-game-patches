# Dark Spire v1.0 — public release payload

Reassembly: `cat parts/part_{00..08}.bin > DarkSpire_Korean_v1.0_PATCH.zip`

Archive size **5,044,506 bytes**; SHA-256 **b903abbbd28ea2be0a92605d16bb7a02734dae5926c7c31e7b5744ec4c642028**.

Exactly 9 binary parts, in ascending numerical order. GitHub Actions verifies the assembled ZIP, all six member names and the contained BPS SHA-256 before creating release `dark-spire-korean--v1.0`. ROMs and saved states must not appear in the package. This directory intentionally contains only release payload fragments and the validation metadata.

## Current official release

The nine parts above preserve the **initial** archive exactly as historical evidence and are not the current downloadable ZIP. The live v1.0 GitHub Release excludes `배포문_KO.txt` (a separate forum-post draft), removes attribution lines, and updates the README file list and `SHA256SUMS.txt`. It includes exactly 5 files: `DarkSpire_Korean_Patcher.exe`, `DarkSpire_USA_to_Korean_v1.0.bps`, `PATCH.bat`, `README_KO.txt`, `SHA256SUMS.txt`.

Live ZIP size **5,060,086 bytes**; SHA-256 **`e7d03338fcfdc3697bf87cd5f368eb8752dff14355349b8e1e6404c665b1e91c`**. The BPS, Windows EXE, and BAT are byte-for-byte unchanged. The publishing workflow verifies the final ZIP hash and GitHub Release asset digest.
