# All metrics

77 Metrics provides 21 metrics grouped into seven categories. Every metric can be placed on any dashboard page; each page can hold up to 12 tiles.

## Complete metric list

| Metric | Label | Short | Category |
|--------|-------|-------|----------|
| Speed | Speed | SPD | [Speed](speed.md) |
| Average Speed | Average Speed | AVG | [Speed](speed.md) |
| Moving Avg | Moving Avg | MAVG | [Speed](speed.md) |
| Max Speed | Max Speed | MAX | [Speed](speed.md) |
| Vertical Speed | Vertical Speed | VSP | [Speed](speed.md) |
| Distance | Distance | DST | [Distance](distance.md) |
| Trip Distance | Trip Distance | TRP | [Distance](distance.md) |
| Altitude | Altitude | ALT | [Elevation](elevation.md) |
| Grade | Grade | GRD | [Elevation](elevation.md) |
| Elevation Gain | Elevation Gain | GAIN | [Elevation](elevation.md) |
| Elevation Loss | Elevation Loss | LOSS | [Elevation](elevation.md) |
| Net Elevation | Net Elevation | ELEV | [Elevation](elevation.md) |
| Elevation Profile | Elevation Profile | PROF | [Elevation](elevation.md) |
| Elapsed Time | Elapsed Time | TIME | [Time](time.md) |
| Moving Time | Moving Time | MVG | [Time](time.md) |
| Stopped Time | Stopped Time | STP | [Time](time.md) |
| Heading | Heading | HDG | [Navigation](navigation.md) |
| Direction | Direction | DIR | [Navigation](navigation.md) |
| G-Force | G-Force | G | [G-Force](g-force.md) |
| Max G | Max G | MAXG | [G-Force](g-force.md) |
| GPS | GPS | GPS | [GPS Info](gps.md) |

## How metrics update

All metrics update as GPS readings arrive, approximately once per second. Metrics that require accumulated data (such as Max Speed or Elevation Gain) are always available but show zero or a dash until sufficient data exists.

## The dash (—)

A dash means the metric cannot be calculated from available data. Common reasons:

- GPS has not yet acquired a fix (Speed, Altitude, Heading, Direction)
- Not enough data has been recorded (Vertical Speed, Grade)
- Barometric and GPS altitude have not yet converged (Net Elevation)
- No moving time has elapsed (Moving Avg)
