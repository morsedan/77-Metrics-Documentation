# Dashboard

The dashboard is the main screen of 77 Metrics. It shows your live metrics as tiles arranged on a grid.

## Pages

The dashboard supports multiple pages. Swipe left or right to move between them. Each page has its own independent set of tiles, layout, and settings. Pages are useful for organizing different metric sets — for example, one page for speed metrics and another for elevation metrics.

## Tiles

Each tile displays one metric. Tiles occupy cells on a grid:

- **Portrait:** 2 columns × 6 rows
- **Landscape:** 4 columns × 3 rows

Tiles come in seven sizes. Larger sizes span more grid cells, giving the metric more visual space. See [Dashboard Customization](../getting-started/dashboard-customization.md) for the full size table.

## Live metrics

All tiles update in real time as GPS data arrives (approximately once per second). Metrics that are not yet calculable display a dash (—).

## Enhanced information mode

Each page has an optional Enhanced Information toggle. When enabled, tiles at Size 2 and larger show visualizations alongside the live value. Examples:

- Speed shows a speedometer gauge; Size 3+ adds a speed history chart
- Elapsed Time shows an animated clock ring that resets each hour
- Grade shows a pitch gauge; Size 3+ adds an attitude ball
- Heading shows a rotating compass rose with cardinal direction labels
- Direction shows a live map with a vehicle heading arrow; Size 3+ adds the travel path
- Altitude shows a vertical range gauge marking min and max elevation observed
- Vertical Speed shows a zero-centered climb/descent gauge; Size 3+ adds a history chart
- G-Force shows a cumulative 2D heat map of G-force history alongside the radial vector meter

Enhanced information is a per-page setting — you can enable it on some pages and leave it off on others. See [Dashboard customization](../getting-started/dashboard-customization.md#enhanced-information) for the full per-metric table.

## Customization

See [Dashboard Customization](../getting-started/dashboard-customization.md) for instructions on adding metrics, resizing tiles, rearranging the layout, and managing pages.
