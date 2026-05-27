# FloraFleet brand assets

| File | Use |
|------|-----|
| `florafleet-avatar.svg` / `-512.png` | **GitHub org profile picture.** Filled mint rounded-square background, mark kept inside the circular safe zone so GitHub's round mask doesn't clip it. |
| `florafleet-logo.svg` / `-512.png` | Transparent-background mark for docs, slides, light/dark surfaces. |

## Upload the org avatar

GitHub has no API for org avatars — upload by hand:

**Settings → Profile → Profile picture → Upload a photo**
→ https://github.com/organizations/florafleet/settings/profile

Use `florafleet-avatar-512.png`.

## Colors

| Token | Hex |
|-------|-----|
| Leaf light | `#43a047` |
| Leaf dark | `#1b5e20` |
| Stem | `#2e7d32` |
| Bud | `#66bb6a` |
| Avatar bg | `#e8f5e9` → `#c8e6c9` |

## Regenerate PNGs from SVG

```bash
qlmanage -t -s 512 -o . florafleet-avatar.svg   # macOS QuickLook
# or: rsvg-convert -w 512 -h 512 florafleet-avatar.svg -o florafleet-avatar-512.png
```
