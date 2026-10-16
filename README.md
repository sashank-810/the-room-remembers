# The Room Remembers

A quiet, top-down puzzle about rooms that remember what you did in previous attempts.

**Current version:** Room 01 (browser prototype). This repository is structured to publish the game with GitHub Pages, without any build step or Codex usage.

## Play

After GitHub Pages is enabled for this repository, the game will be available at:

`https://sashank-810.github.io/the-room-remembers/`

Desktop: use WASD or arrow keys to move and `R` to rewind. Phone: use the on-screen direction pad and **Rewind**.

## Enable GitHub Pages

1. Open this GitHub repository → **Settings** → **Pages**.
2. Under **Build and deployment**, set **Source** to `Deploy from a branch`.
3. Select branch **main**, folder **/(root)**, and choose **Save**.
4. When Pages completes the deployment, use the published URL in the Play section above.

## Update the game

Replace `index.html` in the root of this repository and commit to `main` (or use a PR and merge it). Pages automatically rebuilds after each commit. There is no compilation step.

## File map

- `index.html`: complete browser game (HTML/CSS/JavaScript)
- `.nojekyll`: instructs GitHub Pages to skip Jekyll processing
- `DEVELOPMENT.md`: engineering roadmap for when Codex is available

## Roadmap

- Three connected rooms, persistent cross-room memory
- Five-room vertical slice with differentiated mechanics
- Later: offline-trained adaptive director, constrained to validated puzzle configurations

**Note:** GitHub Pages on the free tier requires this repository to be public. All committed game code will be publicly readable; avoid including API keys, private files, and unreleased proprietary material.