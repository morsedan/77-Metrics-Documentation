# Speed metrics

Five metrics measure the speed or rate of movement of the vehicle.

---

## Speed

**Label:** Speed · **Short:** SPD · **Unit:** mph or km/h

Current speed reported directly by GPS. Updates once per second.

Shows a dash (—) when GPS has not yet acquired a fix or when the reported speed is negative (which GPS uses to signal an invalid reading).

---

## Average Speed

**Label:** Average Speed · **Short:** AVG · **Unit:** mph or km/h

Total distance traveled divided by total elapsed time since drive start. Pauses are excluded from elapsed time, so Average Speed reflects actual driving pace rather than wall-clock time.

In Enhanced Information mode at Size 2 or larger, the tile also shows:
- A bar comparing current speed to twice the average (the bar is centered at average speed)
- Pace text: "On pace" when within 0.5 mph/km/h of the average, otherwise a signed difference such as "+12 mph" or "−8 km/h"

Shows a dash (—) when elapsed time is zero (immediately after drive start).

---

## Moving Avg

**Label:** Moving Avg · **Short:** MAVG · **Unit:** mph or km/h

Total distance divided by moving time only. Moving time excludes time spent stopped (below approximately 3.6 km/h / 1 m/s). Moving Avg is always higher than or equal to Average Speed.

In Enhanced Information mode at Size 2 or larger, the tile shows the same pace bar and difference text as Average Speed, but relative to the moving average.

Shows a dash (—) until the vehicle has moved for at least one GPS interval.

---

## Max Speed

**Label:** Max Speed · **Short:** MAX · **Unit:** mph or km/h

The highest speed recorded during the current drive. Updates whenever a new speed reading exceeds the previous maximum.

In Enhanced Information mode at Size 2 or larger, the tile shows a progress bar (current speed as a fraction of max speed) and a gap value such as "−15 mph" or "At max."

Shows a dash (—) until at least one valid speed reading has been recorded.

---

## Vertical Speed

**Label:** Vertical Speed · **Short:** VSP · **Unit:** ft/min or m/min

Rate of altitude change — positive when climbing, negative when descending. Calculated from the barometric altimeter using a rolling time window. More stable than a GPS-only calculation.

Shows a dash (—) when insufficient altitude data has been collected to compute a reliable rate.
