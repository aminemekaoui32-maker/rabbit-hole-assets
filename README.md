# Rabbit Hole — brand assets

Assets for the "Rabbit Hole" Facebook page (English-language facts, mysteries and stories).
Use these in every video so the character and branding stay consistent.

## Folders

| Folder | Files | Use |
|---|---|---|
| `character/` | `rabbit_closed`, `rabbit_half`, `rabbit_open` (.svg + .png, 1080 px square) | Full-frame character shots |
| `character/` | `rabbit_*_circle` (.svg + .png, 800 px, transparent outside the circle) | Talking-host bubble in a corner of the video |
| `profile/` | `profile_1080.png` | Page profile picture |
| `cover/` | `cover_1640x624.png` | Facebook page cover photo (key content kept inside the mobile-safe centre) |
| `logo/` | `logo_dark` (navy background), `logo_transparent` (.svg + .png) | Intros, outros, thumbnails, cover |
| `watermark/` | `watermark.svg`, `watermark.png` (660 px wide, transparent) | Corner watermark on every video |
| `src/` | `original.jpg` | Source artwork (1600 px) |

## Lip-sync (talking character)

The character has three mouth states, all pixel-aligned (same size, same position):

- `closed` — silence, pauses
- `half` — quiet or short sounds
- `open` — loud syllables / vowels

Recommended approach: measure the voice-over loudness every ~80–100 ms and pick
`closed` below a low threshold, `half` in the middle, `open` above a high threshold.
Avoid switching faster than every 2 frames so the mouth doesn't flicker.
Use the `_circle` versions for a host bubble in the bottom corner; use the square
versions for full-screen intros and outros.

## Notes

- Prefer the PNG files when rendering video; the SVGs embed the artwork as an image
  and their text uses the Inter / Inter Display fonts, which must be installed to
  render the wordmark exactly.
- Brand colors: gold ring `#E0A84A`, navy `#0B1A24`, cyan accent `#4FD1E8`, white text.
- Tagline: FACTS · MYSTERIES · STORIES
