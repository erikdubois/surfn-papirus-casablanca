# CLAUDE.md — surfn-papirus-casablanca

## Project overview

Standalone repo for the **Surfn-Papirus-Casablanca** icon theme, split out of the `erikdubois/surfn`
monolith. See [README.md](./README.md).

## Current state

Ships one theme: `usr/share/icons/Surfn-Papirus-Casablanca/`. Packaged as `surfn-papirus-casablanca-icons-git` (recipe in
`~/KIRO-PKG-BUILD-ICONS/surfn-papirus-casablanca/`), `depends=('surfn-icons-git')` — the base Surfn theme.

## Patterns & decisions

- Theme dir PascalCase; repo/package lowercase. `icon-theme.cache` gitignored (rebuilt by
  the pacman hook on install). Bash scripts follow the canonical Kiro template.
