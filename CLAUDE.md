# CLAUDE.md — neo-candy-orange

## Project overview

Standalone repo for the **neo-candy-orange** folder-icon theme — the same folder set as
`erikdubois/surfn-orange` re-based onto the neo-candy-icons fallback.

## Current state

Ships one theme: `usr/share/icons/neo-candy-orange/` — folders only. Packaged as `neo-candy-orange-icons-git`
(recipe in `~/KIRO-PKG-BUILD-ICONS/neo-candy-orange/`), `depends=('neo-candy-icons-git')`.

## Patterns & decisions

- Folders only; everything else inherits neo-candy-icons. `icon-theme.cache` gitignored.
  Payload reused verbatim from the Surfn counterpart; only Name/Inherits/dir name differ.
