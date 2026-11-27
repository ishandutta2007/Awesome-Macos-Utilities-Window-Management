# Awesome-Macos-Utilities-Window-Management

## Top macOS Utilities & Window Management Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Window Snapping, Tiling, Launchers & Menu Bar Control*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **macOS Utilities & Window Management**. These tools help users snap, tile, and organize windows, launch apps and commands quickly, manage menu bar clutter, and capture screenshots—turning macOS into a more keyboard-driven and efficient workspace.

**Examples** include Magnet, Rectangle Pro, BetterSnapTool, Mosaic, Raycast, Alfred, Divvy, Moom, CleanShot X, Bartender, and 1architect/macspace-releases (the category leaders and notable projects).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosted window management, transparent launcher alternatives, and open menu bar utilities—ideal for power users, developers, and anyone who wants a customizable, privacy-respecting Mac setup without paid subscriptions.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Magnet](https://magnet.crowdcafe.com/)**  
  App Store classic for drag-to-edge window snapping and keyboard shortcuts for halves, thirds, and quarters; reliable and sandboxed, though development pace has been conservative [citation:15][citation:8].

- **[Rectangle Pro](https://rectangleapp.com/pro)**  
  Paid upgrade to the free Rectangle app, adding custom snap areas, workspace arrangements that restore window layouts when displays connect or disconnect, and a 10-day trial [citation:1][citation:5].

- **[BetterSnapTool](https://apps.apple.com/app/bettersnaptool/id417375580)**  
  Budget-friendly snapping utility with custom invisible trigger zones on screen edges, allowing precise splits like 30/70; interface is dated but the engine is stable [citation:15][citation:8].

- **[Mosaic](https://www.lightpillar.com/mosaic.html)**  
  Window manager from Light Pillar (makers of Keyboard Maestro) offering drag-and-drop snapping, saved custom layouts, multi-display layout application, and Touch Bar support; sold primarily via Setapp [citation:1].

- **[Raycast](https://www.raycast.com/)**  
  Extensible launcher with built-in window management, clipboard history, snippets, and a scriptable command catalog; current versions require macOS Tahoe and Apple Silicon [citation:2][citation:9].

- **[Alfred](https://www.alfredapp.com/)**  
  Veteran launcher with a free core (app launching, calculator, web search) and a paid Powerpack for workflows, text expansion, and custom hotkeys; supports Intel and Apple Silicon [citation:9].

- **[Divvy](https://mizage.com/divvy/)**  
  Grid-based window manager where users draw a window's size on a grid and assign layouts to keyboard shortcuts; trial available [citation:8].

- **[Moom](https://manytricks.com/moom/)**  
  Window layout tool with visual grid resizing via the green button and "Snapshots" that remember and restore multi-monitor arrangements when displays are reconnected [citation:15][citation:8].

- **[CleanShot X](https://cleanshot.com/)**  
  Premium screenshot and screen recording suite with scrolling capture, OCR, GIF export, pinned screenshots, click highlights, and CleanShot Cloud for shareable links with privacy controls [citation:3].

- **[Bartender](https://www.macbartender.com/)**  
  Menu bar manager for hiding, grouping, and reordering menu bar items; Bartender 7 adds mouse-free management, optional screen recording, and a unified command bar for searching items and clipboard history [citation:4].

- **[1architect/macspace-releases](https://github.com/1architect/macspace-releases)**  
  Modular open-source system data and Apple Intelligence cleaner for macOS, not a window manager; included per user reference [citation:16].

## Open-Source GitHub Projects

- **[Rectangle](https://github.com/rxhanson/Rectangle)**  
  The most popular free and open-source window manager for macOS, offering keyboard shortcuts and snap areas for halves, thirds, quarters, and corners; lightweight and reliable with no configuration required [citation:5][citation:15].

- **[Loop](https://github.com/MrKai77/Loop)**  
  Free and open-source window snapper with a radial menu triggered by holding a key and moving the cursor in a direction; also supports keyboard shortcuts for specific actions [citation:5].

- **[Amethyst](https://github.com/ianyh/Amethyst)**  
  Automatic tiling window manager inspired by Linux's xmonad, arranging windows in layouts like tall, wide, fullscreen, and column; cycles layouts as windows open and close [citation:5].

- **[AeroSpace](https://github.com/nikitabobko/AeroSpace)**  
  i3-inspired tiling window manager with tree-based automatic tiling, its own virtual workspaces (ignoring native macOS Spaces), and configuration via a single text file; no SIP changes required [citation:5].

- **[yabai](https://github.com/koekeishiya/yabai)**  
  Highly customizable tiling window manager driven through CLI and config files, paired with skhd for keyboard shortcuts; offers the most control but requires significant setup and partial SIP disabling for some features [citation:5].

- **[OmniWM](https://github.com/OmniNull/OmniWM)**  
  Free, open-source window manager bringing niri-style scrolling and Dwindle layouts to macOS 26 Tahoe; includes a command palette, scratchpads, workspace bar, and menu bar icon hiding [citation:12].

- **[Ice (cavaldos fork)](https://github.com/cavaldos/Ice)**  
  Free and open-source menu bar manager for hiding and organizing icons, with an Always-Hidden section, Ice Bar for notched MacBooks, drag-and-drop layout, hotkeys, and support for macOS 14 through 27 [citation:25].

- **[Floe](https://github.com/wudb/Floe)**  
  Open-source menu bar manager with Visible/Hidden/Always-Hidden groups, searchable icon organization, layout recovery, and import support for Ice and Bartender layouts [citation:20].

- **[BetterShot](https://github.com/KartikLabhshetwar/better-shot)**  
  Free, open-source screenshot and screen recording app for macOS with scrolling capture, OCR, image/video editing, teleprompter, and optional sharing via a self-hosted Cloudflare R2 bucket; positioned as a CleanShot X alternative [citation:14].

- **[Look](https://github.com/kunkka19xx/look)**  
  Open-source, cross-platform launcher positioned as a lightweight Spotlight and Raycast alternative; privacy-focused with local-only storage and no telemetry .

- **[Wrangler](https://github.com/jgaddis99/wrangler)**  
  Free, open-source window manager with configurable grids, batch-tiling for app windows, visual drag-to-snap overlay, and multi-monitor support; designed for developers and power users [citation:18].

### Additional Strong Open-Source Options

- **Nudge** — Lightweight open-source window manager with keyboard shortcuts, drag-to-edge snapping, and 19 layouts; under 1 MB [citation:23].
- **ShiftIt** — Older open-source window organizer for macOS, predecessor to many modern tools [citation:30].
- **Hidden** — Ultra-light menu bar icon hider, a simpler alternative to Ice and Bartender [citation:28].
- **holzBar** — Modern Ice fork with profiles, groups, and settings sync; Swift 6, zero dependencies, never goes online [citation:28].
- **Thaw** — Open-source menu bar manager focused on stability and simplicity [citation:28].
- **asyar** — Privacy-first cross-platform launcher with clipboard secret redaction and extension store, though macOS support may be less mature than Raycast or Alfred .

**Frameworks for building custom systems**: Combine **Rectangle** or **Loop** for basic snapping, **AeroSpace** or **yabai** for automatic tiling if you want a Linux-like workflow, **Ice** or **Floe** for menu bar control, **BetterShot** for capture and sharing, and **Look** as a lightweight launcher. For a fully scriptable setup, pair **yabai + skhd** with **Hammerspoon** for custom automation.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Some open-source projects (e.g., AeroSpace, OmniWM) require specific macOS versions (macOS 13+ or macOS 26 Tahoe) and may be in public beta with breaking changes.
- Window managers and menu bar utilities typically require Accessibility and/or Screen Recording permissions; review what each app requests before granting access.
- Paid SaaS tools often offer trials; pricing and system requirements change frequently—verify on the official site before purchasing.

---

**Made for macOS power users, developers, designers, and anyone building a faster, more keyboard-driven Mac workflow.**  
Let's make macOS utilities and window management more open, customizable, and efficient.
