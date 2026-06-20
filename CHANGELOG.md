# Changelog

## 2026.06.20 — split out of the surfn monolith

### What Changed

Initial standalone repo. The **Surfn-Papirus-Casablanca** theme was carved out of the monolithic
`erikdubois/surfn` repo so it ships as its own package, `surfn-papirus-casablanca-icons-git`, depending on the base
`surfn-icons-git`.

### Technical Details

- `usr/share/icons/Surfn-Papirus-Casablanca/` copied verbatim from the monolith; theme dir kept PascalCase
  so `Inherits=` resolution is unaffected. Repo/package names lowercase per Arch convention.
- `icon-theme.cache` not shipped — the pacman gtk-update-icon-cache hook rebuilds it on install.

### Files Modified

- Initial scaffold + usr/share/icons/Surfn-Papirus-Casablanca/
