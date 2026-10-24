# Content and terminology guidelines

Consistent terminology across support docs, marketing copy, App Store listings, and any future website makes the product easier to understand and search.

---

## App name

- **Always:** 77 Metrics
- **Never:** Seventy-Seven Metrics, 77metrics, 77M, the app, the tool
- Use the full name on first mention in any document. Subsequent mentions may omit "Metrics" only in contexts where it is completely unambiguous.

---

## Key terms

### In-app labels — use these exactly

| Correct term | Do not use |
|-------------|------------|
| **tile** | card, cell, panel, widget (widgets are the Home Screen / Lock Screen items, not dashboard tiles) |
| **metric** | stat, stat tile, reading, data point |
| **dashboard** | main screen, home screen (Home Screen is the iOS concept), display |
| **page** | tab, view, screen (when referring to a dashboard page) |
| **Enhanced Information** | enhanced mode, detailed view, advanced view |
| **drive** | trip (a trip is a named group of drives in history), session |
| **Drive Complete** | end screen, summary, results |
| **Trip History** | drive history, saved drives, log |
| **Start Drive** | begin recording, start recording |
| **Edit Dashboard** | customize, settings (settings is a separate screen) |
| **Edit Layout** | arrange, move tiles |
| **Size 1 – Size 7** | small/medium/large (prefer the numbered size labels) |

### Apple platform terms — follow Apple's capitalization

| Correct | Do not use |
|---------|-----------|
| CarPlay | Carplay, carplay, Apple CarPlay (Apple does not use "Apple CarPlay" in most contexts) |
| iPhone | phone, device, handset |
| iOS 17 or later | iOS 17+, iOS17 |
| Home Screen | home screen (when referring to the iOS Home Screen) |
| Lock Screen | lock screen |
| Dynamic Island | dynamic island |
| Live Activity | live activity |
| App Store | app store |

### Export terms

| Correct | Do not use |
|---------|-----------|
| CSV | csv, .csv file (the format is CSV; the file has a .csv extension) |
| GPX 1.1 | GPX, gpx, .gpx |
| Garmin TrackPointExtension v2 | Garmin extension (be specific when relevant) |

---

## Metric labels

Use the exact in-app label for each metric. Do not abbreviate or rename.

| Label in app | Short label | Do not use |
|-------------|-------------|------------|
| Speed | SPD | Current speed, live speed |
| Average Speed | AVG | Avg speed |
| Moving Avg | MAVG | Moving average speed |
| Max Speed | MAX | Maximum speed, top speed |
| Vertical Speed | VSP | Climb rate, vertical velocity |
| Distance | DST | Odometer, mileage |
| Trip Distance | TRP | Trip odometer |
| Altitude | ALT | Elevation (Altitude is the metric name; Elevation is the category) |
| Grade | GRD | Incline, slope, pitch |
| Elevation Gain | GAIN | Climb |
| Elevation Loss | LOSS | Descent (when referring to the metric) |
| Net Elevation | ELEV | Net altitude change |
| Elevation Profile | PROF | Elevation chart (as a metric name) |
| Elapsed Time | TIME | Total time |
| Moving Time | MVG | Drive time |
| Stopped Time | STP | Idle time |
| Heading | HDG | Compass heading |
| Direction | DIR | Compass direction |
| G-Force | G | G force (no hyphen) |
| Max G | MAXG | Peak G |
| GPS | GPS | GPS Info, GPS data |

---

## Claims guidance

### Allowed

- "21 metrics" — verified from source
- "7 tile size levels" — verified
- "Barometric and GPS altitude fusion" — verified; do not claim specific accuracy numbers
- "Approximately once per second" for live tile updates — verified (1 Hz GPS)
- "Every 30 seconds" for checkpoints — verified
- "GPX 1.1 with Garmin TrackPointExtension v2" — verified from export code
- "No account required" — verified; no server communication in the app
- "Works offline" — verified; GPS is hardware-based
- "CarPlay: up to 8 configurable metrics, display only" — verified; CarPlay is read-only, no drive controls

### Requires care

- "Accurate elevation" — true relative to GPS-only, but avoid implying survey-grade precision
- "Real-time" — use for live tile updates on the dashboard only; avoid for widgets (they update on a schedule)
- "Export to [app]" — say "compatible with" rather than implying a certified integration

### Not allowed

- Performance claims with specific numbers not sourced from the implementation (e.g., "accurate to within 3 meters")
- Claims about safety or driver assistance
- Implied support for motorsport regulatory compliance
- "Free" or pricing claims — price is an App Store decision made separately from documentation

---

## Voice and tone

**Support documentation:** Neutral, precise, second person. "Tap Start Drive" not "You should tap Start Drive" or "Start Drive is tapped."

**Marketing copy:** Warmer, still factual. Short sentences. Lead with benefit. Avoid exclamation points except very sparingly.

**App Store description:** Conventional App Store style — section headers in ALL CAPS are normal here. Bullet points with • are conventional. Keep paragraphs short (2–3 lines).

**Website copy:** Conversational but direct. One sentence to state a benefit, one to explain it. No jargon unless explained.

---

## Screenshot conventions

Filenames use this format: `SURFACE_DESCRIPTION_DEVICE.png`

Examples:
- `dashboard_active-drive_iphone-15-pro.png`
- `trip-summary_elevation-profile_iphone-15-pro.png`
- `dashboard-edit_tile-list_iphone-15-pro.png`
- `carplay_active-drive_display.png`

Screenshot text in docs should describe what is shown without reproducing actual personal data from a real drive.

---

## What this repository does not contain

- Credentials, API keys, or App Store Connect configuration
- Private business plans or financial projections
- Legal documents (privacy policy, EULA) pending review
- Unreleased feature descriptions
- Personally identifiable information from real test drives
