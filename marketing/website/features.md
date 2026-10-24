# Website features page copy

Draft copy for the 77 Metrics website features page.

> **Note:** Draft only. Do not publish until the app is live on the App Store and a production URL is configured.

---

## Page headline

**Draft:** Everything 77 Metrics does.

**Subheadline:** 21 metrics. A configurable dashboard. CarPlay. Widgets. And a full record of every drive.

---

## Feature sections

### Dashboard

**Heading:** Your metrics, your layout.

The 77 Metrics dashboard is a grid of resizable tiles. Each tile shows one live metric. Seven tile sizes — from a compact 1×1 cell to a full-screen 2×6 — let you control how much space each reading gets.

Organize different metrics across multiple dashboard pages. Swipe between pages while driving. Enable Enhanced Information mode on any page to unlock additional visualizations: pace bars, G-force heat maps, compass overlays, and charts alongside the primary value.

**Key details:**
- 21 configurable metrics
- Up to 12 tiles per page
- 7 tile size levels
- Multiple pages with independent settings
- Portrait and landscape layouts

---

### Metrics

**Heading:** 21 ways to understand your drive.

| Category | Metrics |
|----------|---------|
| Speed | Speed, Average Speed, Moving Avg, Max Speed, Vertical Speed |
| Distance | Distance, Trip Distance |
| Elevation | Altitude, Grade, Elevation Gain, Elevation Loss, Net Elevation, Elevation Profile |
| Time | Elapsed Time, Moving Time, Stopped Time |
| Navigation | Heading, Direction |
| G-Force | G-Force, Max G |
| GPS Info | GPS (coordinates + accuracy) |

Every metric updates approximately once per second during an active drive. Metrics that require accumulated data (like Elevation Gain or Max Speed) show zero at drive start and grow from there.

---

### Elevation

**Heading:** Altitude data you can trust.

GPS altitude has a known limitation: it drifts. 77 Metrics addresses this by combining GPS altitude with the iPhone's built-in barometric altimeter. The barometric sensor is highly sensitive to small altitude changes; GPS provides the absolute anchor. Together they produce more stable, accurate elevation readings than either source alone.

**What you can track:**
- Altitude above sea level, updated continuously
- Elevation Gain — total climbing across the full drive
- Elevation Loss — total descent across the full drive
- Net Elevation — how high you are relative to your starting point
- Grade — the current road gradient as a percentage
- Elevation Profile — a chart of altitude over the full drive

---

### Drive recording

**Heading:** Record. Pause. Resume. Recover.

Start a drive with a tap. Pause to exclude waiting time — stop lights, rest stops, fuel stops — without ending the session. Resume and pick up exactly where you left off.

Every drive is checkpointed to disk automatically, approximately every 30 seconds. If the app closes unexpectedly, the recording survives. On next launch, 77 Metrics offers to recover the interrupted session so you can review and save it normally.

After stopping, continue the most recently saved drive as a new segment. Both segments merge into a single drive record with combined statistics.

---

### Trip history and summaries

**Heading:** Every drive, reviewed in full.

After every drive, a summary screen shows:
- Route on an interactive map
- Speed over time — scrub to any moment
- Elevation over time — synced to the speed chart
- Vertical speed — climb and descent rates
- G-force summary and heat map
- GPS accuracy statistics

Group related drives into a named trip — outbound and return legs of a road trip, or a multi-day journey. Trip groups appear alongside individual drives in history.

---

### Export

**Heading:** Take your data anywhere.

Export any drive in two standard formats:

**CSV** — a plain-text file with one GPS sample per row. Columns include timestamp (ISO 8601), latitude and longitude (7 decimal places), altitude (meters), speed (m/s), course (degrees), and horizontal and vertical accuracy. Suitable for spreadsheets, pandas, or any data analysis workflow.

**GPX 1.1** — with Garmin TrackPointExtension v2, compatible with Garmin Connect, Strava, Komoot, and most GPS applications. Each recording segment within a drive is a separate `<trkseg>`, so paused gaps are not represented as straight-line connections.

Trip groups export as a combined GPX with one `<trk>` per drive.

---

### CarPlay

**Heading:** Your metrics on your car's screen.

77 Metrics appears in the CarPlay app launcher and displays a scrollable list of configured metrics on your vehicle's built-in display. Choose up to 8 metrics. The list updates every second during an active drive.

CarPlay is a display — drive recording is always controlled from the iPhone app.

---

### Widgets and Live Activities

**Heading:** Metrics wherever you look.

**Home Screen widget (small):** Shows one configurable metric during an active drive. When idle, shows a Start Drive button.

**Lock Screen circular widget:** Shows one configurable metric at a glance. Tap to start a drive when idle.

**Lock Screen rectangular widget:** Shows up to two configurable metrics during an active drive.

**Live Activity:** Keeps up to two metrics visible on the Lock Screen and in the Dynamic Island throughout the drive. Updates continuously while recording; shows the paused state when a drive is paused.

Configure all widget metrics in Settings → CarPlay & Widgets.

---

### Privacy

**Heading:** Your data stays yours.

77 Metrics records GPS, barometric, and accelerometer data during active drives. All data is stored on your iPhone. Nothing is transmitted to any server. No account is required.

You can delete individual drives at any time. Deleting the app removes all associated data from your device.

---

## Requirements

- iPhone with iOS 17 or later
- Location Services enabled
- CarPlay: compatible vehicle or aftermarket head unit
- Live Activities: iOS 16.1 or later, enabled in iOS Settings
