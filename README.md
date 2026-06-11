# Simran turns 30 — birthday site

One-page scrapbook: cover → timeline → photo gallery → 6-question quiz → sealed envelope that opens into a letter once the quiz is done. Content is final; no placeholders remain.

## Deploy on GitHub Pages

1. github.com → New repository → name it (e.g. `simran-30`) → **Public** → Create.
2. **Add file → Upload files** → upload `index.html` and the `photos` folder (28 jpgs). Commit.
3. **Settings → Pages → Source: Deploy from a branch → main, / (root)** → Save.
4. Live in 1-2 minutes at `https://<username>.github.io/simran-30/`.

Mobile caveat: GitHub's phone upload flattens folders. If photos land at repo root, edit `index.html` and find-replace `photos/` with nothing. A laptop avoids this.

Privacy: page carries a noindex tag, but the repo is public. Delete the repo after the birthday week if you want it gone.

## Editing later

All content (timeline, captions, quiz, letter, footer) lives in the `CONFIG` block at the top of the `<script>` in `index.html`. Edit, commit, live in ~1 minute.

## Structure notes

- Hero: `photo_31` (black-tie, Christmas trees)
- Timeline thumbnails: 02 (Calcutta), 05 (Krabi), 14 (Genting), 22 (Dubai Hilton), 29 (puja at home)
- Quiz: finishing it (any score) unseals the envelope
- Excluded from the album: one video thumbnail, one duplicate Hilton shot, and #19 per your call
