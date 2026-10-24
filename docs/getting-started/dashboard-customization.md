# Dashboard customization

The 77 Metrics dashboard is fully customizable. You can choose which metrics each tile shows, how large tiles are, how they are arranged on the grid, and how many pages you have.

Customization uses two separate editing tools:

| Tool | What it does | How to open it |
|------|-------------|----------------|
| **Tile List** | Add/remove tiles, change which metric a tile shows, manage pages, toggle Enhanced Information | Tap **Edit Dashboard** on the idle screen or from the drive controls |
| **Layout Canvas** | Resize tiles, drag them to new positions | Tap **Edit Layout** inside the Tile List |

---

## The Tile List

Tap **Edit Dashboard** to open the Tile List. It shows your current dashboard pages and their tiles.

### Changing what a tile shows

1. In the Tile List, tap the **pencil icon** on any tile row
2. A menu lists all 21 available metrics
3. Tap the metric you want — the tile updates immediately

**Metric already on this page?** If you select a metric that is already used by another tile on the same page, a **swap** option appears. Tapping the metric a second time swaps the two tiles.

> **Note:** Changing metrics is blocked while the vehicle is moving. Wait until stopped to make changes during an active drive.

### Adding a tile

Tap **Add Metric** at the bottom of the Tile List. A new tile appears with a metric selection menu. Choose the metric to assign.

Each page holds between 1 and 12 tiles. A metric can appear only once per page.

### Removing a tile

Tap the **− (minus) button** on any tile row. The tile and its metric are removed from the page. At least one tile must remain on each page — the button is disabled when only one tile remains.

### Enhanced Information

Each page has an **Enhanced Information** toggle near the top of its settings.

When **off** (the default), all tiles show the metric name, its value, and the unit — nothing more.

When **on**, tiles at Size 2 and larger show additional visualizations alongside the main value:

| Metric | What Enhanced Information adds |
|--------|-------------------------------|
| Speed | Speedometer gauge; speed history chart at Size 3+ |
| Average Speed | Pace comparison bar and "On pace" / "±N mph" text |
| Moving Avg | Same pace comparison as Average Speed |
| Max Speed | Progress bar showing current speed vs. max |
| Elapsed Time | Animated clock ring that resets each hour |
| Moving Time | Stopped-time breakdown; movement timeline chart at Size 3+ |
| Vertical Speed | Zero-centered gauge; history chart at Size 3+ |
| Altitude | Elevation range gauge showing min/max observed |
| Grade | Pitch gauge; attitude ball (pitch + roll) at Size 3+ |
| Direction | Live map with vehicle heading arrow; travel path at Size 3+ |
| G-Force | G-force heat map alongside the vector meter |

Enhanced Information is **per-page** — you can enable it on one page and leave it off on another.

### Page title

Each page can have an optional title. Tap the title field at the top of the page settings and type a name. The title appears as the page tab label. Leave it blank to show "Page N" instead.

### Managing pages

**Add a page:** Tap the **+ button** in the page selector row. A new page opens with a set of default tiles at Size 2.

**Delete a page:** Scroll down and tap **Delete Page** (destructive action). At least one page must remain.

**Reorder pages:** Tap **Edit** in the page selector row to enter reorder mode, then drag pages into the order you want.

**Switch pages:** In the Tile List, tap any page button in the page selector row at the top.

### Settings

Tap the **gear icon** in the Tile List toolbar to open Settings. Two global options affect all pages:

- **Units** — Imperial (mph, ft, mi) or Metric (km/h, m, km)
- **Precision** — Whole numbers or one decimal place (default)

---

## The Layout Canvas

From inside the Tile List, tap **Edit Layout** to open the Layout Canvas. This is where you resize tiles and drag them into position.

### The grid

The dashboard grid adapts to the iPhone's orientation:

| Orientation | Grid |
|-------------|------|
| Portrait | 2 columns × 6 rows |
| Landscape | 4 columns × 3 rows |

The Layout Canvas reflects the current orientation. Rotate your iPhone to edit the landscape layout separately.

### Tile sizes

Tiles have seven sizes. Each size spans a different number of grid cells:

| Size | Portrait (col × row) | Landscape (col × row) |
|------|---------------------|----------------------|
| 1 | 1 × 1 | 1 × 1 |
| 2 | 1 × 2 | 2 × 1 |
| 3 | 2 × 2 | 2 × 2 |
| 4 | 2 × 3 | 3 × 2 |
| 5 | 2 × 4 | 4 × 2 |
| 6 | 2 × 5 | 3 × 3 |
| 7 | 2 × 6 | 4 × 3 |

Size 1 fills one cell. Size 7 fills the entire portrait grid.

Each tile on the canvas shows a **shrink button (−)** and an **expand button (+)**. Tap them to step the tile one size smaller or larger. Buttons are dimmed when the tile is already at its minimum or maximum size.

### Reflow on resize

When you expand a tile, other tiles may need to move to make room:

- Tiles that fit elsewhere reflow into available space automatically
- A tile that cannot fit at its current size **shrinks** to the largest size that fits
- A tile that cannot fit at any size is **displaced** — removed from the grid temporarily

Displaced tiles appear in an "Off Grid" list below the canvas. They return automatically when space becomes available — for example, after you shrink another tile.

> **No tiles are deleted during reflow.** A displaced tile keeps its metric and its size preference; it just waits off the grid until space opens.

### Dragging tiles

Hold a tile briefly until it lifts, then drag it to a new position. A highlighted region shows where the tile will land.

**Same-size swap:** If you drop a tile onto a tile of the same dimensions, the two tiles swap positions.

**Larger displaces smaller:** A larger tile can be moved onto cells occupied by smaller tiles. The smaller tiles reflow into available space.

**Smaller cannot displace larger:** If you try to drop a small tile onto a position occupied by a larger tile, it snaps back to its original position.

### Undo and redo

Every resize and move in the Layout Canvas can be undone. Tap the **← (undo)** button in the toolbar to reverse the last change, or **→ (redo)** to re-apply it.

Undo history is per-page. Switching pages clears the undo stack for the previous page.

---

## How changes are saved

All changes — metric assignments, tile sizes, positions, page titles, Enhanced Information settings, and unit preferences — are saved to the device automatically as you make them. There is no separate save step.

Changes are preserved across app restarts and iPhone restarts. Your dashboard layout is not synced through iCloud or any server; it lives entirely on the device.

---

## Default layout

On a fresh install, 77 Metrics starts with one page and six tiles at Size 2:

| Tile | Metric |
|------|--------|
| 1 | Speed |
| 2 | Direction |
| 3 | Altitude |
| 4 | Grade |
| 5 | Moving Time |
| 6 | Elevation Profile |

---

*Back to [Getting Started](index.md) · See also [Features: Dashboard](../features/dashboard.md)*
