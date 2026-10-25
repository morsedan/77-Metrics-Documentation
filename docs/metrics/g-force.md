# G-Force metrics

Two metrics measure the acceleration forces experienced during the drive.

## How G-force is measured

77 Metrics uses the iPhone's accelerometer, sampled at approximately 50 Hz. The app tracks longitudinal G-force (acceleration and braking along the direction of travel) and lateral G-force (cornering forces).

With Enhanced Information enabled at Size 2 or larger, the G-Force tile adds a cumulative 2D heat map alongside the radial vector meter. The heat map records all G-force events during the drive on a grid: the color of each cell reflects how often and how strongly forces occurred in that direction, using a dull-red-to-white ramp (low to high intensity). A dot marks the current position on the map.

---

## G-Force

**Label:** G-Force · **Short:** G · **Unit:** G

Current longitudinal acceleration force. Positive values indicate forward acceleration (speeding up); negative values indicate deceleration (braking).

Values are formatted with a leading sign: "+0.35 G" for acceleration, "−0.42 G" for braking. Displays "0.00 G" when forces are below 0.005 G.

G-Force is always available once the drive starts; it does not require GPS.

---

## Max G

**Label:** Max G · **Short:** MAXG · **Unit:** G

The highest G-force magnitude recorded during the drive. Unlike the live G-Force tile, Max G tracks the peak over the full drive and never decreases during a session.

Shows a dash (—) until the first valid G-force reading is recorded.

For continued drives (resumed from a previous drive), Max G carries forward the maximum from the previous segment, so it always reflects the highest force across the full combined drive.
