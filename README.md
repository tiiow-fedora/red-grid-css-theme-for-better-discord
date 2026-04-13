# Vesktop QuickCSS — Neon Red Transparent Theme

A minimal QuickCSS theme for Vesktop that adds a transparent Discord layout with a neon red grid background and soft glass-style UI panels.

---

## Overview

This theme modifies Vesktop’s interface to:

- Add a neon red animated grid background
- Make core UI layers transparent
- Apply glass blur effects to panels
- Keep chat fully transparent
- Style headers, sidebars, and modals with dark red accents
- Add subtle hover highlights for messages
- Maintain readability while reducing visual noise

---

## Preview (concept)

- Black base background
- Red grid overlay with pulsing animation
- Frosted glass panels for UI sections
- Transparent chat feed
- Red glow accents on focus and hover

---

## Installation

1. Open Vesktop  
2. Go to Settings  
3. Open QuickCSS  
4. Paste the full CSS below  
5. Save and reload Discord  

---

## Features

### Neon grid background
Creates a layered animated grid using:
- Horizontal and vertical repeating linear gradients
- Radial glow overlays
- Subtle pulsing animation (`grid-pulse`)

### Transparent UI layers
Removes default Discord/Vesktop backgrounds from:
- App container
- Layout layers
- Chat area
- Message containers

### Glassmorphism panels
Applies blur and transparency to:
- Channel header
- Sidebar
- Server list
- Input box
- User panel
- Member list
- Popouts and modals

### Message styling
- Fully transparent messages by default
- Soft red hover highlight

### Input focus effect
- Red glow border on active typing area
- Subtle shadow for depth

---

## Key CSS Sections

### Background system
- `#app-mount`, `.appMount__51fd7`
- Neon grid animation + radial lighting

### Transparency layer removal
Targets major Discord layout wrappers to eliminate solid backgrounds

### Chat cleanup
Makes message list and scrollers fully transparent

### UI panels
Sidebar, header, member list, and bottom panels get frosted glass styling

### Popouts
Dark red glass blur with border and shadow

---

## Notes

- This theme is aggressive with transparency, so readability depends on your wallpaper  
- Performance impact is minimal, but animation may slightly affect low-end systems  
- Discord class names can change, which may break parts of the theme over time  
- Best used with dark wallpapers for contrast  

---

## License

Free to use and modify. No warranty. Expect breakage after Discord updates.
