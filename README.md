# AI Model Pixel Characters

Pixel portraits and four-direction character sprites for Sam, Dario, Liangzi, Doubao, and Nicole.

**For non-commercial study and learning only. Commercial use is not permitted.**

## Preview

| Sam | Dario | Liangzi | Doubao | Nicole |
| --- | --- | --- | --- | --- |
| ![Sam](characters/sam/sam-portrait.png) | ![Dario](characters/dario/dario-portrait.png) | ![Liangzi](characters/liangzi/liangzi-portrait.png) | ![Doubao](characters/doubao/doubao-portrait.png) | ![Nicole](characters/nicole/nicole-portrait.png) |

## Contents

20 transparent PNG files: one portrait, one standing sheet, one walking sheet, and one running sheet for each character.

```text
characters/
  sam/
  dario/
  liangzi/
  doubao/
  nicole/
    nicole-portrait.png
    nicole-stand.png
    nicole-walk-sheet.png
    nicole-run-sheet.png
```

Every character folder follows the same naming convention. Files use lowercase English names and hyphens. Editable project files are not included.

## Image Specifications

| Asset | Canvas | Layout |
| --- | --- | --- |
| Portrait | Sam: 66 x 66; others: 1254 x 1254 | One transparent bust portrait |
| Standing | 160 x 40 | Four 40 x 40 views in one row |
| Walking | 240 x 160 | Four direction rows, six frames per row |
| Running | 240 x 160 | Four direction rows, six frames per row |

Direction order is **front, left, back, right**: left to right for standing sheets, top to bottom for walking and running sheets.

Use nearest-neighbor filtering when enlarging pixel art. Suggested playback is 110 ms per frame for walking and 100 ms per frame for running. Portraits retain their approved dimensions and were not resampled to a common size.

PNG sprite sheets were checked against the local editable files and existing animation frames, with no visible-pixel differences. File dimensions and SHA-256 hashes are recorded in `manifest.json` and `SHA256SUMS`.

## License and Credits

Original contributions by Nicole (nicoletangnan). Portraits were created through an AI-assisted workflow and approved by Nicole.

The assets are offered solely for non-commercial study and learning under [LICENSE.md](LICENSE.md). This is a restricted educational-use collection, not a permissively licensed open-source asset pack.

Standing, walking, and running sprites contain modified **RPG Developer Bakin 2D Cast Figure Sets** material. Original base-material copyright: **(c) 2022-2026 SmileBoom Co. Ltd.** These assets retain the original usage and distribution restrictions; the study-only license does not replace them. See [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

## Publication Status

This complete package is prepared for a private repository. Public redistribution of the Bakin-derived sprite sheets remains pending the required permission. The portrait subset may be published separately under the selected study-only terms.
