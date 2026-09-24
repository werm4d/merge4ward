[README.md](https://github.com/user-attachments/files/32622464/README.md)
# M4D Website — Project Image Manifest

Web images are optimized WebP (quality 82, native size). Keep each under ~250 KB.
Original PNGs can stay in this folder as masters but are no longer referenced by index.html.

| Web file                        | Source (previous file in this folder) | Used by                          |
|---------------------------------|---------------------------------------|----------------------------------|
| claymont-exterior.webp          | 2026-05-22-26-Exterior-Front2.png     | Featured — Claymont (main image) |
| claymont-interior.webp          | 2026-05-21-26-Interior-Main.png       | Featured — Claymont (thumb 1)    |
| claymont-roof.webp              | 2026-05-22-26-Roof-Main.png           | Featured — Claymont (thumb 2)    |
| soulfully-conscious-cafe.webp   | 38 E 23rd Street boards.png           | Card — Soulfully Conscious Cafe  |
| lamott-daycare.webp             | LAMOTT-DAYCARE.png                    | Card — LaMott Daycare            |

Bench inventory for future rotation (OneDrive ARCHIVE): Screenshot_Bennett-FRNT.png, CHESTER.png / CHESTER-II.png, N-MARKET.png.

## Adding or replacing an image
Export to WebP at the image's display size (1600 px wide max). With ImageMagick:

    magick input.png -resize "1600x>" -quality 82 output.webp

Use lowercase, hyphenated filenames (no spaces). Always set width/height and descriptive alt text in index.html.

## Rotating the feature
In index.html the featured block is marked "FEATURED PROJECT — to rotate the feature".
Swap its content with any work-card; the feature block adds a specs grid, location line and role line — fill those when promoting a card.
Every card carries a role line: "M4D: … · Architect: Aubyn Architecture".
