# My Arch + Hyprland System Guide

A single-file, no-build static HTML page documenting my Arch Linux + Hyprland desktop: the hardware, the OS/display stack, what dotfiles actually are, how my rice (caelestia-dots + a JaKooLit overlay) is structured, a tool glossary, the live color theme, installed apps, keyboard shortcuts, and a system health snapshot.

## Files

- `my-system-guide.html` — the page itself. Fully self-contained (no build step, no external network requests, no dependencies) — just open it in a browser.

## Language support

The page supports **English, Thai (ภาษาไทย), Lao (ພາສາລາວ), and Japanese (日本語)**. Switch with the language buttons in the top-right of the header. English is the default; your choice is remembered per-browser via `localStorage`.

Tool and project names (Hyprland, Quickshell, pacman, AUR, etc.) are kept in their original form across all four languages, since that's how they're referenced in the actual config files and upstream docs.

## Viewing it

Just open it directly — no server needed:

```bash
xdg-open my-system-guide.html
```

or double-click it in a file manager, or open it via GitHub Pages if you publish this repo.

## Notes

Content reflects a snapshot of the system at the time it was generated (package counts, battery health percentage, disk usage, etc. will drift as the system changes). Re-generate it periodically if you want it to stay current.
