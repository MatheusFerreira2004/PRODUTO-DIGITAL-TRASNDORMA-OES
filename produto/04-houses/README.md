# 12 example houses

Each house has five pages in the book: **Before**, **Level 1**, **Level 2**, **Level 3** and **The recipe**. The Before and Level 3 pages show the front view large and the aerial view small. Level 1 and Level 2 show the front view only.

Each file below contains:
- **Book text:** the recipe page as the reader sees it, including the Level 1 shopping list and weekend plan.
- **Production:** the prompts to generate the images (not printed in the book; the reader gets the general prompts in *Your home first* and the prompt pack).

## Images per house: 6
| State | Front | Aerial |
|---|---|---|
| Before | ✅ | ✅ |
| Level 1 | ✅ | — |
| Level 2 | ✅ | — |
| Level 3 | ✅ | ✅ |

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

### Levels 1-3, front view (edit the previous front image)
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

### Level 3, aerial view
Upload two images: the **aerial Before** (for angle and surroundings) and the **front Level 3** (for the finished house).
```
Show the finished house from image 2 from exactly the same drone angle, framing,
yard shape, trees and neighbours as image 1. Keep the house structure from
image 1. Apply only the finishes, colours, roof and garden from image 2.
Realistic photo, no people, no text.
```

## Files
| # | File | Style | Palette | Level 1 time |
|---|---|---|---|---|
| 01 | `01-craftsman.md` | Craftsman bungalow | 01 Classic Cream | 2 weekends |
| 02 | `02-ranch.md` | Ranch | 03 Dove & Teal | 1 weekend |
| 03 | `03-cape-cod.md` | Cape Cod | 09 Navy Colonial | 1 weekend |
| 04 | `04-colonial.md` | Colonial | 04 Ivory & Bronze | 1 weekend |
| 05 | `05-split-level.md` | Split-level | 19 Warm Taupe | 1 weekend |
| 06 | `06-queenslander.md` | Queenslander | 20 Queenslander White & Green | 2 weekends |
| 07 | `07-timber-cottage.md` | Timber cottage | 05 Sage Cottage | 1 weekend |
| 08 | `08-1970s-brick.md` | 1970s brick | 23 Tan Brick Update | 1 weekend |
| 09 | `09-federation.md` | Federation | 22 Federation Heritage | 1 weekend |
| 10 | `10-traditional-brick.md` | Traditional brick | 21 Red Brick Classic | 1 weekend |
| 11 | `11-rendered.md` | Rendered house | 17 Terracotta Render | 1 weekend |
| 12 | `12-simple-modern.md` | Simple modern | 13 Charcoal & Cedar | 1 weekend |
