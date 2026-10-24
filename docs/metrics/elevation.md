# Elevation metrics

Six metrics describe the vehicle's altitude and how it has changed during the drive.

## Altitude fusion

77 Metrics combines GPS altitude and the iPhone's barometric altimeter to produce a more accurate and stable altitude reading than either source alone. The barometric sensor is highly precise for small changes but drifts over time; GPS provides an absolute reference that anchors the barometer.

On drive start, the app waits up to 10 seconds for the two sources to converge. Until they do, altitude-dependent metrics may show dashes or display a stabilization indicator.

---

## Altitude

**Label:** Altitude · **Short:** ALT · **Unit:** ft or m (above sea level)

Current elevation above sea level. Prefers the fused (barometric + GPS) altitude when available; falls back to GPS altitude alone.

Shows a dash (—) when no valid altitude reading exists.

---

## Grade

**Label:** Grade · **Short:** GRD · **Unit:** %

Current road gradient as a percentage. Positive values indicate uphill; negative values indicate downhill.

Grade is calculated from the barometric altimeter and GPS-derived distance. It requires a minimum amount of distance to have been traveled and is not calculated when the drift guard detects abnormal barometric behavior (such as driving through a car wash or entering a pressurized tunnel).

Shows a dash (—) when insufficient data is available.

---

## Elevation Gain

**Label:** Elevation Gain · **Short:** GAIN · **Unit:** ft or m

Cumulative altitude gained during the drive. Every time the vehicle climbs, the amount of climb is added to this total. Elevation Gain represents total climbing effort — it increases throughout a hilly drive regardless of net altitude change.

Always shows 0 or a positive value.

---

## Elevation Loss

**Label:** Elevation Loss · **Short:** LOSS · **Unit:** ft or m

Cumulative altitude lost during the drive. Displayed as a positive number (the magnitude of descent). Elevation Loss increases throughout a hilly drive.

Always shows 0 or a positive value.

---

## Net Elevation

**Label:** Net Elevation · **Short:** ELEV · **Unit:** ft or m

The difference between the current altitude and the altitude at the start of the drive. Positive when you are higher than your starting point; negative when lower; near zero when you return to the starting altitude.

Net Elevation is available only after the altitude reading has stabilized (within 10 seconds of drive start). Shows a dash (—) during stabilization.

---

## Elevation Profile

**Label:** Elevation Profile · **Short:** PROF

A mini chart showing how altitude has changed over the course of the drive. The horizontal axis spans the full drive; the vertical axis scales to the observed altitude range.

While the altitude reading is stabilizing at drive start, the tile displays a "Stabilizing altitude…" indicator. The chart begins after stabilization is complete to avoid showing anchor-bias convergence noise as a false initial drop.

Available at Size 3 or larger for meaningful display. Shows a dash at smaller sizes until at least two data points have been recorded.
