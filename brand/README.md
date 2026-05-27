# FloraFleet brand assets

The mark is the FloraFleet logo from [florafleet.eu](https://florafleet.eu) —
a plant on a wheeled cart ("a fleet of growing things").

| File | Use |
|------|-----|
| `florafleet-avatar.svg` / `-512.png` | **GitHub org profile picture.** Mark on a dark rounded-square, scaled to ~78% so GitHub's circular crop never clips it. |
| `florafleet-logo.svg` / `-512.png` | Transparent-background mark for docs, slides, light surfaces. |

## Upload the org avatar

GitHub has no API for org avatars — upload by hand:

**Settings → Profile → Profile picture → Upload a photo**
→ https://github.com/organizations/florafleet/settings/profile

Use `florafleet-avatar-512.png`.

## Colors (from the website)

| Token | Hex |
|-------|-----|
| Petal light | `#a78bfa` |
| Petal mid | `#8b5cf6` |
| Bud / wheels | `#c4b5fd` |
| Stem (green) | `#10b981` |
| Avatar bg | `#211d36` → `#15121f` |

## Regenerate PNGs from SVG

```bash
qlmanage -t -s 512 -o . florafleet-avatar.svg   # macOS QuickLook
# or: rsvg-convert -w 512 -h 512 florafleet-avatar.svg -o florafleet-avatar-512.png
```
