# 12 example houses

Each house has five pages in the book: **Before**, **Level 1**, **Level 2**, **Level 3** and **The recipe**. Each image page shows the front view large and the angled/aerial view small.

Each file below contains:
- **Book text:** the recipe page as the reader sees it.
- **Production:** the prompts to generate the images (not printed in the book; the reader gets the general prompts in *Your home first* and the prompt pack).

## Standard wrappers for production

### Before (generate from scratch, then make the aerial view from it)
```
Realistic photo of [HOUSE DESCRIPTION], seen straight from the front from the
sidewalk, eye level, whole facade in frame. [CONDITION DESCRIPTION].
Soft overcast daylight, no people, no cars, no text, no house numbers,
no logos.
```
Aerial view: upload the front Before and ask:
```
Same house, same condition, same yard and neighbours, seen from a drone about
25 ft (8 m) high at a 45° angle from the front-left. Keep every element
identical. Realistic photo, no people, no text.
```

### Levels (edit the previous image of the same view)
```
Edit this photo. Keep the house exactly the same: same camera angle and framing,
roof shape, windows, doors, porch, steps, railings, trees and neighbouring
buildings. Do not add, remove or move any structural element.

Change only:
[CHANGES]

Keep as is:
[KEEP]

Realistic photo, soft natural daylight, outdoor lights off, no people, no text,
no logos, no house numbers.
```

## Files
| # | File | Style | Palette |
|---|---|---|---|
| 01 | `01-craftsman.md` | Craftsman bungalow | 01 Classic Cream |
| 02 | `02-ranch.md` | Ranch | 03 Dove & Teal |
| 03 | `03-cape-cod.md` | Cape Cod | 09 Navy Colonial |
| 04 | `04-colonial.md` | Colonial | 04 Ivory & Bronze |
| 05 | `05-split-level.md` | Split-level | 19 Warm Taupe |
| 06 | `06-queenslander.md` | Queenslander | 20 Queenslander White & Green |
| 07 | `07-timber-cottage.md` | Timber cottage | 05 Sage Cottage |
| 08 | `08-1970s-brick.md` | 1970s brick | 23 Tan Brick Update |
| 09 | `09-federation.md` | Federation | 22 Federation Heritage |
| 10 | `10-traditional-brick.md` | Traditional brick | 21 Red Brick Classic |
| 11 | `11-rendered.md` | Rendered house | 17 Terracotta Render |
| 12 | `12-simple-modern.md` | Simple modern | 13 Charcoal & Cedar |
